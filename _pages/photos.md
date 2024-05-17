---
layout: homepage
---

## Life Photos

Here are some of my favorite life moments captured in photos.

<div class="gallery-container">
  <div class="gallery-item">
    <img src="../assets/img/life1.jpg" alt="Life Photo 1">
  </div>
  <div class="gallery-item">
    <img src="../assets/img/life2.jpg" alt="Life Photo 2">
  </div>
  <div class="gallery-item">
    <img src="../assets/img/life3.jpg" alt="Life Photo 3">
  </div>
</div>

<style>
  .gallery-container {
    display: flex;
    justify-content: space-between;
    margin-top: 20px;
  }

  .gallery-item {
    flex-basis: calc(33.33% - 10px);
  }

  .gallery-item img {
    max-width: 100%;
    height: auto;
  }
</style>
