---
layout: portfolio
title: Portfolio
permalink: /portfolio/
---

{% for portfolios in site.portfolio %}


<a href="{{ portfolio.url | prepend: site.baseurl }}">
        <h2>{{ portfolio.title }}</h2>
</a>

<p class="post-excerpt">{{ portfolio.description | truncate: 160 }}</p>

{% endfor %}
