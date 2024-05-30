---
layout: page
permalink: /teaching/
title: Teaching
description: Materials for courses you taught. Replace this text with your description.
nav: true
nav_order: 6
---

Teaching is one of our core contributions at the University of St. Gallen.
Besides sharing knowledge with new generations of computer scientists,
we value the insights and view of the continuously renewing student body on our disciplines.
Further, we enjoy close research collaboration with motivated students,
often performed as a thesis or in a HiWi position.
We invite you to join our [courses](#courses),
to write a [thesis](#theses) with us or to [join us as a HiWi or PhD student]({{ '/open-positions' | relative_url }}).

## Courses

{% include courses.html past='false' %}

<a data-toggle="collapse" href="#pastCourses" role="button">
    <i class="fas fa-chevron-down"></i> Show Past Courses
</a>

<div class="collapse" id="pastCourses">
      {% include courses.html past='true' %}
</div>
