---
title: "News"
layout: textlay
excerpt: "Mitra Lab at IRCL (Lille)."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
