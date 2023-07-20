---
layout: page
permalink: /members/
title: members
description: "Our team members:"
nav: true
nav_order: 0
---

## Supervisors

{% for member in site.members.supervisors %}
{% include member.html %}
{% endfor %}

## Masters Students

{% for member in site.members.students %}
{% include member.html %}
{% endfor %}