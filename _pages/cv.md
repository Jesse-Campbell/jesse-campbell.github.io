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
* Ph.D. in Mathematics, University of Florida, 2030 (expected)
* M.S. in Mathematics, University of Florida, 2027 (expected)
* B.S. in Applied Mathematics and Computational Science, Duke Kunshan University, 2025

Work experience
======
* Summer 2023: Testing Team Intern
  * KONE Elevators China
  * Duties includes: Integration of API with database (coded in SQL); Writing test cases to test API
  * Supervisor: Li Lin
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

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
  
Service and leadership
======
