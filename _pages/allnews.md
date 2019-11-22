---
title: "News"
layout: textlay
excerpt: "Valerie de Anda Personal Website'"
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
  <p>{{ article.date }} <br>
      {{ article.headline }}
  </p>
{% endfor %}
