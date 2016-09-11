---
layout: default
title: home
---
<div class="blurb">
	<h1>¡hola mundo!</h1>
    <p>I'm a newbie web developer learning by trial and error while blogging along the way.</p>
</div><!-- /.blurb -->

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>