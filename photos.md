---
layout: homepage
---
[Back](index.md).

## Miscellaneous 🌟
- I was born and raised in Guangzhou🏙️, but I have a particular fondness for Hunan and Sichuan cuisine🌶️🌶️🌶️.
- I enjoy playing the koto and guitar🎸, and I also enjoy drawing comics🎨.
- I love Black Tea Espresso Fusion☕.


## Gallery 🌴

Sunset-collector :)

<div class="gallery-container">
  <div class="gallery-item">
    <img src="../assets/img/alaska1.jpg" alt="Gallery 1">
  </div>
  <div class="gallery-item">
    <img src="../assets/img/alaska2.jpg" alt="Gallery 2">
  </div>
  <div class="gallery-item">
    <img src="../assets/img/barbara.jpg" alt="Gallery 3">
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

<div class="gallery-container">
  <div class="gallery-item">
    <img src="../assets/img/tahoe1.jpg" alt="Gallery 1">
  </div>
  <div class="gallery-item">
    <img src="../assets/img/tahoe2.jpg" alt="Gallery 2">
  </div>
  <div class="gallery-text">
    **Tahoe Lake** - 10/2023
  </div>
</div>

<style>
  .gallery-container {
    display: flex;
    justify-content: center; /* Center align the items */
    margin-top: 20px;
  }

  .gallery-item {
    flex-basis: auto; /* Adjust basis to auto */
    margin: 0 10px; /* Adjust the margin between items */
    text-align: center; /* Center align the text */
  }

  .gallery-item img {
    max-width: 100%;
    width: 200px; /* Set the desired width */
    height: auto; /* Maintain aspect ratio */
  }

  .gallery-item figcaption {
    margin-top: 10px; /* Space between the image and the text */
    font-size: 14px; /* Adjust font size as needed */
    color: #333; /* Text color */
  }
</style>




<div class="gallery-container">
  <div class="gallery-item">
    <img src="../assets/img/alaska1.jpg" alt="Gallery 1" id="galleryImage">
    <div class="image-overlay" onclick="nextImage()">Click to Change</div>
  </div>
</div>

<style>
  .gallery-container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 80vh; /* 适当调整高度 */
  }

  .gallery-item {
    position: relative;
  }

  .gallery-item img {
    max-width: 100%;
    height: auto;
  }

  .image-overlay {
    position: absolute;
    bottom: 10px;
    left: 50%;
    transform: translateX(-50%);
    background-color: rgba(255, 255, 255, 0.5);
    padding: 8px 16px;
    cursor: pointer;
  }
</style>



