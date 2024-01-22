---
layout: page
title: balancing stick
img: assets/img/balancing_stick/balancing-3.jpeg
importance: 1
category: fun
related_publications: false
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/balancing_stick/Stick-Assembly-v2.jpeg" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/balancing_stick/stick-electronics.jpeg" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/balancing_stick/stick.jpeg" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/wao/wao-swing.jpeg" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<iframe width="560" height="315" src="https://www.youtube.com/embed/Hc7ZZhGV2LI?si=3SpHcmnqTovhyAJe" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

2-DOF reaction wheel stick. Assumed axes had no coupling and designed a LQR controller. Key to stability was an integrator on flywheel velocity to drive it to zero at steady state.
