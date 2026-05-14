---
layout: default
title: Blog
permalink: /blog/
---

<section class="blog-page">
  <!-- <header class="blog-header">
    <h1>Blog</h1>
    <p>Writing and reflections on technology, society, cybersecurity, and design.</p>
  </header> -->
  
<div class="blog-grid">
  {% for post in site.posts %}
    <article class="blog-card">
      {% if post.image %}
        <a href="{{ post.url | relative_url }}" class="blog-card-image">
          <img src="{{ post.image | relative_url }}" alt="{{ post.image_alt | default: post.title }}">
        </a>
      {% endif %}

        <div class="blog-card-body">
          <div class="blog-card-meta">
            <span>{{ post.date | date: "%B %-d, %Y" }}</span>
            <span>•</span>
            <span>3 min read</span>
          </div>

          <h2>
            <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
          </h2>

          {% if post.subtitle %}
            <p>{{ post.subtitle }}</p>
          {% else %}
            <p>{{ post.excerpt | strip_html | truncate: 150 }}</p>
          {% endif %}

          <a class="read-more" href="{{ post.url | relative_url }}">Read post →</a>
        </div>
      </article>
    {% endfor %}
  </div>
</section>