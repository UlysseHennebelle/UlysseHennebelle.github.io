---
layout: page
permalink: /publications/
title: Publications
description: Work in progress and published papers.
nav: true
nav_order: 1
---

<style>
  .publications ol.bibliography li .author > em {
    border-bottom: 0;
  }
</style>

<div class="publications">

<h2>Work in Progress</h2>

{% bibliography --group_by none --query @*[status=work_in_progress] %}

<h2>Published</h2>

{% bibliography --group_by none --query @*[status=published] %}

</div>
