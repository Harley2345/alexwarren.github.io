---
layout: index
title: Talks
---

# Talks

<ul>
{% for post in site.talks reversed %}
<li>
<a href="{{ post.url }}">{{ post.title }}</a>
<span class="date">
{{ post.date | date: "%-d %B %Y" }}
at {{ post.location }}
</span>
</li>
{% endfor %}
</ul>