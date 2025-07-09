---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I hold a Postdoc position at Tsinghua University, working with Prof. Jie Tang and Minlie Huang. I obtained my Ph.D. from Sichuan University in June 2023 under the supervision of Prof. Jianzhou Zhang, Prof. Rong Jin (Alibaba DAMO). Dr. Mang Wang (ByteDance). I am participating as one of the contributors to project [VGen](https://github.com/ali-vilab/VGen/tree/main) (通义万相) and [SuperBench](https://fm.ai.tsinghua.edu.cn/superbench/) (清华大学-基础模型中心). I led project include ERD, C-Flat, ZeroFlow and INFTY Engine. All projects gained a total of **4,000+ stars**.

My research lies at the intersection of computer vision and machine learning. My research interests include **Computer Vision**, **Continual Learning**, **Video Generation** and **Vision-Language Model**. My vision is striving to build <i><u>Continual AI — intelligence that learns, adapts, and grows over time.</u></i>

# 🔥 News
- *2025.06*: &nbsp;🎉  VLM-CL, 	
SAMora accepted by ICCV 2025.
- *2025.05*: &nbsp;🎉 [ZeroFlow](https://zeroflow-bench.github.io/) , [Dual-Arch](https://arxiv.org/pdf/2506.03951?), [gR_MoE-LoRA](https://arxiv.org/pdf/2502.15828) accepted by ICML 2025. 
- *2025.03*: &nbsp;🎉 [TDFusion](https://openaccess.thecvf.com/content/CVPR2025/papers/Bai_Task-driven_Image_Fusion_with_Learnable_Fusion_Loss_CVPR_2025_paper.pdf) accepted by CVPR 2025 as **Highlight**.
- *2025.02*: &nbsp;📖 We release a survey [Parameter-Efficient Fine-Tuning for Foundation Models](https://github.com/THUDM/Awesome-Parameter-Efficient-Fine-Tuning-for-Foundation-Models?tab=readme-ov-file).
- *2025.02*: &nbsp;📖 We release a survey [Generative Artificial Intelligence in Robotic Manipulation](https://github.com/GAI4Manipulation/AwesomeGAIManipulation).
- *2025.02*: &nbsp;🎉 [HAR Foundation Model](https://www.sciencedirect.com/science/article/abs/pii/S1566253525002325) accepted by Information Fusion (IF=14.80).
- *2024.09*: &nbsp;🎉 [C-Flat](https://proceedings.neurips.cc/paper_files/paper/2024/file/0e705ac30e573d1526f81a0fd071a151-Paper-Conference.pdf) accepted by NeurIPS 2024.
- *2024.06*: &nbsp;🎉 [UniGrad-FS](https://www.researchgate.net/profile/Ziwei_Liu45/publication/383133040_UniGrad-FS_Unified_Gradient_Projection_With_Flatter_Sharpness_for_Continual_Learning/links/66eb873819c9496b1faca211/UniGrad-FS-Unified-Gradient-Projection-With-Flatter-Sharpness-for-Continual-Learning.pdf) accepted by IEEE TII (IF=11.70).
- *2024.04*: &nbsp;🎉 [R<sup>2</sup>KD](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10843153) accepted by IEEE TIM (IF=5.60).
- *2024.03*: &nbsp;🎉 [InstructVideo](https://openaccess.thecvf.com/content/CVPR2024/papers/Yuan_InstructVideo_Instructing_Video_Diffusion_Models_with_Human_Feedback_CVPR_2024_paper.pdf) accepted by CVPR 2024.
- *2024.01*: &nbsp;🎉 [ArchCraft](https://arxiv.org/pdf/2404.14829) accepted by IJCAI 2024.
- *2023.07*: &nbsp;🎉 [RLIP v2](https://openaccess.thecvf.com/content/ICCV2023/papers/Yuan_RLIPv2_Fast_Scaling_of_Relational_Language-Image_Pre-Training_ICCV_2023_paper.pdf) accepted by ICCV 2023.
- *2023.07*: &nbsp;🎉 [RLIP](https://proceedings.neurips.cc/paper_files/paper/2022/file/f37347375d8b54e3203e5d24aeb6c58c-Paper-Conference.pdf) accepted by NeurIPS 2022 as **Spotlight**.
- *2022.03*: &nbsp;🎉 [ERD](https://openaccess.thecvf.com/content/CVPR2022/papers/Feng_Overcoming_Catastrophic_Forgetting_in_Incremental_Object_Detection_via_Elastic_Response_CVPR_2022_paper.pdf) accepted by CVPR 2022.
- *2021.12*: &nbsp;🎉 [Pose-powered ReID](https://www.sciencedirect.com/science/article/abs/pii/S0031320321006798) accepted by Pattern Recognition (IF=7.50).
- *2021.10*: &nbsp;🏆 Win 1st Place on Webface260M SFR Track! @ICCV MFR Challenge.
- *2021.10*: &nbsp;🥈 Win 2nd Place on InsightFace unconstrained Track! @ICCV MFR Challenge.
- *2021.10*: &nbsp;🥉 Win 3rd Place on Webface260M Main Track! @ICCV MFR Challenge.
- *2021.10*: &nbsp;🥉 Win 3rd Place on InsightFace ms1m Track! @ICCV MFR Challenge.
- *2021.09*: &nbsp;🎉 One paper accepted by ICCV 2021 @workshop.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/zeroflow.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ZeroFlow: Overcoming Catastrophic Forgetting is Easier than You Think](https://arxiv.org/pdf/2501.01045)

**Tao Feng**, Wei Li, DiDi Zhu, Hangjie Yuan, Wendi Zheng, Dan Zhang, Jie Tang

[**Project**](https://zeroflow-bench.github.io/) 
- We introduce ZeroFlow, the first benchmark designed to evaluate gradient-free optimization algorithms for overcoming forgetting.
- We find that forward passes alone are enough to overcome forgetting. Maybe, once is all it takes!
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/moelora.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Stronger Mixture of Low-Rank Experts for Fine-Tuning Foundation Models](https://arxiv.org/pdf/2502.15828)

Mengyang Sun, Yihao Wang, **Tao Feng<sup>†</sup>**, Dan Zhang, Yifan Zhu, Jie Tang<sup>†</sup>

[**Project**](https://zeroflow-bench.github.io/) 
- We propose a new training strategy for MoE-LoRA, to stabilize and boost its feature learning procedure by multi-space projections.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/dual.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Rethinking the Stability-Plasticity Trade-off in Continual Learning from an Architectural Perspective](https://arxiv.org/pdf/2506.03951?)

Aojun Lu, Hangjie Yuan, **Tao Feng<sup>†</sup>**, Yanan Sun

[**Project**](https://github.com/byyx666/Dual-Arch) 
- We propose a novel insight for exploring the stability-plasticity tradeoff from an architectural perspective.
- We introduce a novel framework denoted DualArch, which serves as a plug-in component for continual learning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025-Highlight</div><img src='images/tdfusion.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Task-driven Image Fusion with Learnable Fusion Loss](https://openaccess.thecvf.com/content/CVPR2025/papers/Bai_Task-driven_Image_Fusion_with_Learnable_Fusion_Loss_CVPR_2025_paper.pdf)

Haowen Bai, Jiangshe Zhang, Zixiang Zhao, Yichen Wu, Lilun Deng, Yukun Cui, **Tao Feng**, Shuang Xu

[**Project**](https://github.com/HaowenBai/TDFusion) 
- Our framework includes a dynamically updated, learnable fusion loss generation module.
- TDFusion can be applied to any architecture of fusion and task networks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/c-flat.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Make Continual Learning Stronger via C-Flat](https://proceedings.neurips.cc/paper_files/paper/2024/file/0e705ac30e573d1526f81a0fd071a151-Paper-Conference.pdf)

Ang Bian, Wei Li, Hangjie Yuan, Chengrong Yu, Mang Wang, Zixiang Zhao, Aojun Lu, Ji Pengliang, **Tao Feng<sup>†</sup>**

[**Project**](https://github.com/WanNaa/C-Flat) 
- We propose a Continual Flatness (C-Flat) method featuring a flatter loss landscape tailored for continual learning.
- Just a line of code, Makes Continual Learning Stronger. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/instructvideo.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[InstructVideo: Instructing Video Diffusion Models with Human Feedback](https://openaccess.thecvf.com/content/CVPR2024/papers/Yuan_InstructVideo_Instructing_Video_Diffusion_Models_with_Human_Feedback_CVPR_2024_paper.pdf)

Hangjie Yuan, Shiwei Zhang, Xiang Wang, Yujie Wei, **Tao Feng**, Yining Pan, Yingya Zhang, Ziwei Liu, Samuel Albanie, Dong Ni

[**Project**](https://instructvideo.github.io/.) 
- We propose InstructVideo, a model that efficiently instructs textto-video diffusion models to follow human feedback.
- To mitigate the absence of a dedicated video reward model for human preferences, we repurpose established image reward models.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2024</div><img src='images/archcraft.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Revisiting Neural Networks for Continual Learning: An Architectural Perspective](https://arxiv.org/pdf/2404.14829)

Aojun Lu, **Tao Feng**, Hangjie Yuan, Xiaotian Song, Yanan Sun

[**Project**](https://github.com/byyx666/ArchCraft) 
- This work is the pioneering effort to employ neural architecture design to shape a CL-friendly architecture.
- We propose ArchCraft method to recraft AlexNet/ResNet into AlexAC/ResAC to guide a well-designed network architecture for CL.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/rlipv2.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RLIP v2: Fast Scaling of Relational Language-image Pre-training](https://openaccess.thecvf.com/content/ICCV2023/papers/Yuan_RLIPv2_Fast_Scaling_of_Relational_Language-Image_Pre-Training_ICCV_2023_paper.pdf)

Hangjie Yuan, Shiwei Zhang, Xiang Wang, Samuel Albanie, Yining Pan, **Tao Feng**, Jianwen Jiang, Dong Ni, Yingya Zhang, Deli Zhao

[**Project**](https://github.com/JacobYuan7/RLIPv2) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose RLIP v2, a fast converging model that enables the scaling of relational pre-training to largescale pseudo-labelled scene graph data.
- RLIPv2 introduces Asymmetric Language-Image Fusion (ALIF), a mechanism that facilitates earlier and deeper gated cross-modal fusion with sparsified language encoding layers.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2022-Spotlight</div><img src='images/rlip.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RLIP: Relational Language-Image Pre-training for Human-Object Interaction Detection](https://proceedings.neurips.cc/paper_files/paper/2022/file/f37347375d8b54e3203e5d24aeb6c58c-Paper-Conference.pdf)

Hangjie Yuan, Jianwen Jiang, Samuel Albanie, **Tao Feng**, Ziyuan Huang, Dong Ni, Mingqian Tang

[**Project**](https://github.com/JacobYuan7/RLIP) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose Relational Language Image Pre-training (RLIP), a strategy for contrastive pre-training that leverages both entity and relation descriptions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/erd.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Overcoming Catastrophic Forgetting in Incremental Object Detection via Elastic Response Distillation](https://openaccess.thecvf.com/content/CVPR2022/papers/Feng_Overcoming_Catastrophic_Forgetting_in_Incremental_Object_Detection_via_Elastic_Response_CVPR_2022_paper.pdf)

**Tao Feng**, Mang Wang, Hangjie Yuan

[**Project**](https://github.com/hi-fengtao/ERD) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- First open-source incremental detection codebase.
- We propose a response-based knowledge distillation method for Incremental Object Detection, dubbed Elastic Response Distillation (ERD).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCVW 2021</div><img src='images/mask.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Mask-robust Face Recognition](https://openaccess.thecvf.com/content/ICCV2021W/MFR/papers/Feng_Towards_Mask-Robust_Face_Recognition_ICCVW_2021_paper.pdf)

**Tao Feng**, Liangpeng Xu, Hangjie Yuan, Yongfei Zhao, Mingqian Tang, Mang Wang

[**Project**](https://openaccess.thecvf.com/content/ICCV2021W/MFR/papers/Feng_Towards_Mask-Robust_Face_Recognition_ICCVW_2021_paper.pdf) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We introduce a mask-to-face image blending approach based on UV texture mapping, and a self-learning based cleaning pipeline for processing noisy training datasets.
- Considering the long-tail distribution and hard faces samples, a loss function named Balanced Curricular Loss is introduced.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Information Fusion 2025</div><img src='images/HAR.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Visible Light Human Activity Recognition Driven by Generative Language Model](https://www.sciencedirect.com/science/article/abs/pii/S1566253525002325)

Yanbing Yang, Ziwei Liu, Yongkun Chen, Binyu Yan, Yimao Sun, **Tao Feng<sup>†</sup>**

[**Project**](https://www.sciencedirect.com/science/article/abs/pii/S1566253525002325) 
- We propose the first HAR foundation model that leverages generative large language models (LLMs) to decode visible light feature representations into human activity descriptions.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TII 2024</div><img src='images/unigrad.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Unigrad-FS: Unified Gradient Projection with Flatter Sharpness for Continual Learning](https://www.researchgate.net/profile/Ziwei_Liu45/publication/383133040_UniGrad-FS_Unified_Gradient_Projection_With_Flatter_Sharpness_for_Continual_Learning/links/66eb873819c9496b1faca211/UniGrad-FS-Unified-Gradient-Projection-With-Flatter-Sharpness-for-Continual-Learning.pdf)

Wei Li, **Tao Feng<sup>†</sup>**, Hangjie Yuan, Ang Bian, Guodong Du, Sixin Liang, Jianhong Gan, Ziwei Liu

[**Project**](https://www.researchgate.net/profile/Ziwei_Liu45/publication/383133040_UniGrad-FS_Unified_Gradient_Projection_With_Flatter_Sharpness_for_Continual_Learning/links/66eb873819c9496b1faca211/UniGrad-FS-Unified-Gradient-Projection-With-Flatter-Sharpness-for-Continual-Learning.pdf) 
- We propose a plug-and-play method UniGrad to tackle the inconsistency of conflicting and non-conflicting gradients in gradient updating for CL.
- We find the flat minima region through perturbing the model parameters in CL.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TIM 2024</div><img src='images/r2d.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Class-Incremental Player Detection with Refined Response-based Knowledge Distillation](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10843153)

Liang Bai, Hangjie Yuan, Hong Song<sup>†</sup>, **Tao Feng<sup>†</sup>**, Jian Yang<sup>†</sup>

[**Project**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10843153) 
- We propose a refined response-based KD (R<sup>2</sup>KD) strategy specifically designed for efficient knowledge transfer in incremental detection.
- We are the first to comprehensively study class-incremental detection in real-world sports broadcast scenarios.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Pattern Recognition 2022</div><img src='images/reid.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Identifying Players in Broadcast Videos using Graph Convolutional Network](https://www.sciencedirect.com/science/article/abs/pii/S0031320321006798)

**Tao Feng**, Kaifan Ji, Ang Bian, Chang Liu, Jianzhou Zhang

[**Project**](https://www.sciencedirect.com/science/article/abs/pii/S0031320321006798) 
- A novel person representation method using graph convolu- tional network at the level of relational induction bias is presented.
- We innovatively embed implicit pose structure information into the deep features to form high-level features.
</div>
</div>


# 📖 Academic Service
- Reviewing
  + *Conferences:* ICLR 2024-2025, ICML 2024-2025, NeurIPS 2023-2025, CVPR 2022-2024, ICCV 2023-2025, ECCV 2024, AAAI 2023-2025, IJCAI 2023-2025 ACL 2025 and KDD 2024-2025
  + *Journals:* TPAMI, IJCV, TIP, TMM, TCSVT, TNNLS, TII, TIM and PR etc.
- Services
  + Guest Editor for the Special Issue of Journal of Imaging
