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
- Supervisor: Dr. Kourosh Parand
- Cumulative Grade: 18.94/20


**University of Tabriz**    
Computer Science - Soft Computing and Artificial Intelligence  
- M.S.  (2018 - 2020)
- Thesis Title: Sentiment Analysis of Social Media Users for Opinions Polarity Detection Using Deep Learning Techniques
- Supervisor: Dr. Jafar Razmara
- Advisor: Dr. Shahriar Lotfi
- Cumulative Grade: 19.02/20
  - Ranked 1st among M.S students of CS
  - Selected as the Exceptionally Talented

### Contact Information

**Phone:** +989370174459
