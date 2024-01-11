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



Education
======
* B.S. in Physics, Guangxi University, 2018
* M.S. in physics, Guangxi University, 2021
* Ph.D. in Astrophysics, University of Science and Technology of China, 2025 (expected)
