---
layout: page
title: ALICE v2
description: Autonomous humanoid soccer robot developed from mechanical architecture through assembly and testing.
img: assets/img/projects/alice-v2.jpg
importance: 1
category: humanoid
lang: en
permalink: /en/projects/alice-v2/
---

<link rel="stylesheet" href="{{ '/assets/css/alice-project.css' | relative_url }}">

<article class="alice-showcase">
  <div class="alice-language" aria-label="Language selection"><a href="{{ '/projects/alice-v2/' | relative_url }}" lang="ko">한국어</a><span aria-hidden="true">·</span><strong>English</strong></div>

  <header class="alice-hero">
    <div><p class="alice-eyebrow">Humanoid Robotics · Featured Project</p><h1>Autonomous Humanoid <span>ALICE v2</span></h1></div>
    <div class="alice-hero-copy">
      <p class="alice-lede">A compact robot that integrates mechanical architecture, lightweight structures, sensing, and electronics for natural bipedal walking and autonomous soccer tasks.</p>
      <div class="alice-tags" aria-label="Project keywords"><span class="alice-tag">Mechanical Architecture</span><span class="alice-tag">20 DoF</span><span class="alice-tag">Creo</span><span class="alice-tag">ROS</span></div>
      <div class="alice-actions"><a class="alice-button primary" href="#development">Development</a><a class="alice-button" href="#validation">Validation</a><a class="alice-button" href="{{ '/assets/pdf/jeonghoon-choi-portfolio.pdf' | relative_url }}" target="_blank" rel="noopener">Full PDF</a></div>
    </div>
  </header>

  <figure class="alice-figure">
    <a href="{{ '/assets/img/projects/alice-v2.jpg' | relative_url }}" target="_blank" rel="noopener"><img src="{{ '/assets/img/projects/alice-v2.jpg' | relative_url }}" alt="ALICE v2 humanoid robot and key specifications"></a>
    <figcaption>ALICE v2: a 20-DoF humanoid platform for autonomous walking and soccer tasks.</figcaption>
  </figure>

  <div class="alice-metrics" aria-label="Hardware specifications"><div class="alice-metric"><strong>136 cm</strong><span>Height</span></div><div class="alice-metric"><strong>20 kg</strong><span>Weight</span></div><div class="alice-metric"><strong>20</strong><span>Degrees of freedom</span></div><div class="alice-metric"><strong>6 DoF</strong><span>Each leg</span></div></div>

  <section class="alice-section alice-intro-grid" id="overview">
    <div><p class="alice-eyebrow">Project Overview</p><h2>A humanoid built by solving structure and system integration together.</h2></div>
    <div class="alice-copy"><p>ALICE v2 was developed as an AI-based autonomous soccer robot. Its hardware combines six-degree-of-freedom legs for natural walking, lightweight parts sized for target mass and torque, and modular lower-body structures designed for practical maintenance.</p><p>Cameras, force-torque sensors, batteries, and the main computer were packaged within a constrained body envelope. My work covered the complete hardware cycle from architecture and CAD through fabrication, assembly, and motion testing.</p></div>
    <div></div>
    <div class="alice-takeaways" aria-label="Key contributions">
      <article class="alice-card"><span class="alice-card-index">01 · Architecture</span><h3>Six-DoF leg architecture</h3><p>Defined the joint axes and structural arrangement around walking motion and usable joint range.</p></article>
      <article class="alice-card"><span class="alice-card-index">02 · Integration</span><h3>Sensor and electronics packaging</h3><p>Integrated cameras, lower-body sensors, batteries, and the main computer in a serviceable structure.</p></article>
      <article class="alice-card"><span class="alice-card-index">03 · Validation</span><h3>From assembly to motion tests</h3><p>Checked fabrication tolerances and assembly, then validated full-body motion in a soccer environment.</p></article>
    </div>
  </section>

  <section class="alice-section alice-band" id="development">
    <div class="alice-section-heading"><p class="alice-eyebrow">Engineering Decisions</p><h2>Lightweight construction, precise alignment, and serviceability in one structure.</h2></div>
    <div class="alice-method-grid">
      <article class="alice-card"><span class="alice-card-index">01</span><h3>Joint alignment</h3><p>Aligned the X, Y, and Z rotational axes to intersect consistently in their respective planes.</p></article>
      <article class="alice-card"><span class="alice-card-index">02</span><h3>Lightweight design</h3><p>Designed primarily in AL6061 and reduced part loads to manage actuator capacity, mass, and cost.</p></article>
      <article class="alice-card"><span class="alice-card-index">03</span><h3>Modules and tolerances</h3><p>Used compatible fixtures and insertion features to support repeated tests and control tolerance stack-up.</p></article>
      <article class="alice-card"><span class="alice-card-index">04</span><h3>Compact packaging</h3><p>Selected bevel gears around the knees and ankles while reserving torso volume for electronics.</p></article>
    </div>
    <figure class="alice-figure"><a href="{{ '/assets/img/projects/alice-v2-development.jpg' | relative_url }}" target="_blank" rel="noopener"><img src="{{ '/assets/img/projects/alice-v2-development.jpg' | relative_url }}" alt="ALICE v2 3D model, system layout, and RoboCup assembly"></a><figcaption>Engineering progression from 3D modeling and system packaging to on-site assembly at RoboCup.</figcaption></figure>
  </section>

  <section class="alice-section" id="validation">
    <div class="alice-section-heading"><p class="alice-eyebrow">Build & Validation</p><h2>The design was carried through fabrication, assembly, and full-body motion testing.</h2></div>
    <div class="alice-validation-grid">
      <figure class="alice-figure"><a href="{{ '/assets/img/projects/alice-v2-validation.jpg' | relative_url }}" target="_blank" rel="noopener"><img src="{{ '/assets/img/projects/alice-v2-validation.jpg' | relative_url }}" alt="ALICE v2 component selection, assembly, fabrication, and motion-test process"></a><figcaption>A four-stage process: component selection, design requirements, fabrication, and assembly with motion testing.</figcaption></figure>
      <div class="alice-result"><p class="alice-eyebrow">Outcome</p><h3>Connected mechanical design to robot behavior</h3><ul><li>Selected actuators and mechanical parts using a 2.5 safety factor</li><li>Reviewed leg layout before assembly and verified full-body integration</li><li>Confirmed stable standing with the completed exterior</li><li>Tested whole-body motion in a real soccer environment</li></ul></div>
    </div>
  </section>

  <footer class="alice-cta"><p>Explore more humanoid, rehabilitation, and interaction-robot projects.</p><div class="alice-actions"><a class="alice-button" href="{{ '/en/projects/' | relative_url }}">All projects</a><a class="alice-button primary" href="{{ '/en/portfolio/' | relative_url }}">Portfolio PDF</a></div></footer>
</article>
