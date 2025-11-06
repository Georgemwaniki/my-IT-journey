---
layout: default
title: "Welcome to My IT Journey"
---

Hi, I’m George Mwaniki. I’m documenting my journey from certified to skilled—building hands-on IT experience in networking, cloud, and cybersecurity.

## Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
