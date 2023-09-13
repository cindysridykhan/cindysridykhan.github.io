---
layout: page
title: NeRF training 
description: Here I trained a NeRF (Neural Radiance Fields) on a video taken with my smartphone.
img: assets/gif/500.gif
#redirect: https://unsplash.com
importance: 3
category: projects
---
<div class="row">
    <div class="col-sm mt-3 mt-md-0 text-center">
        {% include figure.html path="assets/gif/500.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Boston Common Park :)
</div>

NeRF (Neural Radiance Fields) is a technique that allows to synthesize 3D novel views of complex scenes using a set of 2D images. Under the hood, it is a fully-connected neural network, that takes as input 5 coordinates (spatial location (x, y, z) and viewing direction (θ, φ)) of a point viewed from a certain angle, and outputs the volume density and view-dependent emitted color at that point.
Here is the result I got from training a NeRF using nerfstudio on a video filmed with my good old smartphone.

Learn more about NeRF here: https://www.matthewtancik.com/nerf
< br>
Train your own with nerfstudio: https://docs.nerf.studio/en/latest/