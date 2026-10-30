---
layout: page
permalink: /publications/
title: Publications
description: 14 research works (10 as first or co-first author) published at CVPR, ICCV, ECCV, NeurIPS, ICML, and AAAI. An asterisk (*) denotes equal contribution.
nav: true
nav_order: 2
toc:
  sidebar: left
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2>First / Co-first Author</h2>

{% bibliography -q @*[first_author=true] %}

<h2 class="collaborations">Collaborations</h2>

{% bibliography -q @*[first_author=false] %}

</div>
