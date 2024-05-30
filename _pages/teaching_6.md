---
layout: page
permalink: /teaching/
title: Teaching
description: 
nav: true
nav_order: 6
---

{% include courses.html past='false' %}

<a data-toggle="collapse" href="#pastCourses" role="button">
    <i class="fas fa-chevron-down"></i> Show Past Courses
</a>

<div class="collapse" id="pastCourses">
      {% include courses.html past='true' %}
</div>
