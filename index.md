---
layout: home
title: 首页
---

# 欢迎来到我的技术博客！

这里是记录算法学习、编程技巧和题解的地方。

## 最新题解

<ul>
{% for post in site.categories.题解 limit:5 %}
  <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

[查看更多题解 →](/solutions/)
