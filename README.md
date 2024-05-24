## New Era of Artificial Intelligence: <br> Unleashing the Power of Large Models in Visual Applications

**ISCAS 2024 Tutorial** (selected for IEEE CASS Continuing Education) <br>
[Jiaying Liu](http://www.wict.pku.edu.cn/struct/people/liujiaying.html), [Wen-Huang Cheng](https://www.csie.ntu.edu.tw/~wenhuang/), and [Shuai Yang](https://williamyang1991.github.io/)<br>
[**Home Page**](https://williamyang1991.github.io/projects/ISCAS2024/index.html) <br>

This repository prodives the slides of our ISCAS 2024 tutorial on `New Era of Artificial Intelligence: Unleashing the Power of Large Models in Visual Applications`

## Contents

| Title | Speaker | tutorial slides 
| :--- | :---------- | :---
|**Specializing Large Models for Domain-Specific Vision Tasks** | Wen-Huang Cheng | -
|**AIGC for Image and Video Generation**  | Shuai Yang | [PDF](https://github.com/williamyang1991/ISCAS_Tutorial/blob/main/JiayingLiu_ISCAS-2024_Tutorial-Restoration-share.pdf)
|**Employing Diffusion Models for Low-level Vision** | Jiaying Liu | [PDF](https://github.com/williamyang1991/ISCAS_Tutorial/blob/main/ShuaiYang_ISCAS-2024_Tutorial-Generation-share.pdf)


## AIGC for Image and Video Generation

![overview1](https://github.com/williamyang1991/ISCAS_Tutorial/assets/18130694/8d630440-d424-4ceb-bf7c-013e22669d89)

- [Preliminary](#preliminary)
- [Image Diffusion Model](#image-diffusion-model)
- [Image Supporting Model](#image-supporting-model)
  - [Pre-trained Prior](#pre-trained-prior)
  - [Image Editing](#image-editing)
  - [Customization](#model-customization)
  - [Control](#adding-control)
- [Video Diffusion Model](#video-diffusion-model)
  - [Data-driven Video Model](#data-driven-video-model)
  - [One-shot Video Model](#one-shot-video-model)
  - [Zero-shot Video Model](#zero-shot-video-model)

## Employing Diffusion Models for Low-level Vision

![overview5](https://github.com/williamyang1991/ISCAS_Tutorial/assets/18130694/e06f7d2d-8117-4032-8002-da233fcc1268)

- [Diffusion for Image Restoration](#diffusion-for-image-restoration)
  - [Training-based](#restore1)
  - [Sampling-based](#restore2)
- [Diffusion for Low-light Enhancement](#diffusion-for-low-light-enhancement)
  - [Human Vision](#enhance1)
  - [Machine Vision](#enhance2)
- [Unified Image Restoration and Enhancement](#unified-image-restoration-and-enhancement)


### Preliminary
DDPM
DDIM (ICLR21)
Classifier guidance (NeurIPS21)
Classifier-free guidance (NeurIPSW21)

### Image Diffusion Model
DALLE2
Latent Diffusion Model (CVPR22)
#### Stable Diffusion Series
SD 1.x
SD 2.x
SD XL (ICLR24)
SD XL Turbo
SD Cascade
SD 3
DALLE3
Midjourney
### Image Supporting Model
#### Pre-trained Prior
Repaint (CVPR22)
SDEdit (CVPR22)
#### Image Editing
Prompt-to-Promt (ICLR23)
Plug-and-Play (CVPR23)
Null-text Inversion (CVPR23)
#### Model Customization
Textual Inversion (ICLR23)
Dream Booth (CVPR23)
LoRA (ICLR22)
Imagic (CVPR23)
#### Adding Control
ControlNet (ICCV23)
T2I Adapter (AAAI24)
### Video Diffusion Model
VDM (NeurIPS22)
Make-A-Video (ICLR23)
Imagen Video 
Video LDM (CVPR23)
HD-VG-130M (dataset)
Panda-70M (CVPR24, dataset)
Sora
#### Data-driven Video Model
#### One-shot Video Model
Tune-A-Video (ICCV23)
Edit-A-Video (ACML 23)
Video-P2P (CVPR24)
#### Zero-shot Video Model
##### Inversion-free model
Text2Video-Zero (ICCV23)
ControlVideo (ICLR24)
Rerender-A-Video (SIGGRAPH Asia23)
FRESCO (CVPR24)
Fairy (CVPR24)
##### Inversion-based model
FateZero (ICCV23)
Pixel2Video (ICCV23)
TokenFlow (ICLR24)
FLATTEN (ICLR24)
VidToMe (CVPR24)
