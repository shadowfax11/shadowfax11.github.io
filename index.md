---
layout: page
title: "Home"
---

I am a PhD student in the Computational Imaging Lab at Rice University. \
<!-- <img src="/images/picture0.jpg" alt="drawing" width="500"/> -->
<p style="display: flex;">
  <img src="/images/picture1.jpg" alt="drawing" width="400" style="display: inline-flex;"/>
  <span style="float: right;padding-left: 20px;padding-top: 20px;">
    I am interested in developing methods for end-to-end imaging systems or visual display systems using ideas from Image and Signal Processing, Computer Vision, Optics, Deep Learning. In short, I aspire to gain expertise in "full-stack knowledge" of imaging systems and to use it for novel applications - to see the unseen, and in process solve imaging problems in healthcare, robotics, AR/VR, etc.
  </span>
</p>



{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
