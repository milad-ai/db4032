---
layout: page
title: Staff
description: A listing of all the course staff members.
---

# Staff

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
## Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}
# About the Instructor
### Education
**Shahid Beheshti University**   
Computer Science - Soft Computing and Artificial Intelligence  
- Ph.D.  (2023 - 2027)
- Cumulative Grade: 18.94/20

**University of Tabriz**    
Computer Science - Soft Computing and Artificial Intelligence  
- M.S.  (2018 - 2020)
- Cumulative Grade: 19.02/20

### Contact Information

**Phone:** +989370174459
