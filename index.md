---
layout: home
title: Home
---

# Welcome to Budget Finds

Discover great deals on AliExpress with honest reviews, comparisons, and affiliate links. Shop smart, save money, and support the site!

## Latest Posts
{% for post in site.posts limit: 5 %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

[View all posts](/posts)

[Shop Deals](/shop)
