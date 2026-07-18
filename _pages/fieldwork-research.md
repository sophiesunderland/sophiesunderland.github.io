---
layout: archive
title: "Fieldwork & Research Geography"
permalink: /fieldwork-research/
author_profile: true
---
<div class="photo-grid">

  <figure>
    <img src="{{ '/images/IMG_4774.jpg' | relative_url }}">
    <figcaption>Luangwa, Zambia</figcaption>
  </figure>

  <figure>
    <img src="{{ '/images/IMG_4541.jpg' | relative_url }}">
    <figcaption>Mosi-oa-Tunya National Park</figcaption>
  </figure>

  <figure>
    <img src="{{ '/images/IMG_4405.jpg' | relative_url }}">
    <figcaption>Kamwala market, Zambia</figcaption>
  </figure>

  <figure>
    <img src="{{ '/images/IMG_1298.jpg' | relative_url }}">
    <figcaption>Kalandula Falls, Angola</figcaption>
  </figure>

</div>

<style>
.photo-grid {
  display:grid;
  grid-template-columns:repeat(2, 1fr);
  gap:30px;
}

.photo-grid figure {
  background:white;
  padding:12px;
  padding-bottom:20px;
  box-shadow:0 4px 12px rgba(0,0,0,.15);
  transform:rotate(-1deg);
}

.photo-grid figure:nth-child(even) {
  transform:rotate(1deg);
}

.photo-grid img {
  width:100%;
  aspect-ratio:1/1;
  object-fit:cover;
}

.photo-grid figcaption {
  text-align:center;
  margin-top:10px;
  font-style:italic;
  color:#666;
}

@media (max-width: 700px) {
  .photo-grid {
    grid-template-columns:1fr;
  }
}
</style>
