---
layout: page
title: Certifications
---

### Contents

<p>Here are my certificates:</p>

<ul>
  {% for post in site.certifications.posts %}
    <li class="spaced">
      <a href="{{ post.url }}">{{ post.title }}</a> 
    </li>
  {% endfor %}
</ul>
