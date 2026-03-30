---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## [Download my CV as a PDF here](https://daichihiraki.github.io/files/cv.pdf)

Education
======
* Ph.D. student in Economics, The University of Tokyo (Current)
* M.A. in Economics, The University of Tokyo, 2024
* B.A. in Economics, The University of Tokyo, 2022

Scholarships and Awards
======
* **Research Fellowship for Young Scientists (DC2)**, Japan Society for the Promotion of Science (JSPS), 2026--2028

Skills
======
* **Programming**: R (Rcpp), Python
* **Languages**: Japanese (Native), English (Conversational)

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
