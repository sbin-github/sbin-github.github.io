---
layout: default
title: Home
description: "Seongbin An — KIMM researcher working on humanoid locomotion, model-based control, and sim-to-real."
---

# Seongbin An

<p class="role">Robotics researcher · Korea Institute of Machinery and Materials (KIMM)</p>

<div class="intro">
<p>My work is in the control of physical robots, particularly humanoid locomotion. I develop and deploy reinforcement-learning policies and study the actuator dynamics, feedback control, and system integration that determine their behavior on real hardware.</p>
<p>My earlier research covered nonlinear motion planning and engineering optimization at ADD, and wearable robot control and pneumatic soft sensing at KAIST.</p>
</div>

## KAIROS humanoid demonstrations <span class="section-date">2026</span>

<div class="home-work">
  <div>
    <h3>KAIROS v0.5 · Locomotion</h3>
    <p>I developed the locomotion policy and was responsible for <strong>both humanoids</strong> presented at KIMM's 50th-anniversary demonstration.</p>
    <h3>KAIROS v0.7 · Locomotion and dancing</h3>
    <p>I developed locomotion and dancing policies for <strong>one humanoid</strong> at the 2026 Global Forum on Mechanical Engineering.</p>
    <p><a href="{{ '/projects' | relative_url }}#public-kairos-demonstrations">Project details and demonstrations</a></p>
  </div>
  <figure class="project-photo">
    <img src="{{ '/images/kairos-v05-anniversary.jpg' | relative_url }}" alt="Two KAIROS v0.5 humanoids at KIMM's 50th-anniversary demonstration" width="600" height="399">
    <figcaption>KAIROS v0.5 at KIMM's 50th-anniversary demonstration, 2026.</figcaption>
  </figure>
</div>

## Research interests

Humanoid locomotion and whole-body coordination; reinforcement learning and model predictive control; actuator and mechanism modeling; sim-to-real integration. Earlier work includes wearable robot control, soft sensing, and human-motion measurement.

## Experience

<dl class="experience">
  <dt>Korea Institute of Machinery and Materials (KIMM)</dt>
  <dd>Humanoid locomotion policy development, actuator dynamics, and deployment of learned control policies on KAIROS.</dd>
  <dt>Agency for Defense Development (ADD)</dt>
  <dd>Motion planning, nonlinear model predictive control, and numerical optimization.</dd>
  <dt>KAIST EXO Lab · 2023–2024</dt>
  <dd>Wearable robot control, pneumatic mechanomyography, and soft sensing.</dd>
  <dt>Dyze Design · 2017</dt>
  <dd>Student intern, Montréal.</dd>
</dl>

## Education

**M.S. in Robotics, KAIST · 2023**  
Thesis: *Enhancing Accuracy of Hand Gesture Recognition and Its Application by Observing Tendons Using Pneumatic Mechanomyography (pMMG)*.

**B.S. in Mechanical Engineering, UNIST · 2021**  
Summa Cum Laude · 1st of 79 students.

## Selected publications

<ol class="bibliography">
{% for pub in site.data.publications %}
{% if pub.selected %}
{% include citation.html pub=pub %}
{% endif %}
{% endfor %}
</ol>

<p class="publication-nav"><a href="{{ '/publications' | relative_url }}">Complete publication list</a></p>
