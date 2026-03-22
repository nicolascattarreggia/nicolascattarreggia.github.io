---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% assign teaching_years = site.data.teaching %}

<div class="teaching-container">

  {% for year in teaching_years %}
    <details class="teaching-block">
      <summary>{{ year.academic_year }}</summary>

      {% for item in year.courses %}
        <div class="teaching-course">
          <strong>{{ item.course }}</strong><br>
          {{ item.institution }}<br>
          {{ item.role }}<br>
          {{ item.description }}
        </div>
      {% endfor %}
    </details>
  {% endfor %}

</div>
