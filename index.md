---
layout: home
title: Home
nav_exclude: false
nav_order: 1
seo:
  type: Course
  name: Decision Making in the Brain
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

**Instructor: Professor Lucy Lai**  ([lucylai@g.harvard.edu](mailto:lucylai@g.harvard.edu)) \
**TA: Lucy Lai**  ([lucylai@g.harvard.edu](mailto:lucylai@g.harvard.edu)) \
**Lecture: M/W/T/Th 5-6:20PM | Zoom**

Quick Links
*

{% for module in site.modules %}
{{ module }}
{% endfor %}
