---
title: "Home"
---

# Welcome

This is my knowledge base.  
Navigate using the links below.

- [Getting Started](docs/getting-started.md)
- [DevOps Notes](docs/devops.md)

---

{% for post in site.posts %}
  {% if post.tags contains "system prompt" %}
    <a href="{{ post.url }}">{{ post.title }}</a>
  {% endif %}
{% endfor %}

---
