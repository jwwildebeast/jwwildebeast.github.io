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
* Ph.D., Industrial and Systems Engineering (in progress), University of Tennessee, Knoxville
* M.S., Industrial and Systems Engineering, University of Tennessee, Knoxville, 2026
* B.S., Computer Science (Software Engineering concentration), Colorado Technical University (Online), 2023  
  * Summa Cum Laude; GPA: 3.98

Work experience
======
* 2024–Present: Graduate Research Assistant, Applied Systems Laboratory (ASL)
  * University of Tennessee, Knoxville
  * Research focus: human-AI collaboration, LLM systems, and complex systems applications.

* 2023–2024: Graduate Research Assistant, Ideation Laboratory (iLab)
  * University of Tennessee, Knoxville
  * Advisor: Dr. Xueping Li
  
Skills
======
* Digital twins
* Optimization
* Software architecture
* Programming
* Machine learning

Selected projects
======
* **graphmem**: Memory layer for large language models supporting shared context, memory archival, and structured note-taking.
* **CortexRuntime**: Runtime for large language model orchestration in which a planner model decomposes missions into subtasks and agents bid for work based on resources, historical task performance, and capabilities.
* **SituationalAwarenessStudy**: Ongoing project investigating how AI assistants influence situational awareness.

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
* Member, Upsilon Pi Epsilon (Computer Science Honor Society)
* Member, Association for Computing Machinery (ACM)
* Member, Institute of Industrial and Systems Engineers (IISE)
* Member, Institute for Operations Research and the Management Sciences (INFORMS)
