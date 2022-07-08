---
layout: page
title: "Home"
---

I am a PhD student in the Computational Imaging Lab at Rice University. 

![Picture](/images/picture0.jpg)
{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
