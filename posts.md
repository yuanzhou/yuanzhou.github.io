---
layout: page
title: Posts
permalink: /posts/
---

{% for post in site.posts %}
[{{post.title}}]({{post.url}}) [{{post.date | date: "%m/%d/%Y"}}]
{% endfor %}

