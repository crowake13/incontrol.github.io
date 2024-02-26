---
title: Hello World
layout: "base.njk"
---

Posts:

{% for post in collections.posts %}

- [{{ post.data.title }}]({{ post.url }})
{% endfor %}