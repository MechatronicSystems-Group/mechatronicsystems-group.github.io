---
layout: page
permalink: /members/
title: Members
description: "Our Team members:"
nav: true
nav_order: 0
---

<!-- Empty page content; the layout will handle the display -->

<!-- Display supervisors -->
{% if site.data.members.supervisors %}
## Supervisors
<div class="members-list">
  {% for supervisor in site.data.members.supervisors %}
    {% include members/member.html member=supervisor %}
  {% endfor %}
</div>
{% endif %}

<!-- Display Masters Students -->
{% if site.data.members.students %}
## Masters Students
<div class="members-list">
  {% for student in site.data.members.students %}
    {% include members/member.html member=student %}
  {% endfor %}
</div>
{% endif %}
