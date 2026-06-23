---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

  <div style="display: flex; align-items: center; gap: 1rem;">
    <a
      href="https://scholar.google.com/citations?user=oqUyCzEAAAAJ&hl=en"
      target="_blank"
      rel="noopener noreferrer"
      title="Google Scholar Profile"
    >
      <img
        src="https://upload.wikimedia.org/wikipedia/commons/c/c7/Google_Scholar_logo.svg"
        alt="Google Scholar"
        style="height: 32px; width: 32px;"
      />
    </a>
  </div>

  {% bibliography %}

</div>
