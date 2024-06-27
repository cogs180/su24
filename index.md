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

## Course Information

|-------------|--------|
| **Instructor** | [Lucy Lai, Ph.D.](https://www.lucy-lai.com) ([lucylai@g.harvard.edu](mailto:lucylai@g.harvard.edu)) |
| **TA**         | Janet Tung ([j5tung@ucsd.edu](mailto:j5tung@ucsd.edu))                |
| **Dates**      | July 1 - August 3, 2024   |
| **Lectures**   | M/T/W/Th at 5-6:20pm PDT  |
| **Discussion**   | T/Th at 1-1:50pm PDT (Optional, but at least 1 required) |
| **Prerequisites**  | COGS 17 and COGS 108 or 109 (or instructor permission) |
| **Credits**   | 4.00 |
| **Website**  | [cogs180.github.io/su24](cogs180.github.io/su24) |

See current (tentative) syllabus [here](https://docs.google.com/document/d/1YbU2V1225l-x12fQKUVlMM4-4mK96GNLAb7WUcLVrbA/edit?usp=sharing) 

{% for module in site.modules %}
{{ module }}
{% endfor %}
