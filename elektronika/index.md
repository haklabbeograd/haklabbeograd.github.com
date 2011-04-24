---
title: Grupa elektronika
layout: default
---

{% for post in site.categories.elektronika limit:5 %}
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.content }}
      <em>Posted on {{ post.date | date_to_long_string }}.</em>
{% endfor %}
