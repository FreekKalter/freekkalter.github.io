---
layout: default
title: Freek Kalter, the blog
---
<div id="home">
  <h1>Freek Kalter, the blog</h1>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div>
