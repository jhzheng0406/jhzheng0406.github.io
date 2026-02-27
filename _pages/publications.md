---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

- [Do We Need All the Synthetic Data? Targeted Image Augmentation via Diffusion Models](https://iclr.cc/virtual/2026/poster/10009127), Dang Nguyen†, Jiping Li†, **Jinghao Zheng†**, and Baharan Mirzasoleiman. **ICLR 2026** (Accepted as a poster)

- [Unified Gradient-Based Machine Unlearning with Remain Geometry Enhancement](https://proceedings.neurips.cc/paper_files/paper/2024/file/2e622ac74f66df03b686a12e2e0e4424-Paper-Conference.pdf), Z. Huang, X. Cheng, **J. Zheng**, H. Wang, Z. He, T. Li, and X. Huang. **NeurIPS 2024** (Accepted as a spotlight)

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{[https://scholar.google.com/citations?user=toxSa0cAAAAJ&hl=zh-CN]}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
