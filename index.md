---
layout: page
title: music for the moving image
---

![](/assets/img/tedor_k_hofstadter_music.jpg)

Exploring   
the relationship   
between music and the moving image,   
sound and vision.

<br>

<!--
## Blog

-->

<ul class="myposts">
{% for post in site.categories.blog %}
    <li>{{ post.date | date: "%F" }} | <a href="{{ post.url }}">{{ post.title}}</a>
    <br>
    </li>
      <hr>
{% endfor %}
</ul>

module leader: [khofstadter](https://khofstadter.info)
