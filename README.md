# awesome-layout-to-image

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re/) [![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com/) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://https://github.com/earth-insights/awesome-layout-to-image/graphs/commit-activity)

<!-- ![img](https://i.imgur.com/Ky2jxnj.png) -->

## multi-layout to image

|    Abbreviation    |         Type         | Title                                                        | Publication |                            Paper                             |                          Code                           |
| :----------------: | :------------------: | ------------------------------------------------------------ | :---------: | :----------------------------------------------------------: | :-----------------------------------------------------: |
|   **ControlNet**   | layout,(text)->image | **Adding Conditional Control to Text-to-Image Diffusion Models** |  ICCV'2023  |        [ControlNet](https://arxiv.org/abs/2302.05543)        |    [link](https://github.com/lllyasviel/ControlNet)     |
|  **T2I-Adapter**   | layout,(text)->image | **T2I-Adapter: Learning Adapters to Dig Out More Controllable Ability for Text-to-Image Diffusion Models** |  AAAI'2024  | [T2I-Adapter](https://ojs.aaai.org/index.php/AAAI/article/view/28226) |    [link](https://github.com/TencentARC/T2I-Adapter)    |
| **Uni-ControlNet** | layout,(text)->image | **Uni-ControlNet: All-in-One Control to Text-to-Image Diffusion Models** |  NIPS'2024  |      [Uni-ControlNet](https://arxiv.org/abs/2305.16322)      | [link](https://github.com/ShihaoZhaoZSH/Uni-ControlNet) |
|    **CRS-Diff**    | layout,(text)->image | **CRS-Diff: Controllable Generative Remote Sensing Foundation Modeln** | arXiv'2024  |         [CRS-Diff](https://arxiv.org/abs/2403.11614)         |      [link](https://github.com/Sonettoo/CRS-Diff)       |
|    **GeoSynth**    | layout,(text)->image | **GeoSynth: Contextually-Aware High-Resolution Satellite Image Synthesis** | CVPRW'2024  |         [GeoSynth](https://arxiv.org/abs/2404.06637)         |        [link](https://github.com/mvrl/GeoSynth)         |

## mask to image

|Abbreviation|Type|Title|Publication|Paper|Code|
|:---:|:---:|---|:---:|:---:|:---:|
|**OASIS**|mask->image|**You Only Need Adversarial Supervision for Semantic Image Synthesis**|ICLR'2021|[OASIS](https://arxiv.org/abs/2012.04781)|[link](https://github.com/boschresearch/OASIS)|
|**/**|mask->image|**Mask Conditional Synthetic Satellite Imagery**|ICLRW'2023|[paper](https://arxiv.org/abs/2302.04305)|[link](https://github.com/ms-synthetic-satellite-image/synthetic-satellite-imagery)|
|**FreestyleNet**|mask,text->image|**Freestyle Layout-to-Image Synthesis**|CVPR'2023|[FreestyleNet](https://arxiv.org/abs/2303.14412)|[link](https://github.com/essunny310/FreestyleNet)|
|**Changen**|mask->image|**Scalable Multi-Temporal Remote Sensing Change Data Generation via Simulating Stochastic Change Process**|ICCV'2023|[Changen](https://arxiv.org/abs/2309.17031)|[link](https://github.com/Z-Zheng/Changen)|
|**Label Freedom**|->image,mask|**Label Freedom: Stable Diffusion for Remote Sensing Image Semantic Segmentation Data Generation**|BigData'2023|[Label Freedom](https://www.researchgate.net/profile/Shenglong-Chen-2/publication/375495451_Label_Freedom_Stable_Diffusion_for_Remote_Sensing_Image_Semantic_Segmentation_Data_Generation/links/65a9f8b5f323f74ff1cc4c03/Label-Freedom-Stable-Diffusion-for-Remote-Sensing-Image-Semantic-Segmentation-Data-Generation.pdf)|/|
|**DP-SIMS**|mask->image|**Unlocking Pre-trained Image Backbones for Semantic Image Synthesis**|arXiv'2023|[DP-SIMS](https://arxiv.org/abs/2312.13314)|/|
|**Dataset Diffusion**|text->image,mask|**Dataset Diffusion: Diffusion-based Synthetic Dataset Generation for Pixel-Level Semantic Segmentation**|NIPS'2023|[Dataset Diffusion](https://arxiv.org/abs/2309.14303)|[link](https://github.com/VinAIResearch/Dataset-Diffusion)|
|**FreeMask**|mask,text->image|**FreeMask: Synthetic Images with Dense Annotations Make Stronger Segmentation Models**|NIPS'2023|[FreeMask](https://arxiv.org/abs/2310.15160)|[link](https://github.com/LiheYoung/FreeMask)|
|**ALDM**|mask,(text)->image|**Adversarial Supervision Makes Layout-to-Image Diffusion Models Thrive**|ICLR'2024|[ALDM](https://arxiv.org/abs/2401.08815)|[link](https://github.com/boschresearch/ALDM)|
|**SatSynth**|->image,mask|**SatSynth: Augmenting Image-Mask Pairs through Diffusion Models for Aerial Semantic Segmentation**|CVPR'2024|[SatSynth](http://arxiv.org/abs/2403.16605)|/|
|**PLACE**|mask,text->image|**PLACE: Adaptive Layout-Semantic Fusion for Semantic Image Synthesis**|CVPR'2024|[PLACE](https://arxiv.org/abs/2403.01852)|[link](https://github.com/cszy98/PLACE)|
|**ChangeAnywhere**|mask->image|**ChangeAnywhere: Sample Generation for Remote Sensing Change Detection via Semantic Latent Diffusion Model**|arXiv'2024|[ChangeAnywhere](https://arxiv.org/abs/2404.08892)|[link](https://github.com/tangkai-RS/ChangeAnywhere)|

## bbox to image

|Abbreviation|Type|Title|Publication|Paper|Code|
|:---:|:---:|---|:---:|:---:|:---:|
|**ReCo**|layout,region caption->image|**ReCo: Region-Controlled Text-to-Image Generation**|CVPR'2023|[ReCo](https://openaccess.thecvf.com/content/CVPR2023/papers/Yang_ReCo_Region-Controlled_Text-to-Image_Generation_CVPR_2023_paper.pdf)|[link](https://github.com/microsoft/ReCo)
|**SSMG**|layout,region caption->image|**SSMG: Spatial-Semantic Map Guided Diffusion Model for Free-Form Layout-to-Image Generation**|AAAI'2024|[SSMG](https://arxiv.org/pdf/2308.10156v2.pdf)|
|**LayoutDiff**|layout,instance class->image|**LayoutDiffusion: Controllable Diffusion Model for Layout-to-image Generation**|CVPR'2023|[LayoutDiff](https://openaccess.thecvf.com/content/CVPR2023/html/Zheng_LayoutDiffusion_Controllable_Diffusion_Model_for_Layout-to-Image_Generation_CVPR_2023_paper.html)|[link](https://github.com/ZGCTroy/LayoutDiffusion)
|**LAW-Diffusion**|layout,instance class->image|**LAW-Diffusion: Complex Scene Generation by Diffusion with Layouts**|ICCV'2023|[LAW-Diffusion](https://openaccess.thecvf.com/content/ICCV2023/papers/Yang_LAW-Diffusion_Complex_Scene_Generation_by_Diffusion_with_Layouts_ICCV_2023_paper.pdf)|

## key point to image

|Abbreviation|Title|Publication|Paper|Code|
|:---:|---|:---:|:---:|:---:|


...
