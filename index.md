---
layout: default
title: Index
---

# Recent Posts:

{% for post in site.posts %}
* [{{ post.title }}]({{ post.url }})
{% endfor %}
