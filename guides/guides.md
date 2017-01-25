---
layout: default
title: All Guides
subtitle:
type: guide
categories: 
roles:
status: draft
phases:
  breadcrumbs:
  -
    title: Home
    url: /DDM
 ---

# {{page.title}}
## {{page.subtitle

***

Essentially a site map

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
