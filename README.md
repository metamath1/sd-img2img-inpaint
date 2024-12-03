# Image-to-Image and Inpainting Pipeline from Scratch

이 저장소에는 **Stable Diffusion 1.5**를 사용하여 `image2image` 및 `inpainting` 파이프라인을 처음부터 구현합니다.
이 파이프라인은 [Diffusers](https://github.com/huggingface/diffusers)를 사용하였으며, 누구나 쉽게 읽고 이해하기 쉽도록 만들어졌습니다.
This repository contains a from-scratch implementation of `image2image` and `inpainting` pipelines using **Stable Diffusion 1.5**. 
The pipeline is built with [Diffusers](https://github.com/huggingface/diffusers) and is designed for ease of understanding.


---

## 🚀 Features
- **Image-to-Image Translation**: Generate modified images using a given input image and textual prompts.
- **Inpainting**: Fill or modify parts of an image based on a mask and textual description.

---

## 📂 File Structure
- `img2img_inpaint_scratch.ipynb`: The Jupyter Notebook containing the full implementation of the pipeline.

---

## 🛠️ Requirements
이 프로젝트는 T4가 지원되는 구글 Colab에서 실행됩니다. This project is designed to run on **Google Colab** with a **T4 GPU**. Ensure you select a GPU runtime in Colab before running the notebook. 

---

## 📖 Usage

### 1. Clone the repository:
```bash
git clone https://github.com/your-username/stable-diffusion-pipeline.git
cd stable-diffusion-pipeline
```

### 2. Open the Jupyter Notebook:
Make sure you have Jupyter installed. Open the notebook with:
```bash
jupyter notebook img2img_inpaint_scratch.ipynb
```

### 3. Image-to-Image Translation:
노트북에서 `PIPELINE_MODE`를 `img2img`로 설정합니다.
In the notebook, set `PIPELINE_MODE` to `img2img`.

### 4. Inpainting:
노트북에서 `PIPELINE_MODE`를 `inpaint`로 설정합니다.
In the notebook, set `PIPELINE_MODE` to `inpaint`.

---

## 🎨 Examples
### Image-to-Image Example:
| Input Image and Generated Image           |
|-------------------------|
| ![Output](grid_output_img2img.png) |

### Inpainting Example:
| Input Image and Generated Image           |
|-------------------------|
| ![Output](grid_output_inpaint.png) |


---

## 📝 Notes
- 이 파이프라인은 `runwayml/stable-diffusion-v1-5`을 기반으로 작성되었습니다. This pipeline is based on the `runwayml/stable-diffusion-v1-5` model.
- 자세한 설명은 `img2img_inpaint_scratch.ipynb`파일의 주석을 참고하세요.For detailed explanation of the implementation, refer to the comments in `img2img_inpaint_scratch.ipynb`.

---

## 📜 License
This repository is distributed under the MIT License. See `LICENSE` for more information.
