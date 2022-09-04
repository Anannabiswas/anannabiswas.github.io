---
layout: default
title: "Projects"
---


Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: defult
    title: project
    description: a project with a background image
    img: /assets/img/ananna_1.jpeg
    ---

<div class="row gx-5 mb-5">
   <h3 class="fw-bold">Project: Deepmice</h3>
        <h5> Activity in V1 predicts spontaneous running behaviour in the absence of visual stimuli in mice </h5>
    <div class="col-sm mt-3 mt-md-0">
       <img src="{{ site.github.url }}/assets/img/ananna_1.jpeg" width="250" height="310" class="img-fluid rounded z-depth-1">
     
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img src="{{ site.github.url }}/assets/img/ananna_1.jpeg" width="250" height="310" class="img-fluid rounded z-depth-1"> 
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img src="{{ site.github.url }}/assets/img/ananna_1.jpeg" width="250" height="310" class="img-fluid rounded z-depth-1">
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
