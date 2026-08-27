---
layout: page
permalink: /publications/
title: publications
description: Published work, papers under review, and manuscripts in preparation.
nav: true
nav_order: 3
---

{% include bib_search.liquid %}

## Under review / submitted

<div class="publications">
{% bibliography --query @unpublished %}
</div>

## In preparation

<div class="publications">
{% bibliography --query @misc %}
</div>

## Published

<div class="publications">
{% bibliography --query @article @phdthesis @mastersthesis @inproceedings @incollection %}
</div>
