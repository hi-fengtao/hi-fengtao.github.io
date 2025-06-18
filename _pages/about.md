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

I hold a Postdoc position at Tsinghua University, working with Prof. Jie Tang and Minlie Huang. I obtained my Ph.D. from Sichuan University in June 2023 under the supervision of Prof. Jianzhou Zhang, Prof. Rong Jin (Alibaba DAMO). Dr. Mang Wang (ByteDance). I am participating as one of the contributors to project VGen (通义万相) and SuperBench (清华大学-基础模型中心). I led project include ERD, C-Flat, ZeroFlow and EasyCL Library (in progress). All projects gained a total of 4,000+ stars.

My research lies at the intersection of computer vision and machine learning – with a special focus on building intelligent visual systems that are continual and data-efficient. My research interests include Computer Vision, Continual Learning, Video Generation and Vision-Language Model.


# 🔥 News
- *2025.05*: &nbsp;🎉 ZeroFlow, Dual-Arch, gR_MoE-LoRA accepted by ICML 2025. 
- *2025.03*: &nbsp;🎉 TDFusion accepted by CVPR 2025 as Spotlight.
- *2025.02*: &nbsp;📖 We release a survey Parameter-Efficient Fine-Tuning for Foundation Models.
- *2025.02*: &nbsp;📖 We release a survey Generative Artificial Intelligence in Robotic Manipulation.
- *2025.02*: &nbsp;🎉 HAR Foundation Model accepted by Information Fusion (IF=14.80).
- *2024.09*: &nbsp;🎉 C-Flat accepted by NeurIPS 2024.
- *2024.06*: &nbsp;🎉 UniGrad-FS accepted by IEEE TII (IF=11.70).
- *2024.04*: &nbsp;🎉 R<sup>2</sup>KD accepted by IEEE TIM (IF=5.60).
- *2024.03*: &nbsp;🎉 InstructVideo accepted by CVPR 2024.
- *2024.01*: &nbsp;🎉 ArchCraft accepted by IJCAI 2024.
- *2023.07*: &nbsp;🎉 RLIP v2 accepted by ICCV 2023.
- *2023.07*: &nbsp;🎉 RLIP accepted by NeurIPS 2022 as Spotlight.
- *2022.03*: &nbsp;🎉 ERD accepted by CVPR 2022.
- *2021.12*: &nbsp;🎉 Pose-powered ReID accepted by Pattern Recognition (IF=7.50).
- *2021.10*: &nbsp;🏆 Win 1st Place on Webface260M SFR Track! @ICCV MFR Challenge.
- *2021.10*: &nbsp;🥈 Win 2nd Place on InsightFace unconstrained Track! @ICCV MFR Challenge.
- *2021.10*: &nbsp;🥉 Win 3rd Place on Webface260M Main Track! @ICCV MFR Challenge.
- *2021.10*: &nbsp;🥉 Win 3rd Place on InsightFace ms1m Track! @ICCV MFR Challenge.
- *2021.09*: &nbsp;🎉 One papers accepted by ICCV 2021 @workshop.

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

[Rethinking the Stability-Plasticity Trade-off in Continual Learning from an Architectural Perspective]([https://arxiv.org/pdf/2501.01045](https://arxiv.org/pdf/2506.03951?))

Aojun Lu, Hangjie Yuan, **Tao Feng<sup>†</sup>**, Yanan Sun

[**Project**](https://github.com/byyx666/Dual-Arch) 
- We propose a novel insight for exploring the stability-plasticity tradeoff from an architectural perspective.
- We introduce a novel framework denoted DualArch, which serves as a plug-in component for continual learning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025-Spotlight</div><img src='images/tdfusion.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Task-driven Image Fusion with Learnable Fusion Loss](https://openaccess.thecvf.com/content/CVPR2025/papers/Bai_Task-driven_Image_Fusion_with_Learnable_Fusion_Loss_CVPR_2025_paper.pdf)

Haowen Bai, Jiangshe Zhang, Zixiang Zhao, Yichen Wu, Lilun Deng, Yukun Cui, **Tao Feng**, Shuang Xu

[**Project**](https://github. com/HaowenBai/TDFusion) 
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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/instructvideo.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[InstructVideo: Instructing Video Diffusion Models with Human Feedback](https://openaccess.thecvf.com/content/CVPR2024/papers/Yuan_InstructVideo_Instructing_Video_Diffusion_Models_with_Human_Feedback_CVPR_2024_paper.pdf)

Hangjie Yuan, Shiwei Zhang, Xiang Wang, Yujie Wei, **Tao Feng**, Yining Pan, Yingya Zhang, Ziwei Liu, Samuel Albanie, Dong Ni

[**Project**](https://instructvideo.github.io/.) 
- We propose InstructVideo, a model that efficiently instructs textto-video diffusion models to follow human feedback.
- To mitigate the absence of a dedicated video reward model for human preferences, we repurpose established image reward models.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/archcraft.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Revisiting Neural Networks for Continual Learning: An Architectural Perspective](https://arxiv.org/pdf/2404.14829)

Aojun Lu, **Tao Feng**, Hangjie Yuan, Xiaotian Song, Yanan Sun

[**Project**](https://github.com/byyx666/ArchCraft) 
- This work is the pioneering effort to employ neural architecture design to shape a CL-friendly architecture.
- We propose ArchCraft method to recraft AlexNet/ResNet into AlexAC/ResAC to guide a well-designed network architecture for CL.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/erd.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Overcoming Catastrophic Forgetting in Incremental Object Detection via Elastic Response Distillation](https://openaccess.thecvf.com/content/CVPR2022/papers/Feng_Overcoming_Catastrophic_Forgetting_in_Incremental_Object_Detection_via_Elastic_Response_CVPR_2022_paper.pdf)

**Tao Feng**, Mang Wang, Hangjie Yuan

[**Project**](https://github.com/hi-fengtao/ERD) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose a response-based knowledge distillation method for Incremental Object Detection, dubbed Elastic Response Distillation (ERD).
- First open-source incremental detection codebase.
</div>
</div>


# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
