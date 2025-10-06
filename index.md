---
layout: home
title: CR2 Workshop @ ICRA 2026
---

## Debates on the Path Towards Generalizable Contact-Rich Robotics: Control and Representation
Workshop at ICRA 2026

### Abstract
Contact-rich robotics, where robots skillfully interact with the world through physical contact, represents one of the most challenging frontiers in robotics today. Recently, we have seen significant advances in contact representation and control algorithms that also have led to widening gaps between communities. This workshop aims to close these gaps by bringing together leading researchers in the field to participate in a series of facilitated discussions to identify promising research directions, and work toward consensus on key open problems that must be solved to achieve truly generalizable contact-rich robotics systems in the open world.

### Panelists
We are excited to welcome the following expert guest panelists from across both industry and academia with representation from different genders, geographic locations, and career stages.
<div class="projects">
<!-- Display projects without categories -->
{% assign sorted_projects = site.projects | sort: "importance" %}
  <!-- Generate cards for each project -->
{% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="grid">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
{% endif %}
</div>
