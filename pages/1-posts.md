---
layout: default
title: Announcements
permalink: /announcements/
nav: true
---

{% for post in site.posts %}
<a href='{{ site.baseurl}}{{ post.url }}'>
## {{ post.title }}
*{{ post.date }}*
{{ post.excerpt }}
___
</a>
{% endfor %}