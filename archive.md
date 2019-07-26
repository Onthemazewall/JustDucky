---
title: Strips
permalink: /archive/
---
<h2>Archive</h2>
<ul>
{% for post in site.posts %}
<li><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></li>
{% endfor%}
</ul>
