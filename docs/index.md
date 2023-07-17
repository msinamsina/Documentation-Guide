---
title: Home
layout: home
nav_order: 1
food: Pizza
---

<h1>{{ page.food }}</h1>

This is a test
{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
{% endfor %}
