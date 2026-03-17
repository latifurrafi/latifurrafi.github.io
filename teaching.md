---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: false
classes: page-links-blue
---

{% include base_path %}

<p>
  I work as a <a href="https://ostad.app/instructor/204088" target="_blank" rel="noopener">Teaching Assistant for DevOps and Cloud Computing at Ostad</a>, where I support students in learning modern infrastructure and deployment practices. My role focuses on helping learners understand core DevOps concepts, cloud architecture, and real-world software deployment workflows.
</p>

<p>
  In this role, I assist students with hands-on projects involving containerization, CI/CD pipelines, and cloud deployment. I regularly help debug deployment issues, guide students through infrastructure design decisions, and ensure they gain practical experience building production-style systems.
</p>

<p>
  Through mentoring and technical support, I have helped guide a large cohort of learners in developing real-world DevOps skills and understanding modern software delivery practices.
</p>

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}

