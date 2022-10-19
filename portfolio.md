---
layout: default
title: "Portfolio"
---
questo e' il mio portfolio

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
