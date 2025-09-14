---
layout: page
title: MItigation STrategies for Airborne Infection Control 
description: WP3 - Ventilation, development of ventilation concepts, air sanitization, CFD
img: assets/img/MIST.png
importance: 1
category: work
related_publications: true
---

Work Package 3 (WP3) is dedicated to a rigorous analysis of how ventilation and air cleaning can limit the airborne transmission of infectious diseases, building upon the experimental and numerical data from WP2.

**Concept Assessment:**
Sub-projects WP3.1 and WP3.2 will evaluate advanced ventilation and air purification technologies. The primary aim is to maximize the reduction of both long- and short-range transmission while maintaining crucial factors like thermal comfort and energy efficiency. WP3.1 will concentrate on room-wide systems, while WP3.2 will examine localized solutions, with both efforts utilizing validated computational fluid dynamics (CFD) and physical experiments.

**Advanced Transmission Modeling:**
Sub-project WP3.3 will advance the state-of-the-art by incorporating time-dependent scenarios into transmission models. Using Lagrangian simulations, it will analyze how ventilation impacts exposure from the perspective of both the infected source and susceptible individuals, a dynamic often excluded from current models.

**Practical Application:**
The results from WP3 will provide critical input for WP4 (Use Cases) to ensure practical implementation and for WP5 (Strategies for Infection Control) to develop comprehensive strategies and guidelines against the spread of airborne respiratory diseases.

```html
 <div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Twan.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Marcel.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/prof_pic.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, Dr. Twan van Hooff. Middle, Dr. Marcel Loomans. Right, Dr. Peng Qin.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
