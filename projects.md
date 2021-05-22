---
layout: default
title: Projects
---

<ul>
{% for page in site.projects %}
  <li><a href="{{ page.url }}">{{ page.title }}</a></li>
{% endfor %}
</ul>