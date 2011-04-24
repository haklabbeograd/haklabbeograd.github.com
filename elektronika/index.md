---
title: Grupa elektronika
layout: default
---

markdown....

{% for post in site.categories.elektronika limit:5 %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  {{ post.content }}
  <em>Posted on {{ post.date | date_to_long_string }}.</em>
{% endfor %}

