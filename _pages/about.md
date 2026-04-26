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

I am currently a Research Scientist at Nanyang Technological University (NTU) and ANGEL CorpLab, Singapore, where I work with Prof. <a href='https://scholar.google.com/citations?user=sGCf2k0AAAAJ&hl=en'>Jianmin Zheng</a>. Prior to this, I was a Research Fellow at the National University of Singapore (NUS). I obtained my PhD degree from PCA Lab, Nanjing University of Science and Technology (NJUST), under the supervision of Prof. <a href='https://scholar.google.com/citations?user=6CIDtZQAAAAJ&hl=id'>Jian Yang</a> and Prof. <a href='https://scholar.google.com/citations?user=Q7QqJPEAAAAJ&hl=id'>Jin Xie</a>. In 2023, I was a visiting student at CVLab, EPFL, Switzerland, supervised by Dr. <a href='https://scholar.google.com/citations?user=n-B0jr4AAAAJ&hl=id'>Mathieu Salzmann</a>. In 2018, I spent several months as a Research Intern at the Inception Institute of Artificial Intelligence (IIAI), Abu Dhabi. 

My research interests lie in 3D computer vision and reinforcement learning (RL), with a particular focus on:
- 3D scene reconstruction and understanding for spatial intelligence
- Robotic navigation and manipulation for embodied AI
- On-policy/off-policy/offline RL theory and (world-)model based RL/planning

My long-term goal is to develop spatially intelligent agents that can understand, reason about, and act in the physical world!



# 🔥 News
- *2026.02*: &nbsp;🎉 Four papers were accepted by ***CVPR 2026*** (⭐ 1 Oral, 1 Highlight).
- *2025.08*: &nbsp;🎉 One paper was accepted by ***IEEE Robotics and Automation Letters***.
- *2025.07*: &nbsp;🎉 Three papers were accepted by ***AAAI 2026***.
- *2025.06*: &nbsp;🎉 One paper was accepted by ***ICCV 2025***.
- *2025.06*: &nbsp;🎉 One paper was accepted by ***PRCV 2025***.
- *2025.05*: &nbsp;🎉 One paper was accepted by ***ICML 2025***.
- *2025.02*: &nbsp;🎉 One papers were accepted by ***CVPR 2025***.
- *2024.12*: &nbsp;🎉 One paper was accepted by ***AAAI 2025***.
- *2024.10*: &nbsp;🎉 One paper was accepted by ***IROS 2025***.
- *2024.07*: &nbsp;🎉 One paper was accepted by ***ECCV 2024***.
- *2024.05*: &nbsp;🎉 One paper was accepted by ***IEEE Transactions on Circuits and Systems for Video Technology***.
- *2024.04*: &nbsp;🎉 One paper was accepted by ***ICASSP 2024***.
- *2023.10*: &nbsp;🎉 One paper was accepted by ***IROS 2023***.
- *2023.09*: &nbsp;🎉 One paper was accepted by ***NeurIPS 2023***.
- *2023.08*: &nbsp;🎉 One paper was accepted by ***ACM MM 2023***.
- *2023.07*: &nbsp;🎉 One paper was accepted by ***ICCV 2023***.
- *2023.07*: &nbsp;🎉 Two paper were accepted by ***AAAI 2023***.
- *2023.03*: &nbsp;🎉 One paper was accepted by ***CVPR 2023***.
- *2022.09*: &nbsp;🎉 One paper was accepted by ***IEEE Transactions on Neural Networks and Learning Systems***.
- *2022.08*: &nbsp;🎉 One paper was accepted by ***ACCV 2022***.
- *2022.07*: &nbsp;🎉 One paper was accepted by ***ECCV 2022***.
- *2022.03*: &nbsp;🎉 One paper was accepted by ***IEEE Transactions on Neural Networks and Learning Systems***.
- *2022.01*: &nbsp;🎉 One paper was accepted by ***ACPR 2021*** (🏆 Best Paper Award).
- *2021.06*: &nbsp;🎉 One paper was accepted by ***ICCV 2021***.
- *2022.07*: &nbsp;🎉 One paper was accepted by ***AAAI 2022***.
- *2021.07*: &nbsp;🎉 One paper was accepted by ***AAAI 2021***.
- *2021.08*: &nbsp;🎉 One paper was accepted by ***IJCAI 2021***.
- *2018.11*: &nbsp;🎉 One paper was accepted by ***PRCV 2018***.

# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/FUSER-CVPR2026.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FUSER: Feed-Forward Multiview 3D Registration Transformer and SE(3)<sup>N</sup> Diffusion Refinement](https://arxiv.org/pdf/2512.09373) ([**Code**](https://github.com/Jiang-HB/FUSER/tree/main), ⭐ **Oral**)

**Haobo Jiang**, Jin Xie, Jian Yang, Liang Yu, and Jianmin Zheng

- The first *point-cloud-oriented 3D foundation reconstruction model* for feed-forward multiview point-cloud registration.
- An SE(3)<sup>N</sup> diffusion refinement model for multiview pose refinement.
- A new “pairwise-free” paradigm that cuts runtime from minutes to seconds while maintaining SOTA performance.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/GMR2-CVPR2026.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GM-R<sup>2</sup>: Generative Matching Learning for Unsupervised Geometric Representation and Registration](https://jiang-hb.github.io/) ([**Code**](https://jiang-hb.github.io/), ⭐ **Highlight**)

**Haobo Jiang**, Liang Yu, and Jianmin Zheng

- The first generative matching learning paradigm for unsupervised point-cloud registration.
- A denoising-agnostic coupled ControlNet for cross-view geometric representation learning.
- A label-free paradigm achieving SOTA performance without transformation supervision.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/VGGT360-CVPR2026.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[VGGT-360: Geometry-Consistent Zero-Shot Panoramic Depth Estimation](https://arxiv.org/abs/2603.18943) ([**Code**](https://github.com/Yuanjiayii/VGGT-360))

Jiayi Yuan, **Haobo Jiang**, De Wen Soh, and Na Zhao

- A training-free framework for geometry-consistent panoramic depth estimation via multi-view 3D reconstruction.
- Uncertainty-guided projection and structure-aware attention for reliable cross-view reasoning.
- A view-correlated paradigm that overcomes per-view inconsistency for globally coherent depth.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/ZeroMatch-CVPR2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Zero-shot RGB-D Point Cloud Registration with Pre-trained Large Vision Model](https://openaccess.thecvf.com/content/CVPR2025/papers/Jiang_Zero-shot_RGB-D_Point_Cloud_Registration_with_Pre-trained_Large_Vision_Model_CVPR_2025_paper.pdf) ([**Code**](https://github.com/Jiang-HB/ZeroMatch))

**Haobo Jiang**, Jin Xie, Jian Yang, Liang Yu, and Jianmin Zheng

- The first zero-shot RGB-D point-cloud registration framework for robust matching without task-specific supervision.
- A training-free local-global descriptor that combines local FPFH geometry with global Stable-Diffusion contextual priors.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/GPCR-ICML2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Generative Point Cloud Registration](https://proceedings.mlr.press/v267/jiang25k.html) ([**Code**](https://github.com/Jiang-HB/GenerativePCR))

**Haobo Jiang**, Jin Xie, Jian Yang, Liang Yu, and Jianmin Zheng

- The first geometry-to-image synthesis-driven 3D matching paradigm that augments geometry-only descriptors with generated RGB cues.
- Match-ControlNet for reliable, cross-view consistent image generation from point clouds.
- A plug-and-play framework that converts generated color cues into stronger 3D correspondences.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/DiffReg-NeurIPS2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SE(3) Diffusion Model-based Point Cloud Registration for Robust 6D Object Pose Estimation](https://proceedings.neurips.cc/paper_files/paper/2023/file/43069caa6776eac8bca4bfd74d4a476d-Paper-Conference.pdf) ([**Code**](https://github.com/Jiang-HB/DiffusionReg))

**Haobo Jiang**, Mathieu Salzmann, Zheng Dang, Jin Xie, and Jian Yang

- The first SE(3) diffusion registration framework for robust 6D object pose estimation.
- A manifold-aware denoising diffusion process that progressively refines noisy poses on SE(3).
- A plug-and-play diffusion paradigm that boosts existing registration networks via surrogate modeling.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/CenterReg-ICCV2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Center-Based Decoupled Point Cloud Registration for 6D Object Pose Estimation](https://openaccess.thecvf.com/content/ICCV2023/papers/Jiang_Center-Based_Decoupled_Point-cloud_Registration_for_6D_Object_Pose_Estimation_ICCV_2023_paper.pdf) ([**Code**](https://github.com/Jiang-HB/CenterReg))

**Haobo Jiang**, Zheng Dang, Shuo Gu, Jin Xie, Mathieu Salzmann, and Jian Yang

- A center-based decoupled registration framework for robust 6D object pose estimation.
- A correspondence-free center predictor that decouples translation from rotation.
- A center-aware rotation module with part-aware features and normal correction for reliable matching.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/VBReg-CVPR2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Robust Outlier Rejection for 3D Registration with Variational Bayes](https://openaccess.thecvf.com/content/CVPR2023/papers/Jiang_Robust_Outlier_Rejection_for_3D_Registration_With_Variational_Bayes_CVPR_2023_paper.pdf) ([**Code**](https://github.com/Jiang-HB/VBReg))

**Haobo Jiang**, Zheng Dang, Zhen Wei, Jin Xie, Jian Yang, and Mathieu Salzmann

- A variational non-local network for outlier rejection via Bayesian long-range correspondence modeling.
- A customized probabilistic graphical model with a variational lower bound for optimization.
- A Wilson score-based voting scheme for high-quality inlier search, with theoretical advantages over RANSAC.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TNNLS 2022</div><img src='images/RDT-TNNLS2022.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Point Cloud Registration-Driven Robust Feature Matching for 3D Siamese Object Tracking](https://arxiv.org/pdf/2209.06395) ([**Code**](https://jiang-hb.github.io/))

**Haobo Jiang**, Kaihao Lan, Le Hui, Guangyu Li, Jin Xie, and Jian Yang

- A 3D registration-driven Siamese framework for robust point-cloud tracking.
- A tracking-specific non-local registration module for template-search alignment.
- A registration-aided feature aggregation module for refined feature matching.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2021</div><img src='images/CEMNet-ICCV2021.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Sampling Network Guided Cross-Entropy Method for Unsupervised Point Cloud Registration](https://openaccess.thecvf.com/content/ICCV2021/papers/Jiang_Sampling_Network_Guided_Cross-Entropy_Method_for_Unsupervised_Point_Cloud_Registration_ICCV_2021_paper.pdf) ([**Code**](https://github.com/Jiang-HB/CEMNet))

**Haobo Jiang**, Yaqi Shen, Jin Xie, Jun Li, Jianjun Qian, and Jian Yang

- An end-to-end CEM-based deep model for unsupervised point cloud registration.
- A sampling network that predicts promising transformation regions for efficient search.
- An ICP-driven reward and sparsemax-based soft top-k selection for differentiable candidate optimization.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TNNLS 2022 & AAAI 2021</div><img src='images/FPPO-ACPR2022.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Action Candidate Driven Clipped Double Q-learning for Discrete and Continuous Action Tasks](https://arxiv.org/pdf/2203.11526) ([**Code**](https://github.com/Jiang-HB/AC_CDQ))

**Haobo Jiang**, Jin Xie, and Jian Yang

- An action-candidate clipped double estimator that balances overestimation and underestimation bias.
- Theoretical analysis on bias reduction, variance balance, and convergence.
- Integration into Double Q-learning and TD3 for robust discrete and continuous control.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2021</div><img src='images/PlanReg-IJCAI2021.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Planning with Learned Dynamic Model for Unsupervised Point Cloud Registration](https://arxiv.org/pdf/2108.02613) ([**Code**](https://jiang-hb.github.io/))

**Haobo Jiang**, Jin Xie, Jianjun Qian and Jian Yang

- The first to formulate point-cloud registration as a Markov decision process for RL-based alignment.
- A latent dynamics model of point clouds, i.e., *a 3D world model*, for CEM-based planning.
- Planning with the learned latent dynamics model for unsupervised point-cloud registration.

</div>
</div>

# 📝 Full Publications 
2026
- **Haobo Jiang**, Jin Xie, Jian Yang, Liang Yu and Jianmin Zheng, FUSER: Feed-Forward MUltiview 3D Registration Transformer and SE(3)<sup>N</sup>  Diffusion Refinement, **CVPR 2026 (Oral)** ([pdf](https://arxiv.org/pdf/2512.09373), [code](https://github.com/Jiang-HB/FUSER))
- **Haobo Jiang**, Liang Yu and Jianmin Zheng, GM-R<sup>2</sup>: Generative Matching Learning for Unsupervised Geometric Representation and Registration, **CVPR 2026 (Highlight)** ([pdf](https://jiang-hb.github.io/), [Code](https://jiang-hb.github.io/))
- Jiayi Yuan, **Haobo Jiang**, De Wen Soh and Na Zhao, VGGT-360: Geometry-Consistent Zero-Shot Panoramic Depth Estimation, **CVPR 2026** ([pdf](https://arxiv.org/pdf/2603.18943), [code](https://github.com/Yuanjiayii/VGGT-360))      
- Kangjian Zhu, **Haobo Jiang<sup>*</sup>**, Jianjun Qian and Jin Xie, A Cross-view Fusion Framework for Robust 6-DoF Grasp Pose Estimation, **CVPR 2026** ([pdf](https://jiang-hb.github.io/), [Code](https://jiang-hb.github.io/), **Corresponding Author*)
- Tianyu Zhang, **Haobo Jiang**, Jian Yang and Jin Xie, DiffPCI: Large Motion Point Cloud Frame Interpolation with Diffusion Model, **ICCV 2025** ([pdf](https://openaccess.thecvf.com/content/ICCV2025/papers/Zhang_DiffPCI_Large_Motion_Point_Cloud_frame_Interpolation_with_Diffusion_Model_ICCV_2025_paper.pdf), [Code](https://jiang-hb.github.io/))

2026

- **Haobo Jiang**, Jin Xie, Jian Yang, Liang Yu and Jianmin Zheng, FUSER: Feed-Forward MUltiview 3D Registration Transformer and SE(3)N Diffusion Refinement, **CVPR 2026 (Oral)** ([pdf](https://arxiv.org/pdf/2512.09373), [code](https://github.com/Jiang-HB/FUSER))
- **Haobo Jiang**, Liang Yu and Jianmin Zheng, GM-R2: Generative Matching Learning for Unsupervised Geometric Representation and Registration, **CVPR 2026 (Highlight)** ([pdf](https://jiang-hb.github.io/), [code](https://jiang-hb.github.io/))
- Kangjian Zhu, **Haobo Jiang<sup>*</sup>**, Jianjun Qian and Jin Xie, A Cross-view Fusion Framework for Robust 6-DoF Grasp Pose Estimation, **CVPR 2026** ([pdf](https://jiang-hb.github.io/), [code](https://jiang-hb.github.io/), **Corresponding Author***)
- Jiayi Yuan, **Haobo Jiang**, De Wen Soh and Na Zhao, VGGT-360: Geometry-Consistent Zero-Shot Panoramic Depth Estimation, **CVPR 2026** ([pdf](https://arxiv.org/pdf/2603.18943), [code](https://jiang-hb.github.io/))
- Yijie Ding, Yang Liu, **Haobo Jiang** and Jianmin Zheng, ReACT: Reward-informed Autoregressive Decision CAD Transformer, **AAAI 2026** ([pdf](https://ojs.aaai.org/index.php/AAAI/article/view/37360), [code](https://jiang-hb.github.io/))
- Jiawei Lian, Zhengxue Wang, Wentao Qu, **Haobo Jiang**, Le Hui and Jian Yang, Diffusion-Based Contextual Reconstruction for Point Cloud Segmentation with Limited Annotations, **AAAI 2026** ([pdf](https://ojs.aaai.org/index.php/AAAI/article/view/37610), [code](https://github.com/ljwwwiop/DiCoSeg))
- Yihao Chen, **Haobo Jiang<sup>*</sup>**, Liang Yu and Jianmin Zheng, SchellingFormer: Laplacian Matrix-guided Geometric Transformer for Robust Schelling Point Detection, **AAAI 2026** ([pdf](https://ojs.aaai.org/index.php/AAAI/article/view/39126), [code](https://jiang-hb.github.io/), **Equal Contribution***)

2025

- **Haobo Jiang**, Jin Xie, Jian Yang, Liang Yu and Jianmin Zheng, Zero-shot RGB-D Point Cloud Registration with Pre-trained Large Vision Model, **CVPR 2025** ([pdf](https://openaccess.thecvf.com/content/CVPR2025/papers/Jiang_Zero-shot_RGB-D_Point_Cloud_Registration_with_Pre-trained_Large_Vision_Model_CVPR_2025_paper.pdf), [code](https://github.com/Jiang-HB/ZeroMatch))
- **Haobo Jiang**, Jin Xie, Jian Yang, Liang Yu and Jianmin Zheng, Generative Point Cloud Registration, **ICML 2025** ([pdf](https://arxiv.org/pdf/2512.09407), [code](https://github.com/Jiang-HB/GenerativePCR))
- Tianyu Zhang, **Haobo Jiang**, Jian Yang and Jin Xie, DiffPCI: Large Motion Point Cloud Frame Interpolation with Diffusion Model, **ICCV 2025** ([pdf](https://openaccess.thecvf.com/content/ICCV2025/papers/Zhang_DiffPCI_Large_Motion_Point_Cloud_frame_Interpolation_with_Diffusion_Model_ICCV_2025_paper.pdf), [code](https://jiang-hb.github.io/))
- Wei Xie, **Haobo Jiang**, Yun Zhu, Jianjun Qian and Jin Xie, NaviFormer: A Spatio-Temporal Context-Aware Transformer for Object Navigation, **AAAI 2025** ([pdf](https://ojs.aaai.org/index.php/AAAI/article/view/33612), [code](https://github.com/Xie-Nav/NaviFormer))
- Kangjian Zhu, **Haobo Jiang**, Yigong Zhang, Jianjun Qian, Jian Yang and Jin Xie, MonoSE(3)-Diffusion: A Monocular SE(3) Diffusion Framework for Robust Camera-to-Robot Pose Estimation, **IEEE Robotics and Automation Letters 2025** ([pdf](https://arxiv.org/pdf/2510.10434), [code](https://jiang-hb.github.io/))
- Xingyu Zhou, **Haobo Jiang** and Jian Yang, Knowledge Distillation for 3D Registration by Locally and Globally Aligning Geometric Representations, **PRCV 2025** ([pdf](https://link.springer.com/chapter/10.1007/978-981-95-5693-9_37), [code](https://jiang-hb.github.io/))

2024

- Qianliang Wu, **Haobo Jiang**, Lei Luo, Jun Li, Yaqing Ding, Jin Xie and Jian Yang, Diff-Reg: Diffusion Model in Doubly Stochastic Matrix Space for Registration Problem, **ECCV 2024** ([pdf](https://arxiv.org/pdf/2403.19919), [code](https://github.com/wuqianliang/diff-reg))
- Qianliang Wu, Yaqing Ding, Lei Luo, **Haobo Jiang**, Shuo Gu, Chuanwei Zhou, Jin Xie and Jian Yang, SGNet: Salient Geometric Network for Point Cloud Registration, **IROS 2024** ([pdf](https://arxiv.org/pdf/2309.06207), [code](https://jiang-hb.github.io/))
- Can Xu, Le Hui, Yuehui Han, **Haobo Jiang**, Jiaxin Chen, Jin Xie and Jian Yang, Learning Local Semantic Region Activations for Weakly Supervised Object Localization, **IEEE Trans on Circuits and Systems for Video Technology 2024** ([pdf](https://ieeexplore.ieee.org/document/10536104), [code](https://jiang-hb.github.io/))
- Yuechen Xie, **Haobo Jiang** and Jin Xie, Mask6D: Masked Pose Priors for 6D Object Pose Estimation, **ICASSP 2024** ([pdf](https://arxiv.org/pdf/2507.06486), [code](https://jiang-hb.github.io/))

2023

- **Haobo Jiang**, Zheng Dang, Zhen Wei, Jin Xie, Jian Yang and Mathieu Salzmann, Robust Outlier Rejection for 3D Registration with Variational Bayes, **CVPR 2023** ([pdf](https://arxiv.org/pdf/2304.01514), [code](https://github.com/Jiang-HB/VBReg))
- **Haobo Jiang**, Mathieu Salzmann, Zheng Dang, Jin Xie and Jian Yang, SE(3) Diffusion Model-Based Point Cloud Registration for Robust 6D Object Pose Estimation, **NeurIPS 2023** ([pdf](https://arxiv.org/pdf/2310.17359), [code](https://github.com/Jiang-HB/DiffusionReg))
- **Haobo Jiang**, Mathieu Salzmann, Zheng Dang, Jin Xie and Jian Yang, Center-Based Decoupled Point Cloud Registration for 6D Object Pose Estimation, **ICCV 2023** ([pdf](https://openaccess.thecvf.com/content/ICCV2023/papers/Jiang_Center-Based_Decoupled_Point-cloud_Registration_for_6D_Object_Pose_Estimation_ICCV_2023_paper.pdf), [code](https://github.com/Jiang-HB/CenterReg))
- **Haobo Jiang**, Kaihao Lan, Le Hui, Guangyu Li, Jin Xie and Jian Yang, Point Cloud Registration-Driven Robust Feature Matching for 3D Siamese Object Tracking, **IEEE Trans. on Neural Network and Learning Systems 2023** ([pdf](https://arxiv.org/pdf/2209.06395), [code](https://jiang-hb.github.io/))
- Qianliang Wu, Yaqi Shen, **Haobo Jiang**, Guofeng Mei, Yaqing Ding, Lei Luo, Jin Xie and Jian Yang, Graph Matching Optimization Network for Point Cloud Registration, **IROS 2023** ([pdf](https://arxiv.org/pdf/2302.05844), [code](https://jiang-hb.github.io/))
- Wei Xie, **Haobo Jiang**, Shuo Gu and Jin Xie, Implicit Obstacle Map-Driven Indoor Navigation Model for Robust Obstacle Avoidance, **ACM MM 2023** ([pdf](https://arxiv.org/pdf/2308.12845), [code](https://jiang-hb.github.io/))
- Jiayi Yuan, **Haobo Jiang**, Xiang Li, Jianjun Qian, Jun Li and Jian Yang, Recurrent Structure Attention Guidance for Depth Super-Resolution, **AAAI 2023** ([pdf](https://arxiv.org/pdf/2301.13419), [code](https://jiang-hb.github.io/))
- Jiayi Yuan, **Haobo Jiang**, Xiang Li, Jianjun Qian, Jun Li and Jian Yang, Structure Flow-Guided Network for Real Depth Super-Resolution, **AAAI 2023** ([pdf](https://arxiv.org/pdf/2301.13416), [code](https://jiang-hb.github.io/))
- J. Li, Guangyu Li, **Haobo Jiang**, W. Guo and C. Gong, An Efficient Enhanced-YOLOv5 Algorithm for Multi-scale Ship Detection, **ICONIP 2023** ([pdf](https://jiang-hb.github.io/), [code](https://jiang-hb.github.io/))

2022

- **Haobo Jiang**, Guangyu Li, Jin Xie and Jian Yang, Action Candidate Driven Clipped Double Q-Learning for Discrete and Continuous Action Tasks, **IEEE TNNLS 2022** ([pdf](https://arxiv.org/pdf/2203.11526), [code](https://jiang-hb.github.io/))
- Yaqi Shen, Le Hui, **Haobo Jiang**, Jin Xie and Jian Yang, Reliable Inlier Evaluation for Unsupervised Point Cloud Registration, **AAAI 2022** ([pdf](https://arxiv.org/pdf/2202.11292), [code](https://jiang-hb.github.io/))
- Yuehui Han, Le Hui, **Haobo Jiang**, Jianjun Qian and Jin Xie, Generative Subgraph Contrast for Self-Supervised Graph Representation Learning, **ECCV 2022** ([pdf](https://arxiv.org/pdf/2207.11996), [code](https://jiang-hb.github.io/))
- Kaihao Lan, **Haobo Jiang** and Jin Xie, Temporal-Aware Siamese Tracker: Integrate Temporal Context for 3D Object Tracking, **ACCV 2022** ([pdf](https://jiang-hb.github.io/), [code](https://jiang-hb.github.io/))
- Weiqi Zhao, **Haobo Jiang** and Jin Xie, Fast Proximal Policy Optimization, **ACPR 2022** ([pdf](https://jiang-hb.github.io/), [code](https://jiang-hb.github.io/))
- Yubin Guo, **Haobo Jiang**, Xinlei Qi, Jin Xie, Cheng-Zhong Xu and Hui Kong, Unsupervised Visible-Light Images Guided Cross-Spectrum Depth Estimation from Dual-Modality Cameras, **arXiv 2022** ([pdf](https://arxiv.org/pdf/2205.00257), [code](https://jiang-hb.github.io/))

2021

- **Haobo Jiang**, Jin Xie and Jian Yang, Action Candidate Based Clipped Double Q-Learning for Discrete and Continuous Action Tasks, **AAAI 2021** ([pdf](https://arxiv.org/pdf/2105.00704), [code](https://jiang-hb.github.io/))
- **Haobo Jiang**, Yaqi Shen, Jin Xie, Jun Li, Jianjun Qian and Jian Yang, Sampling Network Guided Cross-Entropy Method for Unsupervised Point Cloud Registration, **ICCV 2021** ([pdf](https://arxiv.org/pdf/2109.06619), [code](https://jiang-hb.github.io/))
- **Haobo Jiang**, Jin Xie and Jian Yang, Planning with Learned Dynamic Model for Unsupervised Point Cloud Registration, **IJCAI 2021** ([pdf](https://arxiv.org/pdf/2108.02613), [code](https://jiang-hb.github.io/))

2018

- **Haobo Jiang**, Jianjun Qian, Jin Xie and Jian Yang, Episode-Experience Replay Based Tree-Backup Method for Off-Policy Actor-Critic Algorithm, **PRCV 2018** ([pdf](https://jiang-hb.github.io/), [code](https://jiang-hb.github.io/))

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
