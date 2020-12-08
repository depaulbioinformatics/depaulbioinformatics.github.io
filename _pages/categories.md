---
layout: categories
title: Categories
permalink: /categories
---

<!-- BAD -- calculating "all_keywords" twice on this page...
		- NEED way to compute all_keywords at run time and assign as layout front_matter variable in "default.html"
-->
{% include allkeywords.html %} <!-- defines 'all_keywords' var -->


<h3 class="font-weight-bold">Categories</h3>
<!-- Create Table of Contents (toc) -->
<div class="row text-center justify-content-center toc-background">

		{% for category in all_keywords %}
			<div class="col mt-2 mb-2"><a href="#{{ category | replace: " ","-" }}"><span class="category-label text-capitalize">{{ category }}</span></a></div>
		{% endfor %}

</div>

