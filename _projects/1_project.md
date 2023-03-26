---
layout: page
title: Thermal management of electronics
description: COMSOL simulations of heat conduction
img: assets/img/12.jpg
importance: 1
category: work
---

Thermal management is the current bottleneck in the advancement of high-power integrated circuits (ICs), and phase change heat sinks are a promising  solution. With a unique structural configuration consisting of a  membrane positioned above the heater surface, membrane-based heat sinks (MHS) have thus far attained  heat fluxes of up to 2 kW/cm2 and HTC of up to 1.8 MW/m2K using water as the working fluid. This work reports the latest progress and performance evaluation of MHS for high flux thermal management.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal it's glory in the next row of images.


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">`.
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
