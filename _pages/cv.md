---
title: "CV"
permalink: /cv/
author_profile: true
layout: archive
---

# Curriculum Vitae

<div class="cv-download">
  <a class="btn btn--primary" href="/files/CV_Nicola_Scattarreggia.pdf" target="_blank">Download CV (PDF)</a>
</div>

{% include cv-nav.html %}

<div class="cv-wrapper">

  {% assign current_items = site.data.cv.current %}
  {% include cv-section.html
    section_id="current"
    section_title="Current Appointments"
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
    items=qualifications_items
    open=false
  %}

</div>
