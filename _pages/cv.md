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
* Ph.D in Biomedical Engineering, King's College London, 2024 (expected)
* M.S. in Healthcare Technologies, King's College London, 2020
* B.S. in Biomedical Engineering, Universidad Carlos III de Madrid, 2019
* B.S. in Biomedical Engineering, University of New South Wales, 2019

Work experience
======
* Fall 2022 - Spring 2023: Research Assistant in Medical Robotics
  * Centre for Artificial Intelligence and Robotics Chinese Academy of Science Hong Kong 
  * Duties includes: Creation of a robotic set up for force and visual data collection. The creation of basic and re-usable templates for soft-tissue simulation in SOFA with haptic feedback.
  * Supervisor: Hongbin Liu

* Summer 2018: Research Assistant
  * Biocruces Bizkaia
  * Duties included: Generation of a specific brain map for conditions affecting social skills. Writing and revising exercises and chapters for a book on "Computational Neuroscience"
  * Supervisor: Jesús M. Cortés Díaz

  
Skills
======
* Python
  * Pytorch
  * Image processing
* SOFA
  * SOFAPython3
  * Plugin building
* C++
* Rust

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
  
Management
======
* Currently managing 3 group repositories in Github
* I have lead a software project for the creation of a SOFA simulation scene that was granted a patent
