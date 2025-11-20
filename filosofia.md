---
layout: page
title: Filosofía
permalink: /filosofia/
---

Reflexiones, ideas y cuestionamientos sobre pensamiento crítico, filosofía y existencia.

{% for post in site.posts %}
  {% if post.categories contains "Filosofia" %}
  - [{{ post.title }}]({{ post.url }})
  {% endif %}
{% endfor %}
