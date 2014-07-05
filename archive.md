---
layout: page
title: Archive
---

<table class="archive">
{% for post in site.posts %}
<tr><td class="archive-date">{{ post.date | date_to_string }}</td>
  <td><a href="{{ post.url }}">{{ post.title }}</a></td></tr>
{% endfor %}
</table>
