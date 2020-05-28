## Visualize the world in 3D

<img src="../images/globe_2.png" class="plain" style="height: 300px"/>
<p style="font-size: 75%"><br/>
  Raluca Nicola - Product Engineer ArcGIS API for JavaScript
</p>
<p><br/><small>
International Master of Cartography - May 28, 2020
</small></p>

---

### About me
  <div>
    <iframe data-src="../samples/locations_en.html" ></iframe>
  </div>

---

### [ArcGIS API for JavaScript](https://developers.arcgis.com/javascript/)

Library for visualizing geospatial data in 2D and 3D on the web

<img src="../images/api-sdk.png" style="max-width: 50%"/>

---

### What does a product engineer do?

- Designs, tests and writes documentation for new features
- Makes demos and prototypes
- Answers questions from users
- Participates in conferences
- Writes blog posts

---

## Agenda

1. Basic concepts in 3D
  - Scene | Camera | Lighting | Types of data | Types of symbols
2. Tools for geospatial data visualization in 3D
3. Examples
4. Hands-on demo: create your first 3D map

---

## Basic concepts in 3D

---

<img src="../images/Intro3D.png" class="plain" style="max-width:70%"/>

---

### Scene

<div class="two-columns">
  <div class="half-column">
    <p>Local scene</p>
    <iframe data-src="../samples/local-scene.html" ></iframe>
  </div>
  <div class="half-column">
    <p>Global scene</p>
    <iframe data-src="../samples/global-scene.html" ></iframe>
  </div>
</div>

---

### Camera

<div>
   <video controls src="../images/camera.mp4" type="video/mp4" style="max-width: 70%"/>
</div>

---

### Light sources

<img src="../images/lights.png" class="plain" style="max-width:70%"/>

---

<iframe data-src="../samples/daylight.html" ></iframe>

---

### Raster data

<img src="../images/elevation.png" class="plain" style="max-width:70%"/>

---

### Elevation surface

<div class="two-columns">
  <div class="half-column">
    <img src="../images/elevation-2d.png" class="plain"/>
  </div>
  <div class="half-column">
    <img src="../images/elevation-3d-color.png" class="plain"/>
  </div>
</div>

---

### Tiled raster data

<img src="../images/tiles.png" class="plain" style="max-width:70%"/>

---

### Vector data

<img src="../images/vector-data-en.png" class="plain" style="max-width:70%"/>

---

### Point, line, polygon

<div class="two-columns">
  <div class="left-column">

<div class="code-snippet">
<button class="play" id="relativeToGround"></button>
<pre><code class="lang-ts">
layer.elevationInfo = {
  mode: "relative-to-ground",
  offset: 200
}
</code></pre>
</div>

<div class="code-snippet">
<button class="play" id="onTheGround"></button>
<pre><code class="lang-ts">
layer.elevationInfo = {
  mode: "on-the-ground"
}
</code></pre>
</div>



  </div>
  <div class="right-column">
    <iframe data-src="../samples/vector-data.html"></iframe>
  </div>
</div>

---

### Mesh data

<iframe data-src="../samples/berlin-palace.html"></iframe>

---

### Point cloud data

<iframe data-src="https://developers.arcgis.com/javascript/latest/sample-code/layers-pointcloud-size-density/live/index.html"></iframe>

---

### Types of symbols

<img src="../images/symbols_en.png" class="plain" style="max-width:65%"/>

---

### Tools for visualizing 3D geospatial data

Software:

[SceneViewer](https://www.arcgis.com/home/webscene/viewer.html) | [Mapbox Studio](https://www.mapbox.com/mapbox-studio/) | [KeplerGL](https://kepler.gl/)

Visualization libraries:

[ArcGIS API for JavaScript](https://developers.arcgis.com/javascript/) | [CesiumJS](https://cesium.com/cesiumjs/) | [MapboxGL](https://docs.mapbox.com/mapbox-gl-js/api/) | [DeckGL](https://deck.gl/#/) | [HarpGL](https://www.harp.gl/)

---

## Examples

---

### Urban planning

<div>
  <iframe frameborder="0" scrolling="no" allowfullscreen data-src="https://arcg.is/1yWDGn"></iframe>
</div>

---

### Ski resort map

<div>
  <iframe data-src="https://ralucanicola.github.io/ski-resort-map/"></iframe>
</div>

---

### 2019 earthquakes visualization

<div>
  <iframe data-src="https://ralucanicola.github.io/earthquakes-viz/"></iframe>
</div>

---

### Hiking map

<div>
  <iframe data-src="https://esri.github.io/hiking-trails-app/"></iframe>
</div>

---

### Globe of extremes

<div>
  <iframe data-src="https://ralucanicola.github.io/the-globe-of-extremes/"></iframe>
</div>

---

### A detailed building model

<div>
  <iframe data-src="https://esri.github.io/building-viewer"></iframe>
</div>

---

### Sketching buildings of San Francisco

<div>
  <iframe data-src="https://ralucanicola.github.io/JSAPI_demos/sanfranart/"></iframe>
</div>

---

## Questions? 🤔
<p><br/><small>
🐦 @nicolaraluk
<br/>
<br/>
📧 rnicola@esri.com
</small></p>

---

### Hands-on demo - [https://my-travels.glitch.me/](https://my-travels.glitch.me/)

<img src="../images/hands-on.png" style="max-width:70%"/>



