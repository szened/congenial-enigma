---
title: Blog
layout: "layouts/base.njk"
---

<ul>
  <li><a href="/">home</a></li>
</ul>

## Blog posts

<ul>
{% for post in collections.posts %}
<li><a href="{{ post.url }}">{{ post.data.title }}</a></li>
{% endfor %}
</ul>
