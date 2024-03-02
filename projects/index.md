---
title: Projects
nav:
  order: 2
  tooltip: Our current projects
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="project-card" data="projects" filters="group: featured" %}

{% include section.html %}

## More

{% include list.html component="project-card" data="projects" filters="group: " style="small" %}
