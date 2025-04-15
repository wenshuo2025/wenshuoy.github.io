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
* Ph.D in Microelectronics, Peking University, 2026 (expected)
* B.S. in Atmospheric and Oceanic Science, Peking University, 2021

Work experience
======
* Summer 2021: Testing Engineer
  * Pimchip Technology
  * Duties: I designed a custom printed circuit board (PCB) for a commercial compute-in-memory chip and managed the chip testing plan. I successfully tested the targeted function, realized high energy efficiency on the chip, and assisted in writing the paper for ISSCC.

* Summer 2020: Research Assistant
  * Carnegie Mellon University
  * Duties: I developed simulation models on COMSOL for 2D material devices and memristive devices, and evaluated the models with applications. 


Skills
======
* Strong reading, writing, and speaking competencies in English, Mandarin Chinese, and German.
* Coding: Verilog, C/C++, HLS, Python, Parallel programming (OpenMP, CUDA)
* Designing: Full-custom design, Digital design, PCB design, and FPGA prototype engineering.

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
  

  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Experienced in team leadership, having guided and mentored master’s students, undergraduates, and interns across diverse research projects.
* Official Reviewer: AICAS and DAC.
