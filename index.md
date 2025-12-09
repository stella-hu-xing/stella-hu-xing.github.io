---
layout: home
title: "Welcome"
---

Hi — welcome to my blog. This site uses GitHub Pages + Jekyll.

Below are recent posts:

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%b %-d, %Y" }}
{% endfor %}
