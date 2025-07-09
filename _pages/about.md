---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a Ph.D. student since 2023, advised by [Prof.Peidong Liu](https://scholar.google.com/citations?user=XZczNEEAAAAJ), at the School of Engineering, [Westlake University](https://en.westlake.edu.cn//) in collaboration with [Zhejiang University](https://www.zju.edu.cn/english/), Hangzhou, China. My previous research focused on **geometry and optimization problems in 3D Computer Vision**. Recently, I have been attempting to build an intelligent agent, **TIC**, in a probability space. This framework involves three core sub-tasks: **transport** (learning the dynamics of probability), **inference** (inferring probability from observations), and **control** (steering probability towards a target). Although these three tasks may seem independent, I hope to model and solve them under a unified language. This will give rise to a completely new interdisciplinary field that combines **Generation** (Diffusion Models, Flow Matching), **Control** (Stochastic Optimal Control, Reinforcement Learning), **Sampling**, **Transport** (Schrödinger Bridge, Trajectory Inference, Optimal Transport), **Game** (Mean Field Game), and **Optimization**. Open to collaboration! 😊

Previously, I obtained my Bachelor's degree in the College of Electrical and Information Engineering from [Hunan University](http://www-en.hnu.edu.cn/), Changsha, China.  

I also served as a reviewer for the **CVPR**, **ICCV**, **NeurIPS**, **AAAI**, **ACM MM**, **3DV**, **ICRA**, **IROS** and **RAL**.

## News
<style style="text/css"> .news{font-size:0.75em;} </style>
{% include news.html %}

## Notes
<style style="text/css"> .news{font-size:0.75em;} </style>
{% include notes.html %}

## Publications
Selected publications I am a primary author on are highlighted.

<style style="text/css"> .hoverTable{ width:85%; border-collapse:collapse; border: 0px; } .hoverTable td{ padding:7px; border:#4e95f4 0px solid; } /* Define the default color for all the table rows */ .hoverTable tr{} /* Define the hover highlight color for the table row */ .hoverTable tr:hover { background-color: #f7f7f7; } </style> {% for post in site.publications reversed %} {% include publications.html %} {% endfor %}



