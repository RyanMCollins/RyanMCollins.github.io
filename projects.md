---
title: Projects
layout: default
---

{% assign projects=site.projects | sort: "date" | reverse %}
{%- for project in projects -%}
    {% include project.html %}
{%- endfor -%}