---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
<!-- 
---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

## Selected Methodological & Statistical Research

- **Neural Network Machine Regression (NNMR): A Deep Learning Framework for Uncovering High-order Synergistic Effects**  
  Jiuchen Zhang, Ling Zhou, Peter Song. *arXiv preprint*, 2026.  
  <u><a href="https://arxiv.org/abs/2602.02172">arXiv:2602.02172</a></u>

- **Cumulative Treatment Effect Testing under Continuous-Time Reinforcement Learning**  
  Jiuchen Zhang, Annie Qu. *arXiv preprint*, 2026.  
  <u><a href="https://arxiv.org/abs/2602.02246">arXiv:2602.02246</a></u>

- **Individualized Dynamic Latent Factor Model for Multi-resolutional Data with Application to Mobile Health**  
  Jiuchen Zhang, Fei Xue, Qi Xu, Jung-Ah Lee, Annie Qu. *Biometrika*, 2024.

- **Tensor Factorization Recommender System with Dependency**  
  Jiuchen Zhang, Yubai Yuan, Annie Qu. *Electronic Journal of Statistics*, 2022.

## Selected Collaborative & Applied Research

- **Wearable Internet-of-Things Technology to Measure Sleep of Diverse Caregivers: Preliminary Results from a Randomized Controlled Trial**  
  Jung-Ah Lee, Jiuchen Zhang, Amir Rahmani, Annie Qu. *Alzheimer's & Dementia*, 2024.

- **Improvements in Heart Rate Variability among Dementia Family Caregivers Receiving a Home-Visit Based Intervention: Preliminary Results from a Randomized Controlled Trial**  
  Jung-Ah Lee, Jiuchen Zhang, Eilleen Sabino-Laughlin, Eunae Ju, Amir Rahmani, Annie Qu. *Alzheimer's & Dementia*, 2023.

- **Culturally and Linguistically Appropriate Home Visit Intervention for Underserved Dementia Family Caregivers: Preliminary Results from a Randomized Controlled Trial**  
  Jung-Ah Lee, Eunae Ju, Jiuchen Zhang, Eilleen Sabino-Laughlin, Amir Rahmani, Lisa Gibbs, Sanghyuk Shin, Annie Qu, Priscilla Kehoe, Adey Nyamathi. *Alzheimer's & Dementia*, 2022.

- **Identifying Sleep Disturbance Subtypes Among Dementia Caregivers Using Unsupervised Learning**  
  Eunbee Angela Kim, Jiuchen Zhang, Amir M. Rahmani, Sanghyuk Shin, Adeline Nyamathi, Jung-Ah Lee. *Manuscript in preparation.*

---

## Full Publication List

{% include base_path %}  
{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}  -->
