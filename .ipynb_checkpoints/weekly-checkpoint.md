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

## How to add a new weekly post

1. Create a new file inside the `weekly/` folder.
2. Name it:

   project-post-week-X.md

3. Use this template:

```yaml
---
layout: page
title: "Project Post Week X"
week: X
---
