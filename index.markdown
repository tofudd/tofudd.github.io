---
layout: default
title: tofu homepage
---

Welcome on my personal homepage. 
I've lost count and I don't know which iteration it is. 

## Personal

* [Github](https://github.com/tof4)
* [bartlomiej.tota@outlook.com](mailto:bartlomiej.tota@outlook.com)

## Projects
<ul>
{% for page in site.projects %}
  <li><a href="{{ page.url }}">{{ page.title }}</a></li>
{% endfor %}
</ul>

## Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
