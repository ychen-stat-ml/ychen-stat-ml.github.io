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

Hey, I am Yifan Chen, an Assistant Professor in Computer Science and Mathematics (affiliate) at Hong Kong Baptist University. 

I obtained my Ph.D. degree from Department of Statistics, University of Illinois Urbana-Champaign in 2023, advised by Prof. <a href="https://sites.google.com/site/yunyangstat/">Yun Yang</a>. 
I fortunately work with Prof. <a href="https://sites.google.com/site/yunyangstat/">Yun Yang</a>, 
Prof. <a href="https://stat.illinois.edu/directory/profile/rqzhu/">Ruoqing Zhu</a>, 
Prof. <a href="https://cs.illinois.edu/about/people/faculty/hengji/">Heng Ji</a>,
and Prof. <a href="https://ischool.illinois.edu/people/jingrui-he/">Jingrui He</a> during my Ph.D. studies.
I also collaborated with Prof. <a href="https://www.linkedin.com/in/dilek-hakkani-tur-9517543/">Dilek Hakkani-Tur</a> at Amazon Alexa AI, and Dr. <a href="https://research.ibm.com/people/jie-chen">Jie Chen</a> at IBM Research.
Before that, I received my B.S. degree in Statistics from Fudan University in 2018, advised by Prof. <a href="https://www.fdsm.fudan.edu.cn/en/teacher/preview.aspx?UID=141685">Juan Shen</a> and Prof. <a href="https://www.fdsm.fudan.edu.cn/en/teacher/preview.aspx?UID=1859">Chenghong Zhang</a>.

# 💻 Research

I am broadly interested in the general area of **efficient machine learning**, aiming to understand the statistical structures of modern machine learning algorithms and apply these insights to real-world computational challenges.
I especially focus on <strong>non-parametric models</strong> and neural networks with intensive matrix operations, such as <strong>Transformers</strong> (language models) and graph neural networks (<strong>GNNs</strong>).


# 🕮 Teaching

## Spring 24: COMP 7070 Advanced Topics in Artificial Intelligence and Machine Learning

Overall, this course is an invitation to core machine learning for **AI application research**. It aims to familiarize the students with useful concepts in machine learning, and therefore to benefit their own research.

> Studies related to machine learning is implicitly divided into three genres in this statement: learning theory, core machine learning, and AI application.

Scribed lecture notes can be found on [this page](/teaching.html).


# 🔥 News
- *2023.09*: &nbsp;🎉🎉 One paper was accepted to NeurIPS 2023! Congratulations to Xiaoyuan and other collaborators from Prof. Qingfu Zhang's group at CityU!
- *2023.07*: I am looking for self-motivated **(visiting) Ph.D. students / (remote) research assistants** to work with me on machine learning. Fellowships / salaries are provided to qualified candidates. Any interested applicants can directly send me your **CV** and a brief introduction to your **research interest** to "ychen.stat.ML@outlook.com". Please refer to the [Zhihu post](https://zhuanlan.zhihu.com/p/651070296) for more details.
- *2023.04*: &nbsp;🎉🎉 I will join CS @ Hong Kong Baptist University as an assistant professor in Fall 2023. 
- *2023.04*: &nbsp;🎉🎉 Two papers were accepted to ICML 2023!

# 📝 Publications

\* Co-first author, ✉️ Corresponding author

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2023</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Gromov--Wasserstein Geometric View of Spectrum-Preserving Graph Coarsening](https://arxiv.org/abs/2306.08854)

**Yifan Chen**, Rentian Yao, Yun Yang, Jie Chen

</div>
</div> -->

- ``NeurIPS 2023`` [Hypervolume Maximization: A Geometric View of Pareto Set Learning](https://nips.cc/virtual/2023/poster/72581)  
Xiaoyuan Zhang, Bo Xue, Xi Lin, **Yifan Chen**✉️, Qingfu Zhang✉️
- ``ICML 2023`` [A Gromov--Wasserstein Geometric View of Spectrum-Preserving Graph Coarsening](https://proceedings.mlr.press/v202/chen23ak.html)  
**Yifan Chen**, Rentian Yao, Yun Yang, Jie Chen
- ``ICML 2023`` [NTK-approximating MLP Fusion for Efficient Language Model Fine-tuning](https://proceedings.mlr.press/v202/wei23b.html)  
Tianxin Wei\*, Zeming Guo\*, **Yifan Chen**\*✉️, Jingrui He✉️
- ``TMLR`` [Calibrate and Debias Layer-wise Sampling for Graph Convolutional Networks](https://openreview.net/forum?id=JyKNuoZGux)  
**Yifan Chen**\*, Tianning Xu\*, Dilek Hakkani-Tur, Di Jin, Yun Yang, Ruoqing Zhu. Transactions on Machine Learning Research (TMLR), 2023.
- ``EMNLP 2022`` <span style="color:red">(Oral)</span> [Inducer-tuning: Connecting Prefix-tuning and Adapter-tuning](https://aclanthology.org/2022.emnlp-main.50/)  
**Yifan Chen**\*, Devamanyu Hazarika\*, Mahdi Namazifar, Yang Liu, Di Jin, Dilek Hakkani-Tur
- ``NAACL 2022`` <span style="color:red">(Oral)</span> [Sketching as a Tool for Understanding and Accelerating Self-attention for Long Sequences](https://aclanthology.org/2022.naacl-main.381/)  
**Yifan Chen**\*, Qi Zeng\*, Dilek Hakkani-Tur, Di Jin, Heng Ji, Yun Yang
- ``NAACL 2022`` (Findings) [Empowering parameter-efficient transfer learning by recognizing the kernel structure in self-attention](https://aclanthology.org/2022.findings-naacl.102/)  
**Yifan Chen**\*, Devamanyu Hazarika\*, Mahdi Namazifar, Yang Liu, Di Jin, Dilek Hakkani-Tur
- ``NeurIPS 2021`` [Skyformer: Remodel Self-Attention with Gaussian Kernel and Nystr\"om Method](https://proceedings.neurips.cc/paper/2021/hash/10a7cdd970fe135cf4f7bb55c0e3b59f-Abstract.html)  
**Yifan Chen**\*, Qi Zeng\*, Heng Ji, Yun Yang
- ``AISTATS 2021`` [Accumulations of Projections—A Unified Framework for Random Sketches in Kernel Ridge Regression](http://proceedings.mlr.press/v130/chen21f.html)  
**Yifan Chen**, Yun Yang
- ``AISTATS 2021`` [Fast Statistical Leverage Score Approximation in Kernel Ridge Regression](https://proceedings.mlr.press/v130/chen21e.html)  
**Yifan Chen**, Yun Yang

# 🎖 Honors and Awards
- *2023.05* Dissertation Completion Fellowships (gratefully declined due to early graduation), USD **$25,000**, University of Illinois Graduate College
- *2023.05* The Fortieth International Conference on Machine Learning (ICML 2023) Grant Award, USD **$1,500**
- *2018.06* Shanghai Outstanding Graduate, Shanghai Municipal Education Commission

# 💬 Professional Talks
- *2023.08*, A Gromov--Wasserstein Geometric View of Spectrum-Preserving Graph Coarsening, HKBU Math department invited talk, Hong Kong
- *2023.08*, NTK-approximating MLP Fusion for Efficient Language Model Fine-tuning, the 1st International Conference on AI-generated Content (AIGC2023) invited talk, Remote
- *2022.08*, One Expert with Multiple Instruments, Microsoft Azure internal talk, Remote
- *2022.08*, Sketching as a Tool for Understanding and Accelerating Self-attention for Long Sequences, AI Time PhD NAACL Special Session, Remote
- *2021.12*, Empowering parameter-efficient transfer learning by recognizing the kernel structure in self-attention, Amazon Alexa AI internal talk, Sunnyvale, CA, USA
