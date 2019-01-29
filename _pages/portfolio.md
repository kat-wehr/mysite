---
layout: portfolio
title: Portfolio
permalink: /portfolio/
---

<div class="catalogue">
      <a href="{{ portfolio.url | prepend: site.baseurl }}" class="catalogue-item">
      <div>
        <h1 class="catalogue-title">{{ portfolio.title }}</h1>
        <div class="catalogue-line"></div>

        <p>
          {{ portfolio.content | strip_html | truncatewords: 30 }}
        </p>

      </div>
    </a>
 
</div>
