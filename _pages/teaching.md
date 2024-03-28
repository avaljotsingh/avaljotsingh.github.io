---
layout: page
title: Teaching
permalink: /teaching/
# description: Materials for courses you taught. Replace this text with your description.
nav: false
nav_order: 3
---

{% for course in site.teaching %}
  <h2><a href="{{ course.url }}">{{ course.title }}</a></h2>
  <!-- Add more rendering logic here if needed -->
{% endfor %}
