---
layout: archive
title: ""
permalink: /
author_profile: true
---

I am a Ph.D. student at Robot Learning Lab in the Department of Electrical and Computer Engineering at Seoul National University, South Korea, advised by Prof. Songhwai Oh.
I received my B.S. in Electrical and Computer Engineering from Seoul National University in 2019.
My research focuses on vision-language models for robotics, with broader interests in reinforcement learning, imitation learning, lifelong learning, and skill discovery.



# Key Publications
<ul class="publication-list">
  {% for pub in site.data.publications %}
  <li>
    <div class="publication-item">
      <div class="publication-image">
        <img src="/images/profile.png" alt="{{ pub.title }}">
      </div>
      <div class="publication-content">
        <h3>{{ pub.title }}</h3>
        <p>{{ pub.authors }}</p>
        <p>{{ pub.conference }} <a href="{{ pub.link }}" class="btn">Read More</a></p>
      </div>
    </div>
  </li>
  {% endfor %}
</ul>
