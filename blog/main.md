---
layout: page
title: Blog
---

### Contents

<p>Here are my blog posts in reverse chronological order:</p>

<ul>
  {% for post in site.categories.posts %}
    <li class="spaced">
      <a href="{{ post.url }}">{{ post.title }}</a> {{ post.date | date_to_long_string }}
    </li>
  {% endfor %}
</ul>
