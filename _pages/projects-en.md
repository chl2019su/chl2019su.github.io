---
layout: page
title: projects
permalink: /en/projects/
lang: en
description: Selected robotics projects spanning humanoids, rehabilitation systems, HRI, and biomimetic robots.
nav: false
horizontal: false
---

<div class="mb-4" aria-label="Language selection">
  <a href="{{ '/projects/' | relative_url }}" lang="ko">한국어</a> · <strong>English</strong>
</div>

<div class="projects">
{% assign localized_projects = site.projects | where: "lang", page.lang %}
{% assign sorted_projects = localized_projects | sort: "importance" %}

  <div class="row row-cols-1 row-cols-md-3">
  {% for project in sorted_projects %}
    {% include projects.liquid %}
  {% endfor %}
  </div>
</div>
