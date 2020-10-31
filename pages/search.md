---
permalink: /search/
layout: page
title: "Search for project"
sitemap: false
---

<!-- {% include _google_search.html %} -->
<!-- Html Elements for Search -->
<div id="search-container">
<input type="text" id="search-input" placeholder="search...">
<ul id="results-container"></ul>
</div>

<!-- Script pointing to search-script.js -->
<script src="/assets/js/simple-jekyll-search.min.js" type="text/javascript"></script>

<!-- Configuration -->
<script>
SimpleJekyllSearch({
  searchInput: document.getElementById('search-input'),
  resultsContainer: document.getElementById('results-container'),
  json: '/search.json',
  searchResultTemplate: '<a href="{url}"><div style="border: 1px solid; border-radius: 3px; padding: 3vw; margin: 2vh;"><p><h3>{title}</h3><p>{category}</p><p>{teaser}</p></div></a>'
})
</script>