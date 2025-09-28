---
layout: page
title: Thoughts
permalink: /thoughts/
---

# Thoughts

To record some thinking and idea here.

<ul>
{% assign items = site.thoughts | sort: 'date' | reverse %}
{% for t in items %}
  <li>
    <a href="{{ t.url | relative_url }}">{{ t.title }}</a>
    <small> — {{ t.date | date: "%Y-%m-%d" }}</small>
  </li>
{% endfor %}
</ul>
