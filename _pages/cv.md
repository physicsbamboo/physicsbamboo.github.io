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
* B.S. in Physics, Beijing Normal University, 2018
* M.S. in Physics, Northeastern University, 2020
* Ph.D in Particle Physics, Northeastern University, 2023 (expected)

  
Skills
======
* Programming languages: 
  * C++, C, Python, Fortran, 
* Software packages: 
  * Root, Matlab, Xshell, LaTeX, Mathematica, LABVIEW
* Astrophysics packages: CAMB, CosmoMC, Cobaya, CosmoRec

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
