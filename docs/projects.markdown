---
layout: projectsHome
title: Projects
permalink: /projects/
---
{% for project in site.projects %}
<li>
    <h2><a href="{{ project.url }}">{{ project.title }}</a></h2>
    {{ project.excerpt }}
</li>
{% endfor %}

