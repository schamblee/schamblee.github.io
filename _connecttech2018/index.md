---
layout: default
title: My collection of notes
permalink: :collection
---

All my notes

<ol>
  {% for item in site.connecttech2018 %}
    <li><a href="{{item.url}}">{{item.title}}</a></li>
  {% endfor %}
</ol>
