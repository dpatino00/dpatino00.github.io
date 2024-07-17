---
layout: page
title: Daniel Patino
permalink: /resume/
---

<style>
/* Main Container */
.main.container h1,h2 {
  text-align: center;
  width: 100%; /* Ensure the h2 spans the full width */
}

/* Section Block Styling for Resume */
.section-block {
  padding: 10px;
  margin-bottom: 10px;
  border-radius: 5px; /* Rounded corners */
}

.education-block {
  background-color: #e6ffe6; /* Light green */
}

.skills-block {
  background-color: #fffacd; /* Light yellow */
}

.experience-block {
  background-color: #B0E0E6; /* Light grey */
}

.project-block {
  background-color: #ffe4e1; /* Light pink */
}

.research-block {
  background-color: #f0e68c; /* Khaki */
}

/* Divider for different sections */
.section-separator {
  border: 2;
  height: 5px;
  background: #384743;
  margin: 5px 0;
  padding:0;
}

/* Styling for the inline links */
.jump-to-links {
  margin-bottom: 20px;
  text-align: center; /* Center align the links */
}

.jump-to-links a {
  margin-right: 15px;
  text-decoration: none;
  color: #007bff;
  font-weight: bold;
}

.jump-to-links a:hover {
  text-decoration: underline;
}
</style>

<div class="jump-to-links">
  <a href="#education">Education</a>
  <a href="#technical-skills">Technical Skills</a>
  <a href="#professional-experience">Professional Experience</a>
  <a href="#academic-projects">Academic Projects</a>
  <a href="#research">Research</a>
</div>
<div class="section-separator"></div>

## Education

{% include resume/education.html %}

<div class="section-separator"></div>

## Technical Skills

{% include resume/technical_skills.html %}

<div class="section-separator"></div>

## Professional Experience

{% include resume/experience.html %}

<div class="section-separator"></div>

## Academic Projects

{% include resume/academic_projects.html %}

<div class="section-separator"></div>

## Research

{% include resume/research.html %}
