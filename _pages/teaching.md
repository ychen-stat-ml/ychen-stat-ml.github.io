---
permalink: /teaching
title: Teaching
excerpt: ""
author_profile: false
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

# COMP 7070 Advanced Topics in Artificial Intelligence and Machine Learning

Overall, this course is an invitation to core machine learning for **AI application research**. It aims to familiarize the students with useful concepts in machine learning, and therefore to benefit their own research.

> Studies related to machine learning is implicitly divided into three genres in this statement: learning theory, core machine learning, and AI application.

## Detailed course topics

- "Linearity is all you need"
    - Matrix derivative
    - Basic concepts of numerical analysis
    - Logistic regression
    - Basic concepts of convex optimization (convergence rate of GD and SGD) 


- Harness the power of randomness
    - SubGaussian random variables and concentration inequalities
    - Sketching methods
    - Error decomposition (approximation, optimization, and generalization) and concentration bound for generalization error

- Advanced topics
    - Kernel tricks, RKHS, and neural tangent kernels
    - Generative modeling (MLE - EM algorithm - VI - VAE - GAN/WGAN - Flow - Diffusion)

Note that the detailed lecture schedule may change as the semester progresses, based on student interest.

## Scribed lecture notes

- Lecture 1: Preliminaries [🗈](/docs/7070/01.pdf)
- Lecture 2: Numerical Analysis [🗈](/docs/7070/02.pdf) (matrix derivation and basics of numerical analysis, such as condition number, operator norm, SVD, etc.)
- Lecture 3: Regularization and Logistic Regression [🗈](/docs/7070/03.pdf) (a thorough revisit of the softmax classifier)
- Lecture 4: Convex Optimization and the Convergence Rate of GD/SGD [🗈](/docs/7070/04.pdf)
- Lecture 5: Concentration Inequalities and SubGaussian Random Variables [🗈](/docs/7070/05.pdf)
- Lecture 6: JL Lemma and Sketching Methods [🗈](/docs/7070/06.pdf)
- Lecture 7: Generalization Error [🗈](/docs/7070/07.pdf)
- Lecture 8: Kernel tricks and RKHS [🗈](/docs/7070/08.pdf)
