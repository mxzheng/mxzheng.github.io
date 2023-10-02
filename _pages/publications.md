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

