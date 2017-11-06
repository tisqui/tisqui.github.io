---
layout: page
title: About this blog
permalink: /about/
---

My name is Galina. I live in Bay Area, California. My hobby is travelling around the state and discovering ghost towns. I am sharing my photos and some history I found online about the each one. Hope this will encourage someone to have a trip and document the dissapearing mining towns in their current state.

![Sierra][sierra] 

<h2 align="right">The Desert
	<br>
    –roseate metallic blue
    <br>
    & insect green
	<br>
    blank mirrors &
    <br>
    pools of silver
    <br>
    a universe in
    <br>
    one body</h2>

<h4 align="right">Jim Morrison</h4>

[sierra]: {{site.url}}/assets/img/about.jpg "Mono Lake pano"

<br>

{% for post in paginator.posts %}
  <h4><a href="{{ post.url }}">{{ post.title }}</a></h4>
{% endfor %}

