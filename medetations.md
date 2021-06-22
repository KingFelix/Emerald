---
layout: page
title: medetations
description: "This is where I house my personal thoughts on faith an spirituality. I hope it encourages you on your journey to complete life victory."
---
<!-- Posts -->
<link rel="canonical" href="{{ site.url }}{{site.baseurl}}{{ page.url }}" />

<ul id="posts">

	{% for post in paginator.medetations %}



	  <li class="post">
          <h4>
              {{medetations.tags}}
          </h4>

	  	<h2>

			<a href="{% if site.baseurl == "/" %}{{ medetation.url }}{% else %}{{ medetation.url | prepend: site.baseurl }}{% endif %}">{{ post.title }}</a>
		</h2>

	  	<time datetime="{{ post.date | date_to_xmlschema }}" class="by-line">{{ post.date | date_to_string }}</time>
	  	<p>{{ post.description }}</p>
	  </li>

    {% endfor %}

</ul>
