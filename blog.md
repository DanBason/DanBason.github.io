---
layout: page
title: Blog
permalink: /blog/
---

Writing on AI governance, policy analysis, and data projects.

{% for post in site.posts %}
<div style="margin-bottom: 1.5rem;">
  <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
  <p style="color: #666; font-size: 0.9rem;">{{ post.date | date: "%B %-d, %Y" }}</p>
  <p>{{ post.excerpt }}</p>
</div>
{% endfor %}