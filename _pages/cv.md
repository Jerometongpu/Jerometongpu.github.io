---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Current Appointment
======
* **Lecturer**, School of Undergraduate Education, Shenzhen Polytechnic University
  * Shenzhen, Guangdong, People's Republic of China
  * Email: [putong@szpu.edu.cn](mailto:putong@szpu.edu.cn)

Education
======
* **Ph.D. in Mathematics**, Southern University of Science and Technology, 09/2022 – 07/2026
  * GPA: 3.71/4, Rank: 3/21
  * Supervised by Prof. Yiying Zhang
  * Outstanding Graduate of School of Science, SUSTech

* **Visiting Ph.D. student**, University of Amsterdam, 10/2024 – 09/2025
  * Department of Quantitative Economics
  * Funded by China Scholarship Council (CSC)
  * Supervised by Prof. Roger J.A. Laeven

* **M.S. in Statistics**, Qufu Normal University, 09/2019 – 07/2022
  * GPA: 3.53/4, Rank: 1/15
  * Supervised by Prof. Chuancun Yin
  * Received Outstanding Dissertation Award of Shandong Province

* **B.S. in Mathematics and Applied Mathematics**, Qufu Normal University, 09/2014 – 07/2018

Selected Awards
======
* National Scholarship of China (SUSTech) | 2025
* BYD Scholarship | 2025
* Third Prize and Outstanding Student Speaker, National Outstanding Graduate Students Workshop | 2024
* Outstanding Dissertation Award of Shandong Province | 2023
* Outstanding Teaching Assistant of SUSTech | 2023 & 2024
* National Scholarship of China (Qufu Normal University) | 2021
* Third Prize, 2020 National Graduate Statistical Modeling Competition of China | 2020
* Honorable Mention, 2017 Mathematical Contest In Modeling | 2017
* Third Prize, The Seventh Mathematics Competition of Chinese College Students | 2015

Publications
======
{% assign publications = site.publications | where: "publication_status", "published" | sort: "publication_year" | reverse %}
<ul>{% for post in publications %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Teaching
======
<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Skills and Expertise
======
* **Programming Languages:** Python, R, MATLAB (ranked by proficiency)
* **Research Interests:** Systemic risks, stochastic orders and preferences, dependence structures, ambiguity and related models

Language Proficiency
======
* **TOEFL:** Reading 27/30, Listening 28/30, Speaking 22/30, Writing 22/30. Total 99/120.
