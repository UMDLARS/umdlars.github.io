---
layout: post
description: "Git tips, tricks, and introduction"
---

Table of Contents:

{% for item in site.git %}
  <h2>{{ item.title }}</h2>
  <p>{{ item.description }}</p>
  <p><a href="{{ item.url }}">{{ item.title }}</a></p>
{% endfor %}
