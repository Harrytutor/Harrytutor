---
layout: default
title: Diary Entries
---

Here are all my diary entries:

{% for post in site.posts %}
  - [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
