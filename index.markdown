---
layout: default
title: Home
---

## Hey, I'm Gino! 👋

I'm a **Software Developer** currently working at **Pixite Inc**, where I build scalable web applications using Ruby on Rails, Google Cloud Platform, Elasticsearch, and more.

With nearly a decade of software engineering experience, I'm passionate about creating elegant solutions, mentoring developers, and fostering inclusive tech communities. I'm the founder of **CoolCatsCoding**, a collective where we live by the "Each One, Teach One" philosophy.

When I'm not coding, you'll find me exploring new technologies, contributing to open source projects, and sharing knowledge with the developer community.

---

### 📝 Recent Blog Posts

{% if site.posts.size > 0 %}
<ul class="post-list">
  {% for post in site.posts limit:5 %}
    <li>
      <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
      <h3>
        <a class="post-link" href="{{ post.url | relative_url }}">
          {{ post.title | escape }}
        </a>
      </h3>
      {% if post.excerpt %}
        <p>{{ post.excerpt | strip_html | truncatewords: 30 }}</p>
      {% endif %}
    </li>
  {% endfor %}
</ul>
{% else %}
  <p>No posts yet. Stay tuned!</p>
{% endif %}

[View all posts →](/blog/)

---

### 💼 Work & Projects

- **[Experience](/experience/)** - My professional journey and roles
- **[Portfolio](/portfolio/)** - Featured projects and technical skills

---

### 🔗 Connect With Me

- **GitHub**: [@{{ site.github_username }}](https://github.com/{{ site.github_username }})
- **Email**: [Contact me](/about/)

---

<div style="text-align: center; margin-top: 2em; opacity: 0.7;">
  <small>Built with Jekyll & the Hacker theme</small>
</div>
