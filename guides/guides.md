---
layout: default
title: Guides - Index
subtitle: These guides will help you design, share and use data.
type: guide
status: Alpha
breadcrumbs:
  -
    title: Home
    url: /DDM
---

{% for cat in site.category-list %}
## {{ cat }}
<ul>
  {% for page in site.pages %}
      {% for pc in page.categories %}
        {% if pc == cat %}
          <li><a href="/DDM{{ page.url }}">{{ page.title }}</a></li>
        {% endif %}   <!-- cat-match-p -->
      {% endfor %}  <!-- page-category -->
  {% endfor %}  <!-- page -->
</ul>
{% endfor %}  <!-- cat -->
