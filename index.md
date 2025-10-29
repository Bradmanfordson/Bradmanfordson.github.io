---
layout: default
title: Home
---

<div class="posts">
  {% for post in site.posts %}
    {% include post_card.html %}
  {% endfor %}
</div>
