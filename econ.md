---
layout: default
title: Learning Economics
---

# Learning Economics

I have often found that economics education is not taught in a computer accessible way that allows students to explore the mathematics that lie under the hood. I have decided to try to put together some brief modules explaining various concepts and hopefully letting students modern economic models themselves!

## Basic Microeconomics
{% for item in site.data.pages.econ-pages %}
[{{item.name}}]({{item.link}})
{% endfor %}