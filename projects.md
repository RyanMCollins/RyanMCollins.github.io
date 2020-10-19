---
title: Projects
layout: default
---

{% assign projects=site.projects | sort: "date" | reverse %}
{%- for project in projects -%}
    <div class="row section">
        <div class="col">
            {% include project.html %}
        </div>
    </div>
{%- endfor -%}