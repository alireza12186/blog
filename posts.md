---
layout: default
title: همه مطالب
---
<div class="main-content">
    <article class="module color-3">
            <h1>همه مطالب</h1>
            <hr>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
