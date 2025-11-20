---
layout: category
title: Fé y ética
permalink: /fe_y_etica/
category: fe
description: Escrituras, reflexiones sobre fe cristiana, análisis teológicos y ética aplicada al acto médico y a la vida.

---

{% for post in site.posts %}
  {% if post.categories contains "fe" %}
  - [{{ post.title }}]({{ post.url }})
  {% endif %}
{% endfor %}
