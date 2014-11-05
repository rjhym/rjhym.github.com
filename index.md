---
layout: page
title: 冷峰的点滴记录
tagline: index
---
{% include JB/setup %}
    
## Sample Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

