---
layout: page
title: Microtextures for cavitation control
description: Laser-ablated microstructures repel cavitation, aiding erosion control and enhancing microfluidic mixing.
img: assets/img/GEM_microstructures_SEM2.png
importance: 1
category: research
related_publications: false
---

This study explores the impact of gas-entrapping microstructures made of polydimethylsiloxane (PDMS) on cavitation bubble dynamics. The microstructures are created through a scalable laser ablation technique and demonstrated the ability to repel cavitation bubbles by causing entrapped air pockets to expand and oscillate. This research suggests the potential for directing cavitation bubble collapse away from surfaces to reduce erosion or improve microfluidic mixing in low Reynolds number flows.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/microstructure_fab" title="Laser texturing" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/GEM_microstructures_SEM2.png" title="SEM micrograph" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/CA_sensileDrop.png" title="Contact angle" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left) Fabrication of laser-textured structures. Middle) SEM Micrograph of acrylic mold and PDMS cast. Right) Contact angle of sensile water droplet on untreated PDMS and microstructured surface.
</div>

Several experiments were conducted over three stand-off distances to quantify the degree of repulsion and stability of the surfaces. In all cases near the untreated surface, the bubble collapses towards the boundary, producing a radially expanding toroidal impact on the surface. In contrast, the microstructured surfaces tend to repel the cavitation bubble while there are sufficient in-tact entrapped air pockets.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid
           path="assets/video/GEMS_Supplemental_v1.mp4"
           title="Bubble dynamics"
           class="embed-responsive"
           controls="true" %}
    </div>
</div>

<div class="caption">
Comparison of cavitation dynamics near an untreated, smooth PDMS surface and a representative microstructured surface for three standoff distances.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid
           path="assets/video/GEMS_Supplemental_v1.mp4"
           title="Bubble dynamics"
           class="embed-responsive"
           controls="true" %}
    </div>
</div>

<div class="caption">
Visualization of particle tracking of surrounding flows due to a series of 10 cavitation bubble collapses near an untreated, smooth PDMS surface and a representative microstructured surface. 
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
```

{% endraw %}
