---
layout: default
title: "Blog – Atchatha"
permalink: /blog/
---

# Blog

<p class="meta">Case studies, lessons learned, and behind-the-scenes notes. <br>
Each post shows a “Last Updated” so readers (and search engines) know it’s fresh.</p>

<ul>
  {% for post in site.posts %}
    <li style="margin:12px 0">
      <a href="{{ post.url | relative_url }}"><strong>{{ post.title }}</strong></a><br>
      <span class="meta">{{ post.date | date: "%b %d, %Y" }}</span> — {{ post.excerpt | strip_html | truncate: 160 }}
    </li>
  {% endfor %}
</ul>

{% if site.posts == empty %}
<p class="meta">No posts yet. First write-up coming soon.</p>
{% endif %}
