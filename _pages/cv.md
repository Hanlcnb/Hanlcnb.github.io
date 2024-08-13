---
layout: archive
title: "个人简历"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* 浙江海洋大学，计算机科学与技术，2021~2025

  
Skills
======
* 熟悉java，c，了解python，c++
* 熟练掌握计算机基础
  * 计算机网络，操作系统，数据结构，计组
* 熟悉数据库

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
  
