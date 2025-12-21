---
layout: page
title: Projects
---

Below are selected projects that demonstrate how I approach analytical problems, work with real datasets, and generate insights for decision-making.

{% for project in site.projects %}
### [{{ project.title }}]({{ project.url }})

{{ project.summary }}

{% endfor %}
