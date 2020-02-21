---
layout: page
title: CAD-Showcase
permalink: /blog/categories/CAD-Showcase
---
 
<h5> Posts by Category : {{ page.title }} </h5>

<div class="card">
{% for post in site.categories.CAD-Showcase %}
 <li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</div>