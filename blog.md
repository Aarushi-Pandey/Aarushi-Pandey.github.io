---
layout: blog
title: Blog
---

<section class="section">
  <div class="section__title">Blog</div>
  <h1>Blog</h1>
  <h2>Blog</h2>
  <div class="section__content">

  {% for post in site.posts %}
    <h3>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </h3>
    <p class="section__content__text">
      {{ post.excerpt }}
    </p>
  {% endfor %}

  </div>
</section>
