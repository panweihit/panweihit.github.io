---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

## Current Teaching at Manchester
* [COMP24112]([https://studentnet.cs.manchester.ac.uk/ugt/2021/COMP24112/syllabus/](https://studentnet.cs.manchester.ac.uk/syllabus/?code=COMP24112&year=2022)), Machine Learning

## Past Teaching at TU Delft
* Thesis project for Master in Robotics (past topics can be found [here](https://panweihit.github.io/people/))
* [WB3168](https://studiegids.tudelft.nl/a101_displayCourse.do?course_id=59581), Robotic System Identification and Parameter Estimation
* [RO47001](https://studiegids.tudelft.nl/a101_displayCourse.do?course_id=59665), Robot Dynamcis and Control




{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
