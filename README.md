## New Era of Artificial Intelligence: <br> Unleashing the Power of Large Models in Visual Applications

**ISCAS 2024 Tutorial** (selected for IEEE CASS Continuing Education) <br>
[Jiaying Liu](http://www.wict.pku.edu.cn/struct/people/liujiaying.html), [Wen-Huang Cheng](https://www.csie.ntu.edu.tw/~wenhuang/), and [Shuai Yang](https://williamyang1991.github.io/)<br>
[**Home Page**](https://williamyang1991.github.io/projects/ISCAS2024/index.html) <br>

This repository prodives the slides of our ISCAS 2024 tutorial on `New Era of Artificial Intelligence: Unleashing the Power of Large Models in Visual Applications`

<br>

## Contents

| Title | Speaker | Tutorial Slides 🔥
| :--- | :---------- | :---
|**Specializing Large Models for Domain-Specific Vision Tasks** | Wen-Huang Cheng | [PDF](https://github.com/williamyang1991/ISCAS_Tutorial/blob/main/WenhuangCheng_ISCAS-2024-Tutorial-DSVT-share.pdf)
|**AIGC for Image and Video Generation**  | Shuai Yang | [PDF](https://github.com/williamyang1991/ISCAS_Tutorial/blob/main/ShuaiYang_ISCAS-2024_Tutorial-Generation-share.pdf)
|**Employing Diffusion Models for Low-level Vision** | Jiaying Liu | [PDF](https://github.com/williamyang1991/ISCAS_Tutorial/blob/main/JiayingLiu_ISCAS-2024_Tutorial-Restoration-share.pdf)

<br>

## Specializing Large Models for Domain-Specific Vision Tasks

![overview3](https://github.com/williamyang1991/ISCAS_Tutorial/assets/18130694/1bac37fb-0b81-4227-b8db-2d6fc965887f)

Strategies for Domain-Specific Vision Tasks
- [Fine-tuning](#fine-tuning)
- [Visual-Prompt Tuning](#visual-prompt-tuning)
- [Visual Instruction Tuning](#visual-instruction-tuning)
- [Open Problems](#open-problems)

<br>

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

<br>


## Employing Diffusion Models for Low-level Vision

![overview5](https://github.com/williamyang1991/ISCAS_Tutorial/assets/18130694/e06f7d2d-8117-4032-8002-da233fcc1268)

- [Diffusion for Image Restoration](#diffusion-for-image-restoration)
  - [Training-based](#training-based)
  - [Sampling-based](#sampling-based)
- [Diffusion for Low-light Enhancement](#diffusion-for-low-light-enhancement)
  - [Human Vision](#human-vision)
  - [Machine Vision](#machine-vision)
- [Unified Image Restoration and Enhancement](#unified-image-restoration-and-enhancement)

<br><br>

## Awesome Techniques Introduced in the Tutorial

### Fine-tuning
- [Side-Tuning](https://sidetuning.berkeley.edu/) (ECCV20)
- [TinyTL](https://github.com/mit-han-lab/tinyml/tree/master) (NeurIPS20)
- [MoCo v3](https://github.com/facebookresearch/moco-v3) (ICCV21)
- [VisE](https://github.com/KMnP/vise) (ICCV21)
### Visual-Prompt Tuning
- [VPT](https://github.com/KMnP/vpt) (ECCV22)
- [CoOp](https://github.com/KaiyangZhou/CoOp) (IJCV22)
- [CoCoOp](https://github.com/KaiyangZhou/CoOp) (CVPR22)
- [TaskRes](https://github.com/geekyutao/TaskRes) (CVPR23)
### Visual Instruction Tuning
- [EmoVIT](https://github.com/aimmemotion/emovit) (CVPR24)
- [EmoSet](https://vcc.tech/EmoSet) (ICCV23)
- [InstructBLIP](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) (NeurIPS23)
### Open Problems
#### Hallucination
- [A Survey on Hallucination](https://arxiv.org/abs/2402.00253)
#### Long-context Modeling
- [BLIVA](https://github.com/mlpc-ucsd/BLIVA) (AAAI24)
- [Leave No Context Behind](https://arxiv.org/abs/2404.07143)
#### Robust Automatic Evaluation
- [CLIPScore](https://github.com/jmhessel/clipscore) (EMNLP21)

### Preliminary
- [DDPM](https://hojonathanho.github.io/diffusion/) (NeurIPS20)
- [DDIM](https://github.com/ermongroup/ddim) (ICLR21)
- [Classifier guidance](https://github.com/openai/guided-diffusion) (NeurIPS21)
- [Classifier-free guidance](https://arxiv.org/abs/2207.12598) (NeurIPSW21)
### Image Diffusion Model
#### DALLE Series
- [DALLE2](https://openai.com/dall-e-2/)
- [DALLE3](https://openai.com/index/dall-e-3/)
#### Stable Diffusion Series
- [Latent Diffusion Model](https://github.com/CompVis/latent-diffusion) (CVPR22)
- [SD 1.x](https://github.com/runwayml/stable-diffusion)
- [SD 2.x](https://github.com/Stability-AI/stablediffusion)
- [SD XL](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0) (ICLR24)
- [SD XL Turbo](https://huggingface.co/stabilityai/sdxl-turbo)
- [SD Cascade](https://github.com/Stability-AI/StableCascade) (ICLR24)
- [SD 3](https://stability.ai/news/stable-diffusion-3)
#### Others
- [Midjourney](https://www.midjourney.com/home)
### Image Supporting Model
#### Pre-trained Prior
- [Repaint](https://sde-image-editing.github.io/) (CVPR22)
- [SDEdit](https://github.com/andreas128/RePaint) (CVPR22)
#### Image Editing
- [Prompt-to-Promt](https://github.com/google/prompt-to-prompt) (ICLR23)
- [Plug-and-Play](https://pnp-diffusion.github.io/) (CVPR23)
- [Null-text Inversion](https://null-text-inversion.github.io/) (CVPR23)
#### Model Customization
- [Textual Inversion](https://textual-inversion.github.io/) (ICLR23)
- [Dream Booth](https://dreambooth.github.io/) (CVPR23)
- [LoRA](https://github.com/cloneofsimo/lora) (ICLR22)
- [Imagic](https://imagic-editing.github.io/) (CVPR23)
#### Adding Control
- [ControlNet](https://github.com/lllyasviel/ControlNet) (ICCV23)
- [T2I Adapter](https://github.com/TencentARC/T2I-Adapter) (AAAI24)
### Video Diffusion Model
#### Data-driven Video Model
- [VDM](https://video-diffusion.github.io/) (NeurIPS22)
- [Make-A-Video](https://makeavideo.studio/) (ICLR23)
- [Imagen Video](https://imagen.research.google/video/) 
- [Video LDM](https://research.nvidia.com/labs/toronto-ai/VideoLDM/) (CVPR23)
- [HD-VG-130M](https://github.com/daooshee/HD-VG-130M) (dataset)
- [Panda-70M](https://snap-research.github.io/Panda-70M/) (CVPR24, dataset)
- [Sora](https://openai.com/index/sora/)
#### One-shot Video Model
- [Tune-A-Video](https://github.com/showlab/Tune-A-Video) (ICCV23)
- [Edit-A-Video](https://edit-a-video.github.io/) (ACML23)
- [Video-P2P](https://video-p2p.github.io/) (CVPR24)
#### Zero-shot Video Model
##### Inversion-free model
- [Text2Video-Zero](https://github.com/Picsart-AI-Research/Text2Video-Zero) (ICCV23)
- [ControlVideo](https://github.com/YBYBZhang/ControlVideo) (ICLR24)
- [Rerender-A-Video](https://www.mmlab-ntu.com/project/rerender/) (SIGGRAPH Asia23)
- [FRESCO](https://www.mmlab-ntu.com/project/fresco/) (CVPR24)
- [Fairy](https://fairy-video2video.github.io/) (CVPR24)
##### Inversion-based model
- [FateZero](https://github.com/ChenyangQiQi/FateZero) (ICCV23)
- [Pixel2Video](https://duyguceylan.github.io/pix2video.github.io/) (ICCV23)
- [TokenFlow](https://diffusion-tokenflow.github.io/) (ICLR24)
- [FLATTEN](https://flatten-video-editing.github.io/) (ICLR24)
- [VidToMe](https://vidtome-diffusion.github.io/) (CVPR24)


### Diffusion for Image Restoration
#### Training-based
- [SR3](https://iterative-refinement.github.io/) (TPAMI22)
- [StableSR](https://iceclear.github.io/projects/stablesr/)
- [DiffIR](https://github.com/Zj-BinXia/DiffIR) (ICCV23)
#### Sampling-based
- [DDRM](https://ddrm-ml.github.io/) (NeurIPS22)
- [DiffPIR](https://yuanzhi-zhu.github.io/DiffPIR/) (CVPRW23)
- [GDP](https://generativediffusionprior.github.io/) (CVPR23)
- [DPS](https://dps2022.github.io/diffusion-posterior-sampling-page/) (ICLR23)
- [BoostDiffSR](https://arxiv.org/abs/2305.15357) (ICLR24)
### Diffusion for Low-light Enhancement
#### Human Vision
##### Acceleration
- [PyDiff](https://github.com/limuloo/PyDIff) (IJCAI23)
- [DiffLL](https://github.com/JianghaiSCU/Diffusion-Low-Light) (TOG23)
##### Interpretability
- [Diff-Retinex](https://arxiv.org/abs/2308.13164) (ICCV23)
- [ExposureDiffusion](https://github.com/wyf0912/ExposureDiffusion) (ICCV23)
- [QuadPrior](https://daooshee.github.io/QuadPrior-Website/) (CVPR24)
#### Machine Vision
- [DiD](https://ccnguyen.github.io/diffusion-in-the-dark/) (WACV24)
### Unified Image Restoration and Enhancement
- [Palette](https://iterative-refinement.github.io/palette/) (SIGGRAPH22)
- [UCDIR](https://zhangyi-3.github.io/project/UCDIR/) (NeurIPS23)
- [GDP](https://generativediffusionprior.github.io/) (CVPR23)

<br>

## Acknowledgments
Thanks to [Wenjing Wang](https://daooshee.github.io/website/), [Yiyang Ma](https://realpasu.github.io/), [Zejia Fan](https://zahrafan.github.io/) and [Haowei Kuang](https://sustechellison.github.io/ellison_kuang.github.com/) for their supports during the preparation of the slides.
