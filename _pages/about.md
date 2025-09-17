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

**Shihao Wang**  
Ph.D. Student, Department of Computing, Hong Kong Polytechnic University (PolyU)  
PQ515, PolyU | Tel: +86 18210705396 | [Homepage](https://exiawsh.github.io/shihaow-homepage.github.io/)  
Email: 24053277r@connect.polyu.hk

My research interests include 3D perception and planning for autonomous vehicles and robotics, multimodal foundation models, streaming video understanding, and test-time adaptation for agentic systems.  
I have published at CVPR, ICCV, AAAI and other top conferences, with <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>500+</span></strong></a>.  
[Google Scholar](https://scholar.google.com/citations?user=DhtAFkwAAAAJ) <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

# 🔥 News
- *2024.07*: &nbsp;🎉 [VideoITG](https://arxiv.org/abs/2507.13353) accepted to arXiv, achieving SOTA on long-video understanding benchmarks.
- *2024.06*: &nbsp;🏆 1st Place in End-to-End Driving at Scale, 2nd Place in Driving with Language, CVPR 2024 Autonomous Driving Grand Challenge.
- *2024.05*: &nbsp;🎉 [OmniDrive](https://arxiv.org/abs/2405.01533) accepted to CVPR 2025.
- *2023.10*: &nbsp;🎉 Joined NVIDIA Applied Research Group as Research Intern.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/omnidrivethumb.png' alt="OmniDrive" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[OmniDrive: A holistic vision-language dataset for autonomous driving with counterfactual reasoning](https://arxiv.org/abs/2405.01533)

**Shihao Wang**, Zhiding Yu, Xiaohui Jiang, Shiyi Lan, Min Shi, Nadine Chang, Jan Kautz, Ying Li, Jose M. Alvarez

CVPR 2025

</div>
</div>

- [VideoITG: Multimodal Video Understanding with Instructed Temporal Grounding](https://arxiv.org/abs/2507.13353), **Shihao Wang** et al., arXiv 2025
- [StreamPETR: End-to-End Multi-View 3D Object Detection with Transformers](https://arxiv.org/abs/2303.11926), **Shihao Wang** et al., ICCV 2023
- [Far3D: Expanding the horizon for surround-view 3d object detection](https://arxiv.org/abs/2308.09616), **Shihao Wang** et al., AAAI 2024
- [HydraMDP: End-to-end multimodal planning with multi-target hydra-distillation](https://arxiv.org/abs/2406.06978), **Shihao Wang** et al., arXiv 2024
- [Eagle: Exploring the design space for multimodal llms with mixture of encoders](https://arxiv.org/abs/2408.15998), **Shihao Wang** et al., arXiv 2024

# 🎖 Honors and Awards
- *2024.06* Winner, CVPR24 Challenge on End-to-End Driving at Scale
- *2024.06* 2nd Place, CVPR24 Challenge on Driving with Language
- *2023.11* 1st Place, nuScenes leaderboard on camera-only 3D object tracking

# 📖 Educations
- *2024.09 - Present*, Ph.D. in Computer Vision, Department of Computing, Hong Kong Polytechnic University (PolyU), Hong Kong
- *2021.09 - 2024.06*, M.Sc. in Vehicle Engineering, Beijing Institute of Technology (BIT), Beijing, GPA: 89.5/100
- *2017.09 - 2021.06*, B.Sc. in Vehicle Engineering, Beijing Institute of Technology (BIT), Beijing, GPA: 87.5/100

# 💬 Invited Talks
- *2024.06*, "Vision-Language Foundation Models for Autonomous Driving", CVPR 2024 Autonomous Driving Grand Challenge Workshop
- *2023.12*, "Streaming Perception for Autonomous Vehicles", NVIDIA Research Group

# 💻 Internships
- *2023.10 - 2025.01*, [NVIDIA](https://www.nvidia.com/en-us/research/), Shenzhen, China.  
  - Research Intern, AV Applied Research Group. Contributed to Eagle VLM family, VideoITG, HydraMDP, OmniDrive, GR00T N1.5.
- *2022.04 - 2023.07*, [MEGVII Technology](https://megvii.com/), Beijing, China.  
  - Research Intern, Foundation Model Group (PI: [Xiangyu Zhang](https://scholar.google.com/citations?user=yuB-cfoAAAAJ&hl=en)). Developed StreamPETR, Far3D, etc.

