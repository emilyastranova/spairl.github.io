---
title: "News"
layout: textlay
excerpt: "SPAIRL at Texas A&M University - Commerce."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br>
<em>{{ article.headline }}</em></p>
{% endfor %}
