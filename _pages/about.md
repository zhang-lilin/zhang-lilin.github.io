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
# About Me

I am a doctoral student in Sichuan University (*2024.06 - now*). 
- Supervisor: [**Ning Yang**](https://yneversky.github.io)
- Research Interest: **Trustworthy Machine Learning**
  - robustness
  - fairness
  - privacy
  - explainability
  - ...

<span class='anchor' id='-news'></span>
# News
- *2024.08*: paper accepted by RecSys 2024 (Jingyu Chen, **Lilin Zhang**, Ning Yang*. *Improving Adversarial Robustness for Recommendation Model via Cross-Domain Distributional Adversarial Training*). 

<span class='anchor' id='-publications'></span>
# Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2024</div><img src='images/paper_PUAT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

*Provable Unrestricted Adversarial Training without Compromise with Generalizability* (early access)

**Lilin Zhang**, Ning Yang*, Yanchao Sun, Philip S. Yu.

[[arxiv](https://arxiv.org/abs/2301.09069), [html](https://ieeexplore.ieee.org/abstract/document/10530438), [code](https://github.com/zhang-lilin/PUAT.git)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGIR 2024</div><img src='images/paper_AFRL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

*Adaptive Fair Representation Learning for Personalized Fairness in Recommendations via Information Alignment*

Xinyu Zhu, **Lilin Zhang**, Ning Yang*.

[[arxiv](https://arxiv.org/abs/2404.07494), [html](https://dl.acm.org/doi/abs/10.1145/3626772.3657709), [code](https://github.com/zhuxinyu2700/AFRL)]<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<div class='paper-box'>
<div class='paper-box-image'><div><div class="badge">WWW 2023</div><img src='images/paper_CCFCRec.png' alt="sym" width="100%">
</div>
</div>
<div class='paper-box-text' markdown="1">

*Contrastive Collaborative Filtering for Cold-Start Item Recommendation*

Zhihui Zhou, **Lilin Zhang**, Ning Yang*.

[[arxiv](https://arxiv.org/abs/2302.02151), [html](https://dl.acm.org/doi/abs/10.1145/3543507.3583286), [code](https://github.com/zzhin/CCFCRec)]<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
</div>
</div>

<span class='anchor' id='-educations'></span>
# Educations

[//]: # (- *2024 - now*, Doctor of Engineering, Sichuan University. )
- *2021.09 - 2024.06*, Master of Engineering, Sichuan University. 
- *2017.09 - 2021.06*, Bachelor of Management, Zhongnan University of Economics and Law.
