---
layout: default
title: Finn James - Home
permalink: /posts
---

{% for post in site.posts %}
  <h1><a class="nounderline black" href="{{ post.url }}">{{ post.title }}</a></h1>
  {{ post.excerpt }}
{% endfor %}