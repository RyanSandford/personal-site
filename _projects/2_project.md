---
layout: page
title: Lean 3 Homotopy Type Theory Library Contribution
description: Contributed formalized proofs regarding the notion of the 2-adjoint equivalence to the open source Homotopy Type Theory Library in Lean 3
img: /assets/img/HOTT_thumbnail.png
importance: 2
category: work
---

Homotopy Type Theory (HoTT) is an intuitionistic type theory which views types
as abstract, homotopy-invariant objects. As remarked in the HoTT book,
this correspondence is quite remarkable as it provides a link between
homotopy theory (which is related to algebraic topology, homological algebra, and higher category theory)
and type theory, a field of mathematical logic and theoretical computer science.
HoTT provides a type-theoretic foundation to
mathematics rather then the conventional set theoretic foundation.
This in turn, allows for proofs within HoTT to be formalized and
understood by a computer via a proof assistant.

During the summer of 2019, myself, Daniel Carranza, and Jonathan Chang, under the supervision of
Chris Kapulkin, began exploring the notion of 2-adjoint equivalences and coherences between types.
This resulted in the construction, proof, and formalization of many properties one would expect
from a 2-adjoint equivalence. The following summer the remaining properties were formalized by Daniel
Carranza. The final, formalized proofs were added to the Lean 3, HoTT library and can be found in
the 2adj directory. Moreover, a paper describing the 2-adjoint equivalence, and its formalization was
published to the journal of logical methods in computer science which can be found at:.
Additional links are provided in the publication section of this site.



    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/1.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/3.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/5.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/5.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal it's glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/6.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/11.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/6.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/11.jpg' | relative_url }}" alt="" title="example image"/>
    </div>
</div>
```
