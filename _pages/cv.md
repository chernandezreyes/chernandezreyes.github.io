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
* B.Eng. in Mechatronics Engineering, Universidad de Monterrey, 2015
* M.Eng. in Systems and Control Engineering, Tokyo Institute of Technology, 2018
* Ph.D in Systems and Control Engineering, Tokyo Institute of Technology, 2021 (expected)

Work experience
======
* Apr. 2019 - present: Teaching Assistant
  * Tokyo Institute of Technology, Online Education Development Office
  * Duties: Development of contents for Massive Open Online Courses (MOOCs) on [edx.org](https://www.edx.org/school/tokyotechx)

* Sep. 2015 - Aug. 2016: Systems Developer
  * Castelec Internacional SA. de CV.
  * Duties: Development of Android applications. Systems Integration

* Sep. 2014 - Dec. 2014: Internship
  * Hibot Co. 
  * Duties: Development of embedded software for mobile robots
  
Skills
======
* Programming: Python, C/C++, C\#, Java
* Data analysis and AI libraries: Numpy, Scipy, Scikit-learn, Pandas, Tensorflow, OpenCV
* Other technologies: Linux, ROS, SBCs (Raspberry Pi, Odroid, Nvidia Jetson)
* Languages:
  * English (fluent)
  * Japanese (fluent)
  * Spanish (native)

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
