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
#* Doctoral student in chemistry, Westlake University, 2026 (expected)
* M.S. in Materials and Chemical Engineering,  Shanghai Institute of Organic Chemistry, 2025
* B.S. in Polymer materials and Engineering, Yanshan University, 2022

Work experience
======

* Research Assistant
  * Westlake University
  * Duties included: Molecular design and application of organic electronic materials
  * Supervisor: Professor Shang
  
Skills
======
* Small molecule synthesis and polymer synthesis
* Analysis and characterization
  * NMR
  * HPLC-MS and GPC
  * FTIR, UV-vis and PL spectroscopy
* Gaussian, Orca, Gromacs…

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
  

