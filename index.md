---
layout: default
title: Work
---

## SELECTED WORK

<div class="work-grid">
{% for item in site.portfolio %}
  <div class="work-item">
    {% if item.image %}
    <img src="{{ item.image }}" alt="{{ item.title }}">
    {% endif %}
    <div class="work-item-content">
      <h3>{{ item.title }}</h3>
      <p>{{ item.description }}</p>
    </div>
  </div>
{% endfor %}
</div>

<div class="skills">
  <p>Motion Design, Illustration, Art Direction, Kinetic Typography, Explainer Videos, Music Videos, 2D + 3D Animation, Social Media Content, Logo Animation, Concept Visualization</p>
</div>

<section class="contact-section">
  <p class="contact-text">I am open to freelance opportunities and collaborations.</p>
</section>
