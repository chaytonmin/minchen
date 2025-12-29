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

I am currently an Assistant Researcher at Institute of Computing Technology (ICT), Chinese Academy of Sciences, and I am a Postdoctoral Fellow with Prof. [Yu Hu](https://meridiancas.github.io/). 

Before this, I obtained a Ph.D. from the School of Computer Science at Peking University in 2024, under the supervision of Prof. Bin Dai. I obtained my Master's degree from the School of Computer Science at Beijing Jiaotong University in 2020, under the supervision of Prof. [Liping Jing](https://faculty.bjtu.edu.cn/8249/). I obtained my Bachelor's degree in Energy and Power Engineering from Xi'an Jiaotong University in 2016. 

My research interest includes Autonomous Driving and Embodied Intelligence. 

# 🔥 News
- *2025.12*: &nbsp;🎉🎉 One paper is accepted by JFR (Survey for Off-Road Autonomous Driving).
- *2025.08*: &nbsp;🎉🎉 Selected for the Member of the Professional Committee on Visual Perception Intelligent Systems, China Society of Image and Graphics.
- *2025.06*: &nbsp;🎉🎉 One paper is accepted by IROS 2025 (4D Radar Perception).
- *2025.06*: &nbsp;🎉🎉 One paper is accepted by ICCV 2025 (VLM for Autonomous Driving).
- *2025.06*: &nbsp;🎉🎉 One paper is accepted by TITS (Model Compression for LiDAR Perception).
- *2024.10*: &nbsp;🎉🎉 Selected for the CCF IV Youth Incentive Program.
- *2024.04*: &nbsp;🎉🎉 One paper is accepted by IV 2024 (Model Compression for LiDAR Perception).
- *2024.03*: &nbsp;🎉🎉 One paper is accepted by CVPR 2024 (World Model for Autonomous Driving). 
- *2024.02*: &nbsp;🎉🎉 One paper is accepted by RA-L & IROS 2024 (Pre-training for Autonomous Driving).
- *2023.10*: &nbsp;🎉🎉 One paper is accepted by TIV (Pre-training for Autonomous Driving).
- *2022.05*: &nbsp;🎉🎉 One paper is accepted ICRA 2022 (Dataset for Off-Road Autonomous Driving).
- *2022.04*: &nbsp;🎉🎉 One paper is accepted TVCG (MVS-based 3D Resconstruction).
- *2021.10*: &nbsp;🎉🎉 One paper is accepted ICCV 2021 (MVS-based 3D Resconstruction). 
- *2021.02*: &nbsp;🎉🎉 One paper is accepted RA-L (Parking for Autonomous Driving). 

# 📝 Publications 
**JFR 2025:** **Autonomous Driving in Unstructured Environments: How Far Have We Come?** [Arxiv](https://arxiv.org/abs/2410.07701) [Code](https://github.com/chaytonmin/Survey-Autonomous-Driving-in-Unstructured-Environments)

- **Chen Min**, Shubin Si, Xu Wang, Hanzhang Xue, Dawei Zhao, Liang Xiao, Yiming Nie, Yu Hu, Xuelong Li, etc.

- Comprehensive survey about Autonomous Driving in Unstructured Outdoor Environments.

**IROS 2025: 2 **CORENet: Cross-Modal 4D Radar Denoising Network with LiDAR Supervision for Autonomous Driving** [Arxiv](https://arxiv.org/abs/2508.13485).

- Fuyang Liu, Jilin Mei, Fangyuan Mao, **Chen Min**, Yan Xing, Yu Hu.

- 4D Radar Denoising Network for Autonomous Driving.
  
**ICCV 2025:** **VLR-Driver: Large Vision-Language-Reasoning Models for Embodied Autonomous Driving** [ICCV](https://openaccess.thecvf.com/content/ICCV2025/html/Kong_VLR-Driver_Large_Vision-Language-Reasoning_Models_for_Embodied_Autonomous_Driving_ICCV_2025_paper.html)

- Fanjie Kong, Yitong Li, Weihuang Chen, **Chen Min**, Yizhe Li, Zhiqiang Gao, Haoyang Li, Zhongyu Guo, Hongbin Sun

**TITS:** **Efficient Distillation Using Channel Pruning for Point Cloud-Based 3D Object Detection** [TITS](https://ieeexplore.ieee.org/abstract/document/11034662/)

- Fuyang Li, **Chen Min**, Juan Wang, Liang Xiao, Dawei Zhao, Yiming Nie, Bin Dai

**Arxiv 2024:** **WildOcc: A Benchmark for Off-Road 3D Semantic Occupancy Prediction** [Arxiv](https://arxiv.org/abs/2410.15792)

- Heng Zhai, Jilin Mei, **Chen Min**, Liang Chen, Fangzhou Zhao, Yu Hu

- Off-Road 3D Semantic Occupancy Prediction.

**Arxiv 2024:** **Is Sora a World Simulator? A Comprehensive Survey on General World Models and Beyond** [Arxiv](https://arxiv.org/abs/2405.03520) [Code](https://github.com/GigaAI-research/General-World-Models-Survey)

- Zheng Zhu, Xiaofeng Wang, Wangbo Zhao, **Chen Min**, Nianchen Deng, Min Dou, Yuqi Wang, Botian Shi, Kai Wang, Chi Zhang, Yang You, Zhaoxiang Zhang, Dawei Zhao, Liang Xiao, Jian Zhao, Jiwen Lu, Guan Huang

- Comprehensive survey about General World Models.
  
**IV 2024:** **Pre-pruned Distillation for Point Cloud-based 3D Object Detection** [Arxiv](https://ieeexplore.ieee.org/abstract/document/10588400/) [Code]()

- Fuyang Li, **Chen Min**, Liang Xiao, Dawei Zhao, Shubin Si, Hanzhang Xue, Yiming Nie, Bin Dai

- Model compression for 3D LiDAR perception.

**CVPR 2024:** **DriveWorld: 4D Pre-trained Scene Understanding via World Models for Autonomous Driving** [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Min_DriveWorld_4D_Pre-trained_Scene_Understanding_via_World_Models_for_Autonomous_CVPR_2024_paper.html)

- **Chen Min**, Dawei Zhao, Liang Xiao, Jian Zhao, Xinli Xu, Zheng Zhu, Lei Jin, Jianshu Li, Yulan Guo, Junliang Xing, Liping Jing, Yiming Nie, Bin Dai

- World Models; 4D pre-training; Autonomous Driving

**RA-L 2024:** **Multi-Camera Unified Pre-Training Via 3D Scene Reconstruction for Autonomous Driving** [Paper](https://ieeexplore.ieee.org/abstract/document/10423224) [Code](https://github.com/chaytonmin/UniScene)

- **Chen Min**, Liang Xiao, Dawei Zhao, Yiming Nie, Bin Dai

- Occupancy prediction; 3D pre-training. 

# 🎖 Honors and Awards
- *2024.10* CIVS 2024 Outstanding Candidate Paper Award.
- *2024.10* CCF IV Youth Incentive Program.
- *2021.10* Champion of Group D3 and Third Place in Group C1 in the Autonomous Vehicle Challenge. 

# 📖 Educations
- *2020.09 - 2024.07*, School of Computer Science, Peking University. 
- *2017.07 - 2020.07*, School of Computer Science, Beijing Jiaotong University. 
- *2012.09 - 2016.07*, School of Energy and Power Engineering, Xi'an Jiaotong University. 

# 💻 Internships
- *2022.07 - 2022.11*, Megvii, China.
- *2022.03 - 2022.07*, NIO, China.
- *2018.11 - 2019.05*, Momo, China.
