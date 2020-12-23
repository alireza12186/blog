---
layout: default
title: موضوعات
---
<div class="main-content">
    <article class="module color-3">
            <h1>موضوعات</h1>
            <hr>
{% for category in site.categories %}
  <h3>{{ category[0] }}</h3>
  <ul>
    {% for post in category[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
