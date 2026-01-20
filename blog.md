---
layout: default
title: Notes
---

<section class="hero">
  <p class="eyebrow">Personal Blog</p>
  <h1>Notes</h1>
  <p class="lead">Short-form thoughts, learning notes, and experiments.</p>
</section>

<section class="card">
  <h2>Latest Posts</h2>
  <ul>
    {% for post in site.posts %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        <span class="muted"> — {{ post.date | date: "%b %d, %Y" }}</span>
      </li>
    {% endfor %}
  </ul>
</section>
