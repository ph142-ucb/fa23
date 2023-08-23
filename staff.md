---
layout: page
title: Staff
nav_order: 3
description: A listing of all the course staff members.
---

# Staff

For lab section schedules for each GSI, see the [calendar]({{ site.baseurl }}/calendar).

## Instructor

<div class="role">
  {% assign instructors = site.staffers | where: 'role', 'Instructor' %}
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>

## Lead GSI
<div class="role">
  {% assign lead_gsi = site.staffers | where: 'role', 'Lead GSI' %}
  {% for staffer in lead_gsi %}
  {{ staffer }}
  {% endfor %}
</div> 

## GSIs

<div class="role">
  {% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
  {% for staffer in teaching_assistants %}
  {{ staffer }}
  {% endfor %}
</div>

## Tutor

<div class="role">
  {% assign tutor = site.staffers | where: 'role', 'Tutor' %}
  {% for staffer in tutor %}
  {{ staffer }}
  {% endfor %}
</div> 

## Course Infrastructure

<div class="role">
  {% assign infra = site.staffers | where: 'role', 'Infrastructure' %}
  {% for staffer in infra %}
  {{ staffer }}
  {% endfor %}
</div>
