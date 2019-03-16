---
layout: post
title:  "test nav22222"
date:   2019-03-17 00:30:50 +0800
categories: jekyll update
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
