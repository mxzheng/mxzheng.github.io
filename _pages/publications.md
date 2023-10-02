---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% for publication in site.publications %}
  - **{{ publication.title }}**
    - *Authors*: {{ publication.authors }}
    - *Journal*: {{ publication.journal }}
    - *Link*: [Read Paper]({{ publication.link }})
{% endfor %}

- title: "CryptoLight: An Electro-Optical Accelerator for Fully Homomorphic Encryption"
  authors: "Mengxin Zheng, Qian Lou, Fan Chen, Lei Jiang, Yongxin Zhu"
  journal: "Proceedings of the 17th ACM International Symposium on Nanoscale Architectures (NanoArch 2022)"
  link: "https://dl.acm.org/doi/pdf/10.1145/3565478.3572544"
