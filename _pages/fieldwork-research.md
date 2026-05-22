---
layout: archive
title: "Fieldwork & Research Geography"
permalink: /fieldwork-research/
author_profile: true
---
These are countries where I have conducted fieldwork (or visited for fun!)

<div id="africa-map"></div>

<link
  rel="stylesheet"
  href="https://unpkg.com/leaflet/dist/leaflet.css"
/>

<script src="https://unpkg.com/leaflet/dist/leaflet.js"></script>

<script>
var map = L.map('africa-map', {
    zoomControl: false,
    scrollWheelZoom: false
}).setView([-15, 24], 4);

L.tileLayer('https://{s}.basemaps.cartocdn.com/light_all/{z}/{x}/{y}{r}.png', {
    attribution: '&copy; OpenStreetMap contributors'
}).addTo(map);
</script>

<script>

L.circleMarker([-12.5, 18.5], {
    radius: 8,
    color: '#ff5c00',
    fillColor: '#ff5c00',
    fillOpacity: 0.8
}).addTo(map)
.bindPopup("<b>Angola</b>");

L.circleMarker([-22.3, 24.7], {
    radius: 8,
    color: '#ff5c00',
    fillColor: '#ff5c00',
    fillOpacity: 0.8
}).addTo(map)
.bindPopup("<b>Botswana</b>");

L.circleMarker([-30.5595, 22.9375], {
    radius: 8,
    color: '#ff5c00',
    fillColor: '#ff5c00',
    fillOpacity: 0.8
}).addTo(map)
.bindPopup("<b>South Africa</b>");

L.circleMarker([-13.1339, 27.8493], {
    radius: 8,
    color: '#ff5c00',
    fillColor: '#ff5c00',
    fillOpacity: 0.8
}).addTo(map)
.bindPopup("<b>Zambia</b>");

L.circleMarker([-19.0154, 29.1549], {
    radius: 8,
    color: '#ff5c00',
    fillColor: '#ff5c00',
    fillOpacity: 0.8
}).addTo(map)
.bindPopup("<b>Zimbabwe</b>");

</script>
