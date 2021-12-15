---
layout: page
title: coba
comments: false
image: 
imageshadow: true
permalink: /coba 
--- 




<div class="isichapter">
{% for post in site.posts %}
{% if post.category == "Magic Emperor" %}
<ul>
<li><time class="tanggal">{{ post.date | date: "%b %d, %Y" }}</time> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
</ul>
{% endif %}
{% endfor %}
</div>
