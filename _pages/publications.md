---
layout: page
permalink: /publications/
title: Publications
description: 
sections:
  - bibquery: "@article"
    text: "Journal articles"
  - bibquery: "@inproceedings"
    text: "Conference abstracts"
  - bibquery: "@phdthesis"
    text: "Thesis"
years: [2023, 2022, 2021, 2020, 2019, 2018]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->

<!-- https://github.com/alshedivat/al-folio/issues/1264 -->
<div class="publications">

{%- for section in page.sections %}
  <a id="{{section.text}}"></a>
  <p class="bibtitle">{{section.text}}</p>
  {%- for y in page.years %}

    {%- comment -%}  Count bibliography in actual section and year {%- endcomment -%}
    {%- capture citecount -%}
    {%- bibliography_count -f {{site.scholar.bibliography}} -q {{section.bibquery}}[year={{y}}] -%}
    {%- endcapture -%}

    {%- comment -%} If exist bibliography in actual section and year, print {%- endcomment -%}
    {%- if citecount !="0" %}

      <h2 class="year">{{y}}</h2>
      {% bibliography -f {{site.scholar.bibliography}} -q {{section.bibquery}}[year={{y}}] %}

    {%- endif -%}

  {%- endfor %}

{%- endfor %}

</div>