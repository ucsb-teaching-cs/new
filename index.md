---
layout: minimal
title: ULA Training at UCSB
nav_exclude: true
seo:
  type: Course
  name: UCSB Undergraduate Learning Assistant (ULA) Training Course
last_modified_date: 2021-04-14 04:04
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

**Teaching Computer Science** (CS 190J) course is designed to support the [Computer Science department’s Undergraduate Learning Assistant (ULA) Program](http://cs.ucsb.edu/education/undergrad/ut). The course is offered to outstanding students who are interning as tutors in CS courses for the very first time. Students enrolled into the course are selected through an application process ~~that typically involves an in-person interview~~. Lecture/discussion surveys current research and best practices in CS pedagogy, including student development theories, different pedagogical techniques, and methods for assessing learning. Students gain experience working one-on-one with students, fostering positive learning environments, and providing feedback on student work.

Students who successfully complete this course will earn 4 units towards their major field electives by serving as a tutors. They will also be eligible to apply for paid tutoring positions in lower division undergraduate courses in the following quarters.

Several Computer Science professors are involved in teaching this course and coordinating the ULA program.

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

# Course Offerings
* [Spring 2021](https://ucsb-teaching-cs.github.io/s21) taught by Prof. K
* [Winter 2021](https://ucsb-teaching-cs.github.io/w21) taught by Prof. K
* [Fall 2020](https://ucsb-teaching-cs.github.io/f20) taught by Phill Conrad
* [Spring 2020](https://ucsb-teaching-cs.github.io/s20) taught by Richert Wang
* [Winter 2020](https://ucsb-teaching-cs.github.io/w20-mirza) taught by Diba Mirza
* [Fall 2019](https://ucsb-teaching-cs.github.io/f19) taught by Richert Wang
* [Spring 2019](https://ucsb-teaching-cs.github.io/s19) taught by Diba Mirza
* [Winter 2019](https://ucsb-teaching-cs.github.io/w19) taught by Diba Mirza
* [Fall 2018](https://ucsb-teaching-cs.github.io/f18) taught by 
* [Spring 2018](https://ucsb-teaching-cs.github.io/s18) taught by 

# Resources and References

{% for module in site.modules %}
{{ module }}
{% endfor %}

{% for topic in site.topics %}
{{ topic }}
{% endfor %}

