---
layout: page
title: Weekly Posts
---

Below are my weekly project updates (newest first).

{% assign sorted = site.weekly | sort: "week" | reverse %}

{% for post in sorted %}
- **Week {{ post.week }}** — [{{ post.title }}]({{ post.url }})
{% endfor %}

---
