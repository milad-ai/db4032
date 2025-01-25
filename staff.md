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
- Supervisor: **Dr. Kourosh Parand**
- Cumulative Grade: **18.94**/20


**University of Tabriz**    
Computer Science - Soft Computing and Artificial Intelligence  
- M.S.  (2018 - 2020)
- Supervisor: **Dr. Jafar Razmara**
- Advisor: **Dr. Shahriar Lotfi**
- Cumulative Grade: **19.02**/20
  - Ranked 1st among M.S students of CS
  - Selected as the Exceptionally Talented


## TEACHING EXPERIENCE

### Kashmar Institute of Higher Education (Spring 2023  )
- **Data Structures and Algorithms**  
- **Computer Architecture**  
- **Principles of Computer Systems**  
- **Theory of Languages and Automata**  
- **Principles of Data Science**  [link](http://ds.miladvazan.ir/) 

### Kashmar Institute of Higher Education (Fall 2022)
- **Artificial Intelligence and Expert Systems** [link](http://ai1401k.miladvazan.ir/) 
- **Computer Architecture**  

### Islamic Azad University, Bardaskan Branch (Fall 2022)
- **Artificial Intelligence**  
- **Data Structure**  
- **Computer Architecture**  

  


### Contact Information

**Phone:** +989370174459
