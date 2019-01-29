---
layout: Archive
title:  Blog
permalink: /blog/
---
<div class="tiles">
{% for post in site.categories.foo %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
