---
layout: default
title: Portfolio
---
 
<section class="content">
  <h2>Portfolio</h2>
 
  <p>Dyatlov pass incident pictures</p>
</section>
 
 <img src="http://gomoodboard.imgix.net/production%2F1462555470841-k7716h6irbthdkgg-ccd510b1546bd0931d142aa782286fb7?ixlib=rb-0.3.5&q=90&fm=jpg">
 <img src="http://gomoodboard.imgix.net/production%2F1462555470833-aqfz5h8d88i8fzge-ccd510b1546bd0931d142aa782286fb7?ixlib=rb-0.3.5&q=90&fm=jpg">
 <img src="http://gomoodboard.imgix.net/production%2F1462554780468-7c1cecj73ts51dpt-ccd510b1546bd0931d142aa782286fb7?ixlib=rb-0.3.5&q=90&fm=jpg">
<ul class="entries">
  {% for post in site.posts %}
 
  <li>
    <a href="{{ post.url }}">
      <img src="{{ post.image }}" />
      <h3>{{ post.title }}</h3>
    </a>
  </li>
 
  {% endfor %}
</ul>
