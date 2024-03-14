---
layout: page
title: Home
id: home
permalink: /
---

# Hi! 🌱


My name is Zakaria. A lot of people call me Zak. I prefer the former though.

I enjoy building small apps that make my life a little easier.

I also like to build theoritical models about the world and validate them. 

I enjoy skiing, kite-surfing and anything water-related. 

Welcome to my little part of the world!


<strong>Recently updated notes</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
