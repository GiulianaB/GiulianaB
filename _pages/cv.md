---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Current Position
======
Postdoctoral fellow in the University of Victoria, Canada, under the supervision of Jody Klymak, Tetjana Ross and Guoqi Han.

Education
======
* Ph.D in Universidad de Buenos Aires (2018-2023)
* Licenciada in Ocean Science (2016)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
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
  
