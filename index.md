---
title: Fedired Hub
header: Fedired Hub
description: Como fedired puede ayudarte a conectar con la comunidad de software libre.
permalink: /
layout: default
---

{% for post in site.posts %}
  <p class="blog-item"><b><a href="{{ post.url }}">{{ post.title }}</a></b><br>
  <span class="post-description">{{ post.description }}</span><br>
  <span class="post-meta">📅 {{ post.date | date_to_string }}</span></p>
{% endfor %}

<!-- **THESE LINKS ARE HIDDEN ON THE FRONT END** - they're only used for Fedired verification purposes -->
<div class="verification-links">
  <a rel="me" href="https://fedired.com/@fedired">Fedired</a>
  <a rel="me" href="https://fedired.com/@srnovus">Fedired</a>
</div>
