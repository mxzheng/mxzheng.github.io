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

<table id="Highlights">
     <tr class="r1"><td class="c1">09 / 2023 </td><td class="c2">  
  TrojPrompt: A Black-box Trojan Attack on Pre-trained Language Models
   is accepted by NeurIPS 2023. </td></tr> 
