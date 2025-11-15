---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="https://github.com/FokKwan/huojun.github.io/blob/master/files/Academic_CV.pdf">my Google Scholar profile</a>.</div>
{% endif %}


Education
======
* Ph.D in Control Science and Technology, Huazhong University of Science and Technology, 2025
* B.S. in Mechanical Engineering, Northeastern University (China), 2018

Work experience
======
* 2026 - now: Research Associate
  * The Chinese University of Hong Kong
  * Major: Medical robots
  * Supervisor: Cheng Shing Shin


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
* Currently signed in to 43 different slack teams
