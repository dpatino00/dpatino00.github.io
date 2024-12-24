---
layout: page
title: "Projects"
permalink: /projects/
---
<style>
/* Grid Layout for projects, two projects per row */
.projects-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}
.project-card {
  width: calc(50% - 10px);
  background-color: #f8f8f8;
  border: 1px solid #ddd;
  border-radius: 5px;
  overflow: hidden;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
  padding-bottom: 40px;
  position: relative;
}

/* Card customizations */
.project-card a h3 {
  margin: 10px;
  font-size: 1.2em;
  color: #666;
  transition: color 0.3s ease;
}

.project-card a {
  text-decoration: none;
  color: inherit;
}

.project-card a:hover h3 {
  color: #007BFF;
  text-decoration: underline;
}

.project-card p {
  margin: 10px;
  color: #666;
}
.project-card a {
  text-decoration: none;
  color: inherit;
}
.project-card:hover {
  transform: translateY(-5px);
  color: #384743;
}

/* Github icon */
.github-icon {
  position: absolute;
  bottom: 10px;
  font-size: 1.5em;
  transition: color 0.3s ease;
}
.project-card:hover .github-icon {
  color: #007BFF;
}
</style>

<div class="projects-grid">
  {% for project in site.data.projects %}
  <div class="project-card">
    <a href="{{ project.link }}">
      <h3>{{ project.title }}</h3>
    </a>
    <p>{{ project.description }}</p>
    <a href="{{ project.link }}" class="github-icon">
        {% include icon.html id="github" title="GitHub" %}
    </a>
  </div>
  {% endfor %}
</div>

\* Project was completed as part of Northeastern University coursework. Please request collaborator access.