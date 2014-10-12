---
layout: leanpage
title: About
---

This is the bio. Consider increasing the font or change class.



<div id="recent-container">
	<div id="recent-posts">
		<h1 class="recent-posts-header">Recent Posts</h1>
		<ul class="archive">
		{% for post in site.posts limit:3 %}
			<li>
	          <a href="{{ post.url }}">
	            {{ post.title }}
	          </a>
		    </li>
		{% endfor %}
		</ul>
	</div>

	<div id="recent-projects">
		<h1 class="recent-posts-header">Current Projects</h1>
		Working on sensor development, fresh-water aquarium, automated curtains...
	</div>
</div>
