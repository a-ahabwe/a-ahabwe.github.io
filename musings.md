---
layout: default
title: Musings
permalink: /musings/
---

<div class="musings-list">
  <p><em>Just some fun experiments and thoughts.</em></p>
  
  <ul>
    {% for post in site.posts %}
      <li>
        <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> 
        <small>({{ post.date | date: "%B %Y" }})</small>
      </li>
    {% endfor %}
  </ul>
</div>
