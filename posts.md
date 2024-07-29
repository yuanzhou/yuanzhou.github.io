---
layout: page
title: Posts
permalink: /posts/
---

{% for post in site.posts %}
<h3><a href="{{post.url}}">{{post.title}}</a></h3>
<small>{{post.date | date: "%m/%d/%Y"}}</small>
<p>{{ post.excerpt | truncatewords: 40 }}</p>
<br />
{% endfor %}

