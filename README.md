# Awesome-Motion-Style-Transfer

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collection of papers about motion style transfer, motion stylization, or stylized motion generation.

> Feel free to create a PR or an issue.  (Pull Request is preferred)


**Outline**

- [0. Survey](#0-survey)
- [1. Motion Style Transfer](#1-motion-style-transfer)
- [2. Multi-modal Motion Stylization](#2-multi-modal-motion-stylization)
- [3. Stylized Motion Generation](#3-stylized-motion-generation)

---


## 0. Survey

| Paper | Venue | Code/Project Link |
| --- | --- | --- |
| [Motion Style Transfer: Methods, Challenges, and Future Directions](https://link.springer.com/chapter/10.1007/978-981-95-0100-7_4) | CASA 2025 |  |


## 1. Motion Style Transfer

> Inputs: content (motion) + style (reference motion)

- Whole-body-level

| Paper | Venue | Code/Project Link |
| --- | --- | --- |
| [Motion Style Slider: Endpoint-Supervised Continuous Style Control for Human Motion Diffusion](https://liaochenchieh.com/assets/pdf/motion-style-slider-eccv-2026.pdf) | ECCV 2026 | [webpage](https://liaochenchieh.com/projects/motion-style-slider/) |
| [STyMo: Fast and Controllable Few-Shot Motion Style Transfer](https://dl.acm.org/doi/10.1145/3811356) | ACM TOG (SIGGRAPH 2026) | [code](https://github.com/facebookresearch/STyMo) |
| [VQ-Style: Disentangling Style and Content in Motion with Residual Quantized Representations](https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.70377) | EG 2026 |  |
| [AStF: Motion Style Transfer via Adaptive Statistics Fusor](https://dl.acm.org/doi/10.1145/3746027.3754938) | ACM MM 2025 | [code](https://github.com/CHMimilanlan/AStF) |
| [Decoupling Contact for Fine-Grained Motion Style Transfer](https://dl.acm.org/doi/full/10.1145/3680528.3687609) | SIGGRAPH Asia 2024 | |
| [Generative Human Motion Stylization in Latent Space](https://openreview.net/pdf?id=daEqXJ0yZo) | ICLR 2024 | [code](https://github.com/Murrol/GenMoStyle-code) [webpage](https://yxmu.foo/GenMoStyle/) |
| [Arbitrary Motion Style Transfer with Multi-Condition Motion Latent Diffusion Model](https://openaccess.thecvf.com/content/CVPR2024/papers/Song_Arbitrary_Motion_Style_Transfer_with_Multi-condition_Motion_Latent_Diffusion_Model_CVPR_2024_paper.pdf) | CVPR 2024 | [code](https://github.com/XingliangJin/MCM-LDM.git) |
| [MoST: Motion Style Transformer between Diverse Action Contents](https://openaccess.thecvf.com/content/CVPR2024/html/Kim_MoST_Motion_Style_Transformer_Between_Diverse_Action_Contents_CVPR_2024_paper.html) | CVPR 2024 | [code](https://github.com/Boeun-Kim/MoST) |
| [Scalable Motion Style Transfer with Constrained Diffusion Generation](https://ojs.aaai.org/index.php/AAAI/article/view/28889) | AAAI 2024 | |
| [Diffusion-based Human Motion Style Transfer with Semantic Guidance](https://onlinelibrary.wiley.com/doi/10.1111/cgf.15169) | CGF (SCA 2024) | [code](https://github.com/hlcdyy/diffusion-based-motion-style-transfer) |
| [SMCD: High Realism Motion Style Transfer via Mamba-based Diffusion](https://arxiv.org/abs/2405.02844) | arxiv 24.05 | |
| [FineStyle: Semantic-Aware Fine-Grained Motion Style Transfer with Dual Interactive-Flow Fusion](https://ieeexplore.ieee.org/abstract/document/10269731/) | IEEE TVCG 2023 | [code](https://github.com/XingliangJin/Fine-Style.git) |
| [Style-ERD: Responsive and Coherent Online Motion Style Transfer](https://openaccess.thecvf.com/content/CVPR2022/papers/Tao_Style-ERD_Responsive_and_Coherent_Online_Motion_Style_Transfer_CVPR_2022_paper.pdf) | CVPR 2022 | [code](https://github.com/tianxintao/Online-Motion-Style-Transfer) [webpage](https://tianxintao.github.io/Online-Motion-Style-Transfer/) |
| [Unpaired Motion Style Transfer with Motion-oriented Projection Flow Network](https://ieeexplore.ieee.org/abstract/document/9859776/) | ICME 2022 |  |
| [Real-Time Style Modelling of Human Locomotion via Feature-Wise Transformations and Local Motion Phases](https://dl.acm.org/doi/abs/10.1145/3522618) | CGIT 2022 | [code](https://github.com/ianxmason/local-phases) |
| [Diverse Motion Stylization for Multiple Style Domains via Spatial-Temporal Graph-Based Generative Model](https://dl.acm.org/doi/abs/10.1145/3480145) | CGIT 2021 | [code](https://github.com/soomean/Diverse-Motion-Stylization) |
| [Autoregressive Stylized Motion Synthesis with Generative Flow](https://openaccess.thecvf.com/content/CVPR2021/html/Wen_Autoregressive_Stylized_Motion_Synthesis_With_Generative_Flow_CVPR_2021_paper.html) | CVPR 2021 | [code](https://github.com/IGLICT/Stylemotion) |
| [Unpaired Motion Style Transfer from Video to Animation](https://dl.acm.org/doi/10.1145/3386569.3392469) | ACM TOG (SIGGRAPH 2020) | [code](https://github.com/DeepMotionEditing/deep-motion-editing) [webpage](https://deepmotionediting.github.io/style_transfer) |
| [Few-shot Learning of Homogeneous Human Locomotion Styles](https://doi.org/10.1111/cgf.13555) | CGF 2018 | |
| [Fast Neural Style Transfer for Motion Data](https://ieeexplore.ieee.org/abstract/document/8013475) | CGA 2017 | |
| [Spectral Style Transfer for Human Motion between Independent Actions](https://dl.acm.org/doi/10.1145/2897824.2925955) | ACM TOG (SIGGRAPH 2016) | |
| [A Deep Learning Framework For Character Motion Synthesis and Editing](https://dl.acm.org/doi/abs/10.1145/2897824.2925975) | ACM TOG (SIGGRAPH 2016) | [webpage](https://theorangeduck.com/page/deep-learning-framework-character-motion-synthesis-and-editing) |
| [Realtime Style Transfer for Unlabeled Heterogeneous Human Motion](https://dl.acm.org/doi/abs/10.1145/2766999) | ACM TOG 2015 | |


- Body-part-level

| Paper | Venue | Code/Project Link |
| --- | --- | --- |
| [MoSAIC: Aligned Intervention Supervision for Part-Local Motion Style Transfer](https://arxiv.org/abs/2607.26304) | arxiv 26.07 | [code](https://github.com/UTSA-VIRLab/MoSAIC) |
| [Motion Puzzle: Arbitrary Motion Style Transfer by Body Part](https://dl.acm.org/doi/full/10.1145/3516429) | ACM TOG (SIGGRAPH 2022) | [code](https://github.com/DK-Jang/motion_puzzle) |

## 2. Multi-modal Motion Stylization

> Inputs: content (motion) + style (text / reference motion / image / video)

| Paper | Venue | Code/Project Link |
| --- | --- | --- |
| [Flexible Motion Stylization via Multi-modality Latent Diffusion Model](https://ieeexplore.ieee.org/abstract/document/11661589/) | TPAMI 2026 |  |
| [Generative Motion Stylization of Cross-structure Characters within Canonical Motion Space](https://dl.acm.org/doi/abs/10.1145/3664647.3680864) | ACM MM 2024 |  |


## 3. Stylized Motion Generation

> Inputs: content (text) + style (text / reference motion)

| Paper | Venue | Code/Project Link |
| --- | --- | --- |
| [Stylized Text-to-Motion Generation via Hypernetwork-Driven Low-Rank Adaptation](https://dl.acm.org/doi/10.1145/3799902.3811205) | SIGGRAPH 2026 | [code](https://github.com/junhyukjeon/style-salad) [webpage](https://junhyukjeon.github.io/projects/style-salad/) |
| [Stylized Text-to-Motion Synthesis Via Multi-Condition Latent Diffusion](https://ieeexplore.ieee.org/abstract/document/11461022) | ICASSP 2026 | |
| [Dance Like a Chicken: Low-Rank Stylization for Human Motion Diffusion](https://onlinelibrary.wiley.com/doi/10.1111/cgf.70365) | CGF (Eurographics 2026) | [code](https://github.com/haimsaw/LoRA-MDM) [webpage](https://haimsaw.github.io/LoRA-MDM/) |
| [Generalizing Stylized Motion Generation Method by Introducing Metadata-Independent Learning and Unified Multiple Motion Dataset](https://ieeexplore.ieee.org/abstract/document/11303907/) | IEEE TMM 2025 | [code](https://github.com/erayuki-lmd/Generalized_Stylized_Motion_Generation_Method) |
| [DiFusion: Flexible Stylized Motion Generation Using Digest-and-Fusion Scheme](https://ieeexplore.ieee.org/abstract/document/11202393/) | IEEE TVCG 2025 | |
| [StyleMotif: Multi-Modal Motion Stylization using Style-Content Cross Fusion](https://openaccess.thecvf.com/content/ICCV2025/papers/Guo_StyleMotif_Multi-Modal_Motion_Stylization_using_Style-Content_Cross_Fusion_ICCV_2025_paper.pdf) | ICCV 2025 | [webpage](https://stylemotif.github.io/) |
| [SMooDi: Stylized Motion Diffusion Model](https://arxiv.org/pdf/2407.12783) | ECCV 2024 | [webpage](https://neu-vi.github.io/SMooDi/) |
| [StyleVR: Stylizing Character Animations With Normalizing Flows](https://ieeexplore.ieee.org/abstract/document/10076832/) | IEEE TVCG 2023 | |
| [Unifying Human Motion Synthesis and Style Transfer with Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2212.08526) | arxiv 22.12 | [code](https://github.com/mrzzy2021/StyledMotionSynthesis) |

