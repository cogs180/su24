---
layout: page
title: Course Staff
nav_order: 4
description: A listing of all the course staff members.
---

# Course Staff

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
## Teaching Assistant

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}
