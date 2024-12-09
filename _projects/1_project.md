---
layout: page
title: Analysis of Optical Coherence Tomography Scans
description: Retinal OCT Image Analysis
img: assets/img/CNN_uNET2.png
video: assets/video/
importance: 1
category: work
related_publications: true
giscus_comments: true
---

Optical Coherence Tomography (OCT) is a non-invasive imaging technique that provides high-resolution cross-sectional images of the retina. It uses low-coherence light to measure the echo time delay of light reflected from different retinal layers, creating detailed images crucial for diagnosing and managing various eye conditions. OCT is widely used to assess retinal structures, enabling early detection and monitoring of eye diseases such as:
Age-Related Macular Degeneration (AMD),
Diabetic Retinopathy (DR),
Glaucoma,
Macular Edema, and Retinal Detachments.

In this project, we have developed several methods for Retinal OCT Layer Segmentation, Retinal Fluid Segmentation, Retinal OCT scans Enancement through denoising, and Retinal OCT Image Synthesis.


    ---
 <div class="caption">
 OCT Image Acquisition.
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/Video_OCT.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
    
</div>
    ---
    <div class="caption">
Depthwise Separable Convolutional Network for Retinal OCT Fluid Segmentation Architecture {% cite girish2019depthwise %} .
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/resxcep.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<!--
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
   </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
   </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
Depthwise Separable Convolutional Network for Retinal OCT Fluid Segmentation Architecture {% cite girish2019depthwise %} .
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/resxcep.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite girish2019depthwise %}.
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
-->
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
