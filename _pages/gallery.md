---
layout: single
title: Gallery
permalink: /gallery/
gallery:
  - url: /assets/img/gallery/drawing/
  image_path: /assets/img/gallery/drawing/*.jpg
gallery2:
  - url: /assets/img/gallery/drawing/artbook/
    image_path: /assets/img/gallery/artbook/*.jpg
---
<h3> Drawings
{% include gallery %}

<h3> Artbooks
{% include gallery id="gallery2"%}
