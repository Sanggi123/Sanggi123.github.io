---
title: "테스트 카테고리"
layout: archive
permalink: categories/test
author_profile: true
sidebar_main: true
---


{% assign posts = site.categories.test %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}