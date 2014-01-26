---
layout: page
title: 
tagline: 入则孝-出则悌-谨而信-泛爱众-而亲仁
comments: false
---
{% include JB/setup %}


文章列表.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

