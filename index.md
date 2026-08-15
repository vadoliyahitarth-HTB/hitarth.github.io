---
layout: default
title: Cybersecurity Journey
---

<link rel="stylesheet" href="{{ '/assets/css/style.css' | relative_url }}">

# 🏴‍☠️ Hitarth's Cybersecurity Journey

**Cybersecurity Student • Learner • Builder**

Learning cybersecurity by studying, practicing, breaking things,
and building projects.

## 🔥 Currently Learning

- 🌐 Networking
- 🐧 Linux
- 🛡️ Web Security
- 🔎 Reconnaissance
- 🐛 Bug Bounty

## 🔥 Latest Writeups

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url | relative_url }})

{{ post.excerpt }}

{% endfor %}

## 🚀 Goal

Build real skills through hands-on labs, writeups and projects.
