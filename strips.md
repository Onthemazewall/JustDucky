---
title: Strips
permalink: /strips/
---
<h2>Strips</h2>
<ul>
{% for post in site.posts %}
<li><a href="{{ site.posts.first.url | prepend: site.baseurl }}">{{ site.posts.first.title }}</a></li>
{% endfor%}
</ul>
