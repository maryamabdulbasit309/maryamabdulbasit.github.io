---
layout: default
title: Blog
---

# 📝 My Blog

{% raw %}
{% for post in site.posts %}
## 👉 [{{ post.title }}]({{ post.url }})
📅 {{ post.date | date: "%B %d, %Y" }}

{% endfor %}
{% endraw %}
