---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Control Science and Engineering, Nanjing University of Aeronautics and Astronautics, 2026 (expected)
* B.E. in Automation, Nanjing Institute of Technology, 2020
  
Publications
======
<ul>
  {% assign first_pubs = site.publications | where: "role", "first" %}
  {% for post in first_pubs reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>


Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
