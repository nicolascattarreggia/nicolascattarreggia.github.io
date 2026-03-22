---
title: "Teaching"
permalink: /teaching/
author_profile: true
layout: archive
---

{% include teaching-nav.html %}

<div class="teaching-wrapper">

  {% assign current_items = site.data.teaching.2025-2026 %}
  {% include teaching-section.html
    section_id="2025-2026"
    section_title="2025-2026"
    items=current_items
    open=true
  %}

  {% assign past_items = site.data.cv.past %}
  {% include cv-section.html
    section_id="past"
    section_title="Past Appointments"
    items=past_items
    open=false
  %}

  {% assign education_items = site.data.cv.education %}
  {% include cv-section.html
    section_id="education"
    section_title="Education"
    items=education_items
    open=false
  %}

  {% assign honours_items = site.data.cv.honours %}
  {% include cv-section.html
    section_id="honours"
    section_title="Honours and Awards"
    items=honours_items
    open=false
  %}

  {% assign editorial_items = site.data.cv.editorial %}
  {% include cv-section.html
    section_id="editorial"
    section_title="Editorial"
    items=editorial_items
    open=false
  %}

  {% assign qualifications_items = site.data.cv.qualifications %}
  {% include cv-section.html
    section_id="qualifications"
    section_title="Qualifications"
