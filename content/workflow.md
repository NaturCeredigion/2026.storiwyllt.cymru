---
date: 2026-03-25T20:22:17+00:00
modified: 2026-03-25T20:22:17+00:00
draft: false
image: https://res.cloudinary.com/naturceredigion/image/upload/v1774433498/260320-lletau-llyffant-root-moss-stone-twr-gwyllt-169.jpg
title: Image workflow
---

1. Take photos, make notes
2. Choose, edit, crop & upload to Signal group
3. Download files to PC
4. Rename with timestamp & description eg 250320-aberaeron-workshop1-toad.jpg
5. Upload to Cloudinary `Stori Wyllt 2026` folder
6. Copy URL:
7. Paste into `image` frontmatter property
8. Or paste inline into body of document:  `![AltText](URL)` 
   Which looks like this:
```
![Toad home pile of stones and wood and moss](https://res.cloudinary.com/naturceredigion/image/upload/v1774433498/260320-lletau-llyffant-root-moss-stone-twr-gwyllt-169.jpg)
```

### Straight image
![Toad home pile of stones and wood and moss](https://res.cloudinary.com/naturceredigion/image/upload/v1774433498/260320-lletau-llyffant-root-moss-stone-twr-gwyllt-169.jpg)

### Figure image
{{< figure src="https://res.cloudinary.com/naturceredigion/image/upload/v1774433496/260320-becca-toad-twr-gwyllt-169.jpg" >}}

### Gallery
<div class="gallery-box">
  <div class="gallery">
    <img src="https://res.cloudinary.com/naturceredigion/image/upload/v1774433498/260320-lletau-llyffant-root-moss-stone-twr-gwyllt-169.jpg" alt="" loading="lazy">
    <img src="https://res.cloudinary.com/naturceredigion/image/upload/v1774433498/260320-lletau-llyffant-trees-twr-gwyllt-169.jpg" alt="" loading="lazy">
    <img src="https://res.cloudinary.com/naturceredigion/image/upload/v1774433496/260320-becca-toad-twr-gwyllt-169.jpg" alt="" loading="lazy">
    <img src="https://res.cloudinary.com/naturceredigion/image/upload/v1774433496/260320-lletau-llyffant-closeup-twr-gwyllt-169.jpg" alt="" loading="lazy">
    <img src="https://res.cloudinary.com/naturceredigion/image/upload/v1774433495/260320-lletau-llyffant-both-sides-gabion-twr-gwyllt-169.jpg" alt="" loading="lazy">
  </div>
</div>

### Gallery with `figure` & `figcaption`
<div class="gallery-box">
  <div class="gallery">
    <figure>
      <img src="https://res.cloudinary.com/naturceredigion/image/upload/v1774433498/260320-lletau-llyffant-root-moss-stone-twr-gwyllt-169.jpg" alt="" loading="lazy">
      <figcaption>Rocks</figcaption>
    </figure>
    <figure>
      <img src="https://res.cloudinary.com/naturceredigion/image/upload/v1774433498/260320-lletau-llyffant-trees-twr-gwyllt-169.jpg" alt="" loading="lazy">
      <figcaption>Both sides</figcaption>
    </figure>
    <figure>
      <img src="https://res.cloudinary.com/naturceredigion/image/upload/v1774433496/260320-becca-toad-twr-gwyllt-169.jpg" alt="" loading="lazy">
      <figcaption>Toad</figcaption>
    </figure>
    <figure>
      <img src="https://res.cloudinary.com/naturceredigion/image/upload/v1774433496/260320-lletau-llyffant-closeup-twr-gwyllt-169.jpg" alt="" loading="lazy">
      <figcaption>HOles</figcaption>
    </figure>
    <figure>
      <img src="https://res.cloudinary.com/naturceredigion/image/upload/v1774433495/260320-lletau-llyffant-both-sides-gabion-twr-gwyllt-169.jpg" alt="" loading="lazy">
      <figcaption>Resplendent</figcaption>
    </figure>
  </div>
</div>


