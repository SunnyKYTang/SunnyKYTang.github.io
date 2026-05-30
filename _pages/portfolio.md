---
title: "Portfolio"
permalink: /portfolio/
layout: single
---

# Projects

{% raw %}
{% for project in site.portfolio %}
- [{{ project.title }}]({{ project.url }})
{% endfor %}
{% endraw %}