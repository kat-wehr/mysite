---
layout: portfolio
title: Portfolio
permalink: /portfolio/
---

<div class="catalogue">
      <a href="{{ portfolio.url | prepend: site.baseurl }}"> {{ portfolio.title }} </a>

{% for post in portfolio %}
    {% if post.flag == 'portfolio' %}
    <li><a href="{{ site.baseurl }}{{ portfolio.url }}">{{ portfolio.title }}</a></li>
    {% endif %}
{% endfor %}

</div>
