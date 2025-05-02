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


I'm a postdoctoral researcher at Mila and Université de Montréal, working with <a href="https://alexhernandezgarcia.github.io/" style="color: #7289da; text-decoration: none;">Alex Hernandez-Garcia</a>. My research focuses on scientific discovery with deep learning, with a particular interest in GFlowNets, active learning, and sample-efficient training. I'm currently exploring improved exploration strategies for GFlowNets and their applications to synthesizable molecule generation. I’m also deeply engaged in combinatorial optimization, motivated by the belief that many real-world problems require navigating large, structured, and discrete spaces. Here is my <a href="https://hyeonahkimm.github.io/assets/cv.pdf" class="link-in-list" style="color: #7289da; text-decoration: none;"> cv</a>.


# 🔥 News
- *May 2025*: &nbsp;🎉🎉 Two papers accepted to ICML 2025
- *Jan 2025*: &nbsp;🎉🎉 One paper accepted to AISTATS 2025
- *Dec 2024*: &nbsp;🎉🎉 **Google Conference Scholarship** for NeurIPS 2024
- *Dec 2024*: &nbsp;🎉🎉 "Genetic-guided GFlowNets for Sample Efficient Molecular Optimization" is selected for a contributed talk at the WiML workshop (NeurIPS 2024)
- *Oct 2024*: &nbsp;🎉🎉 One paper accepted to NeurIPS 2024
- *Sep 2024*: &nbsp;🎉🎉 "A Neural Separation Algorithm for the Rounded Capacity Inequalities" is selected as a featured article (INFORMS Journal on Computing)

# 📝 Publications 
([C]: Conference, [J]: Journal, [W]: Workshop, [P]: Preprint)

- **[P] Neural Genetic Search in Discrete Spaces** [[paper]](https://arxiv.org/abs/2502.10433), [[code]](https://github.com/hyeonahkimm/ngs)\\
**Hyeonah Kim**\*, Sanghyeok Choi\*, Jiwoo Son, Jinkyoo Park, Changhyun Kwon\\

- **[C] Ant Colony Sampling with GFlowNets for Combinatorial Optimization** [[paper]](https://arxiv.org/abs/2403.07041), [[code]](https://github.com/ai4co/gfacs)\\
Minsu Kim\*, Sanghyeok Choi\*, **Hyeonah Kim**, Jiwoo Son, Jinkyoo Park, Yoshua Bengio\\
*AISTATS 2025*

- **[W] Improved Off-policy Reinforcement Learning in Biological Sequence Design** [[paper]](https://arxiv.org/abs/2410.04461), [[code]](https://github.com/hyeonahkimm/delta_cs) \\
**Hyeonah Kim**, Minsu Kim, Taeyoung Yun, Sanghyeok Choi, Emmanuel Bengio, Alex Hernández-García, Jinkyoo Park
*AIDrugX@NeurIPS*

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

- **[W] RL4CO: a Unified Reinforcement Learning for Combinatorial Optimization Library** [[paper]](https://arxiv.org/abs/2306.17100), [[code]](https://github.com/ai4co/rl4co)\\
Federico Berto\*, Chuanbo Hua\*, Junyoung Park\*, Minsu Kim, **Hyeonah Kim**, Jiwoo Son, Haeyeon Kim, Joungho Kim, Jinkyoo Park  \\
*NeurIPS 2023 Workshop: New Frontiers in Graph Learning (Oral)*

- **[C] Meta-SAGE: Scale Meta-Learning Scheduled Adaptation with Guided Exploration for Mitigating Scale Shift on Combinatorial Optimization** [[paper]](https://proceedings.mlr.press/v202/son23a.html), [[code]](https://github.com/kaist-silab/meta-sage)\\
Jiwoo Son\*, Minsu Kim\*, **Hyeonah Kim**, Jinkyoo Park \\
*ICML 2023*

# 🎖 Honors and Awards
- *Dec 2024:* Google Conference Scholarship for NeurIPS 2024 (1st author of Genetic-guided GFlowNets for Sample Efficient Molecular Optimization)
- *Nov 2024:* KAIST Graduate Student Outstanding Paper Award 2024 (1st author of A Neural Separation Algorithm for the Rounded Capacity Inequalities)
<!-- - *Feb 2015* Summa Cum Laude  -->

# 📖 Educations
- *Mar 2021 - Feb 2025*, Ph.D. Candidate in Industrial and Systems Engineering, KAIST (SILAB & COMET Lab)
- *Mar 2019 - Feb 2021*, M.S in Industrial Engineering, Seoul National University (Optimization and Operational Research Lab)
- *Mar 2011 - Feb 2015*, B.S Industrial Engineering, Hanyang University (Information Design Lab)

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Work Experience
- *Jan 2015 - Jun 2017*, Software Engineer at LGE ERP Manufacturing, LGCNS 
