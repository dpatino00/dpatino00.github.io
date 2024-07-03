---
layout: page
title: Daniel Patino
permalink: /resume/
---

<style>

.main.container h1,h2 {
  text-align: center;
  width: 100%; /* Ensure the h2 spans the full width */
}

.section-block {
  padding: 10px;
  margin-bottom: 10px;
  border-radius: 5px; /* Rounded corners */
}

.education-block {
  background-color: #e6ffe6; /* Light green background */
}

.skills-block {
  background-color: #fffacd; /* Light yellow background */
}

.experience-block {
  background-color: #f5f5f5; /* Light grey background */
}

.project-block {
  background-color: #ffe4e1; /* Light pink background */
}

.research-block {
  background-color: #f0e68c; /* Khaki background */
}

.section-separator {
  border: 2;
  height: 5px;
  background: #384743;
  margin: 5px 0;
  padding:0;
}
</style>

## Education

{% include resume/education.html %}

<div class="section-separator"></div>

## Technical Skills

{% include resume/technical_skills.html %}

<div class="section-separator"></div>

## Professional Experience

{% include resume/experience.html %}

<div class="section-separator"></div>

## Academic Projects @ Northeastern

{% include resume/academic_projects.html %}

<div class="section-separator"></div>

## Research Experience

{% include resume/research.html %}
