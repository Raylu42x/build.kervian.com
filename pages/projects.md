---
layout: page
title: Projects
permalink: /projects/
---

A collection of all projects.

{% for post in site.posts %}
  {% if post.tags contains "project" %}
  - [{{ post.title }}]({{ post.url }})
  {% endif %}
{% endfor %}
