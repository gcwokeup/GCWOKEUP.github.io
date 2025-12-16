---
layout: default
title: Blog
permalink: /blog/
---

# Blog Posts

All my thoughts on software engineering, technology, and continuous learning.

---

{% if site.posts.size > 0 %}
  {% for post in site.posts %}
  <article class="post-entry">
    <h2>
      <a href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
    </h2>
    <p class="post-meta">
      <time datetime="{{ post.date | date_to_xmlschema }}">
        {{ post.date | date: "%B %-d, %Y" }}
      </time>
      {% if post.categories.size > 0 %}
        • {{ post.categories | join: ", " }}
      {% endif %}
    </p>
    {% if post.excerpt %}
      <div class="post-excerpt">
        {{ post.excerpt }}
      </div>
    {% endif %}
    <p><a href="{{ post.url | relative_url }}">Read more →</a></p>
    <hr>
  </article>
  {% endfor %}
{% else %}
  <p>No posts yet. Check back soon!</p>
{% endif %}

[← Back to Home](/)

