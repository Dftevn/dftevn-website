---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% capture content %}

{% include figure.html image="images/team/team_1.jpg" %}
{% include figure.html image="images/team/team_2.jpg" %}
{% include figure.html image="images/team/team_3.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
