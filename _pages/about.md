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

I am an Assistant Professor at Ulsan National Institute of Science and Technology (UNIST), jointly appointed in the Department of Industrial Engineering and the Graduate School of Artificial Intelligence. My research focuses on machine learning for structured decision-making and discovery. I develop generative models, reinforcement learning methods, and search algorithms for navigating large, structured, and discrete spaces. My work spans combinatorial optimization and AI for Science, including molecular and biological design, with a recurring emphasis on sample-efficient learning when evaluations are expensive or data are limited. Here is my <a href="https://hyeonahkimm.github.io/assets/cv.pdf" class="link-in-list" style="color: #7289da; text-decoration: none;">CV</a>.

# 🔥 News
- *Sep 2026*: &nbsp; Joined UNIST as an Assistant Professor
- *May 2026*: &nbsp; One papers accepted to ICML 2026
- *May 2025*: &nbsp; **Sejong Science Fellowship** from the National Research Foundation of Korea
- *May 2025*: &nbsp; Two papers accepted to ICML 2025
- *Jan 2025*: &nbsp; One paper accepted to AISTATS 2025

# 📝 Publications 
([C]: Conference, [J]: Journal, [W]: Workshop, [P]: Preprint)
- **[C] Synthesizable Molecular Generation via Soft-constrained GFlowNets with Rich Chemical Priors** [[paper]](https://openreview.net/forum?id=NoESvlwHHq), [[code]](https://github.com/hyeonahkimm/s3gfn)\\
**Hyeonah Kim**, Minsu Kim, Celine Roget, Dionessa Biton, Louis Vaillancourt, Yves V. Brun, Yoshua Bengio, Alex Hernández-García \\
*ICML 2026*

- **[P] Test-Time Search in Neural Graph Coarsening Procedures for the Capacitated Vehicle Routing Problem** [[paper]](https://arxiv.org/abs/2510.00958)\\
Yoonju Sim, **Hyeonah Kim**, Changhyun Kwon \\
*Preprint*

- **[C] RL4CO: a Unified Reinforcement Learning for Combinatorial Optimization Library** [[paper]](https://arxiv.org/abs/2306.17100), [[code]](https://github.com/ai4co/rl4co)\\
Federico Berto\*, Chuanbo Hua\*, Junyoung Park\*, Laurin Luttmann\*, Yining Ma, Fanchen Bu, Jiarui Wang, Haoran Ye, Minsu Kim, Sanghyeok Choi, Nayeli Gast Zepeda, André Hottung, Jianan Zhou, Jieyi Bi, Yu Hu, Fei Liu, **Hyeonah Kim**, Jiwoo Son, Haeyeon Kim, Davide Angioni, Wouter Kool, Zhiguang Cao, Qingfu Zhang, Joungho Kim, Jie Zhang, Kijung Shin, Cathy Wu, Sungsoo Ahn, Guojie Song, Changhyun Kwon, Kevin Tierney, Lin Xie, Jinkyoo Park \\
*Knowledge Discovery and Data Mining (KDD) 2025 (Datasets and Benchmarks Track - Oral)*

- **[C] Neural Genetic Search in Discrete Spaces** [[paper]](https://arxiv.org/abs/2502.10433), [[code]](https://github.com/hyeonahkimm/ngs)\\
**Hyeonah Kim**\*, Sanghyeok Choi\*, Jiwoo Son, Jinkyoo Park, Changhyun Kwon \\
*ICML 2025*

- **[C] Improved Off-policy Reinforcement Learning in Biological Sequence Design** [[paper]](https://arxiv.org/abs/2410.04461), [[code]](https://github.com/hyeonahkimm/delta_cs) \\
**Hyeonah Kim**, Minsu Kim, Taeyoung Yun, Sanghyeok Choi, Emmanuel Bengio, Alex Hernández-García, Jinkyoo Park \\
*ICML 2025*

- **[C] Ant Colony Sampling with GFlowNets for Combinatorial Optimization** [[paper]](https://arxiv.org/abs/2403.07041), [[code]](https://github.com/ai4co/gfacs)\\
Minsu Kim\*, Sanghyeok Choi\*, **Hyeonah Kim**, Jiwoo Son, Jinkyoo Park, Yoshua Bengio \\
*AISTATS 2025*

- **[C] Genetic-guided GFlowNets for Sample Efficient Molecular Optimization** [[paper]](https://arxiv.org/abs/2402.05961), [[code]](https://github.com/hyeonahkimm/genetic_gfn)\\
**Hyeonah Kim**, Minsu Kim, Sanghyeok Choi, Jinkyoo Park \\
*NeurIPS 2024*

- **[C] Symmetric Replay Training: Enhancing Sample Efficiency in Deep Reinforcement Learning for Combinatorial Optimization** [[paper]](https://arxiv.org/abs/2306.01276), [[code]](https://github.com/kaist-silab/symmetric_replay)\\
**Hyeonah Kim**, Minsu Kim, Sungsoo Ahn, Jinkyoo Park \\
*ICML 2024*

- **[C] Equity-Transformer: Solving NP-hard Min-max Routing Problems as Sequential Generation with Equity Context** [[paper]](https://arxiv.org/abs/2306.02689), [[code]](https://github.com/kaist-silab/equity-transformer)\\
Jiwoo Son\*, Minsu Kim\*, Sanghyeok Choi, **Hyeonah Kim**, Jinkyoo Park \\
*AAAI 2024*

- **[J, W] A Neural Separation Algorithm for the Rounded Capacity Inequalities** [[paper]](https://doi.org/10.1287/ijoc.2022.0310), [[code]](https://github.com/hyeonahkimm/neuralsep)\\
**Hyeonah Kim**, Jinkyoo Park, Changhyun Kwon \\
*INFORMS Journal on Computing (IJOC), 2024* \\
*NeurIPS 2022 GLFrontiers Workshop*

- **[C] Meta-SAGE: Scale Meta-Learning Scheduled Adaptation with Guided Exploration for Mitigating Scale Shift on Combinatorial Optimization** [[paper]](https://proceedings.mlr.press/v202/son23a.html), [[code]](https://github.com/kaist-silab/meta-sage)\\
Jiwoo Son\*, Minsu Kim\*, **Hyeonah Kim**, Jinkyoo Park \\
*ICML 2023*


# 🎖 Honors and Awards
- *Sep 2025 - Aug 2026:* Sejong Science Fellowship, National Research Foundation of Korea
- *Dec 2024:* Google Conference Scholarship for NeurIPS 2024 (1st author of Genetic-guided GFlowNets for Sample Efficient Molecular Optimization)
- *Nov 2024:* KAIST Graduate Student Outstanding Paper Award 2024 (1st author of A Neural Separation Algorithm for the Rounded Capacity Inequalities)
<!-- - *Feb 2015* Summa Cum Laude  -->

# 📖 Education
- *Mar 2021 - Feb 2025*, Ph.D. in Industrial and Systems Engineering, KAIST (SILAB & COMET Lab)
- *Mar 2019 - Feb 2021*, M.S. in Industrial Engineering, Seoul National University (Optimization and Operational Research Lab)
- *Mar 2011 - Feb 2015*, B.S. in Industrial Engineering, Hanyang University (Information Design Lab)

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Work Experience
- *Sep 2026 - Present*, Assistant Professor, Department of Industrial Engineering and Graduate School of Artificial Intelligence, UNIST
- *Apr 2025 - Aug 2026*, Postdoctoral Researcher, Mila and Université de Montréal
- *Jan 2015 - Jun 2017*, Software Engineer, LG CNS (LGE ERP Manufacturing)
