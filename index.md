---
layout: page
title: 新生代
tagline: 关注工人，传播马克思主义
---
{% include JB/setup %}

#最新文章

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a><br>{{ post.excerpt }}</li>
  {% endfor %}
</ul>
