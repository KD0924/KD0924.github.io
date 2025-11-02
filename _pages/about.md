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

Hi! I'm **Kexuan Du**, currently based in Manchester, UK.  
I hold an MSc in **Health Data Science** from *The University of Manchester*.

My research interests focus on **causal inference**, **large language models (LLMs)**, and **machine learning**.  





# 📖 Educations
- *2024.09 - 2025.12*, Master of Science in Health Data Science, University of Manchester. 
- *2020.09 - 2024.07*, Bachelor of Science in Statistics, Southwestern University of Finance and Economics. 

<hr>

<h2 id="projects">Projects</h2>
{% include projects.html show_title=false %}

