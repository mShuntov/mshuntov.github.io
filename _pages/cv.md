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
* Ph.D in Astrophysics, Sorbonne Université / Institut d'Astrophysique de Paris, 2022
* M.S. in Physics, University of Zagreb, 2018
* B.S. in Physics, University of Zagreb, 2016

Work experience
======
* 2022 – present: Postdoctoral Researcher
  * Cosmic DAWN Center, Niels Bohr Institute / University of Copenhagen
  * Galaxy formation and evolution, multi-band imaging surveys, machine learning

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
