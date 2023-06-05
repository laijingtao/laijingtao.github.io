---
layout: page
title: Glacial erosion
description: Modeling tectonic and climatic controls on glacial erosion
img: assets/img/publication_preview/Lai_2021_ESurf.jpg
importance: 1
category: Research
project_tag: glacial_erosion
---

### Mountain-scale glacial erosion modeling

Glacial erosion has shaped many mountain ranges during the Late Cenozoic
glaciation. To understand the controls of tectonics and climate on glacial
erosion, I’ve developed a numerical landscape evolution model that I couple with
a thermomechanically coupled ice sheet model (PISM) to examine the sensitivities
of glacier dynamics and glacial erosion to various tectonic and climatic
conditions.

Using this model, I investigate the response of glacial erosion to increased
geothermal heat flow. The model reveals a tendency for increased glacial erosion
with increasing geothermal heat flow, suggesting a novel interaction between
tectonics and glacial erosion: tectonics may accelerate glacial erosion by
elevating geothermal heat (Lai and Anders, 2020, _EPSL_).

I also investigate the impact of climate on the patterns and rates of glacial
erosion. This research suggests that climate controls glacial erosion primarily
through the basal thermal regime and glacial erosion tends to be maximized at
the transition between cold-based and warm-based ice (Lai and Anders, 2021,
_ESurf_ ). This finding challenges the traditional view that glacial erosion is
greatest at the intersection between bedrock topography and the equilibrium line
altitudes of glaciers.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/publication_preview/Lai_2021_ESurf.jpg" title="preview" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### Asymmetric glaciation and drainage reorganization

Glacial erosion can move drainage divides and induce fluvial adjustments
downstream, yet the timescale over which these adjustments occur remains
unclear. We examine landscape evolution in the northwest-southeast trending
Qilian Shan, where the contrast in solar insolation between north- and
south-facing slopes has generated larger glaciers on the northern range crest.

Our analyses suggest that this asymmetric glaciation has caused southward
migration of the main drainage divide, prompting river channels below the
extents of ice on north-facing slopes to become oversteepened for their drainage
area and channels on south-facing slopes to become analogously understeepened.

These changes in steepness should accelerate or slow down postglacial fluvial
incision, even in these regions where topography has not been directly modified
by glacial erosion. Numerical modeling suggests these discrepancies persist for
millions of years – much longer than the duration of recent glacial-interglacial
cycles – implying a widespread and enduring influence of intermittent
glaciations on landscape evolution in glaciated mountain ranges during the
Quaternary.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/publication_preview/Lai_2023_Geology.png" title="preview" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### Related publications:
<div class="publications">

    {% bibliography -f {{site.scholar.bibliography}} -q @*[project ^= *{{page.project_tag}}*]* %}

</div>

