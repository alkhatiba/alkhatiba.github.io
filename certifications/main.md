---
layout: page
title: Certifications
subtitle: My Certificates
---

### Contents

<p>Here are my certificates:</p>

<ul>
  {% for post in site.certificates %}
    <li class="spaced">
      <a href="{{ post.url }}">{{ post.title }}</a> {{ post.date | date_to_long_string }}
    </li>
  {% endfor %}
</ul>
