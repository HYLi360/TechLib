---
title: "TechLib by HYLi360"
layout: default
markdown: kramdown
# Index page
---

<ul>
  {% for page in site.pages %}
    {% if page.path contains '_posts/' %}
      <li><a href="{{ page.url }}">{{ page.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
