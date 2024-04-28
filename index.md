---
layout: index
title: Home
---
{% for post in site.home %}
<div class="post">
<div class="post-title"><h1>{{ post.title }}</h1></div>
<div class="post-content">{{ post.content }}</div>
</div>
{% endfor %}