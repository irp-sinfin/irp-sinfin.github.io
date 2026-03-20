---
layout: page
title: "Archive"
permalink: /archive/
---

Below is the complete list of news, visits, and events related to the SINFIN (and formerly INFINIS) project.

{% assign postsByYear = site.posts | group_by_exp: "post", "post.date | date: '%Y'" %}
{% for year in postsByYear %}
  <h2 style="border-bottom: 2px solid #2a7ae2; padding-top: 20px;">{{ year.name }}</h2>
  <ul style="list-style-type: none; padding-left: 0;">
    {% for post in year.items %}
      <li style="margin-bottom: 8px;">
        <span style="color: #666; font-family: monospace; margin-right: 15px;">{{ post.date | date: "%b %d" }}</span>
        <a href="{{ post.url | relative_url }}" style="font-weight: 500;">{{ post.title }}</a>
      </li>
    {% endfor %}
  </ul>
{% endfor %}
