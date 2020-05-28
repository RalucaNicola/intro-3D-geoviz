## Vizualizează lumea în 3D

<img src="../images/globe_2.png" class="plain" style="height: 300px"/>
<p style="font-size: 75%"><br/>
  Raluca Nicola - Product Engineer ArcGIS API for JavaScript
</p>
<p><br/><small>
Seminar Asociația Română de Cartografie, 8 Mai 2020
</small></p>

---

### Despre mine
  <div>
    <iframe data-src="../samples/locations.html" ></iframe>
  </div>

---

### [ArcGIS API for JavaScript](https://developers.arcgis.com/javascript/)

Bibliotecă de vizualizare online a datelor spațiale în 2D și 3D

<img src="../images/api-sdk.png" style="max-width: 50%"/>

---

### Ce implică munca de product engineer?

- Design și specificație pentru un nou feature (de exemplu un nou tip de simbol)
- Testare și documentație a feature-ului
- Demo-uri si prototipuri
- Răspunsuri la întrebările utilizatorilor (forum, medii sociale, mail)
- Participare la conferințe
- Bloguri

---

## Agendă

1. Concepte de bază în 3D
  - Scena | Camera | Iluminare | Tipuri de date | Tipuri de simboluri
2. Instrumente de vizualizare de date geospațiale 3D online
3. Exemple de vizualizări
4. Hands-on demo: creează prima hartă 3D

---

## Concepte de bază în 3D

---

<img src="../images/Intro3D.png" class="plain" style="max-width:70%"/>

---

### Scena

<div class="two-columns">
  <div class="half-column">
    <p>Scenă proiectată</p>
    <iframe data-src="../samples/local-scene.html" ></iframe>
  </div>
  <div class="half-column">
    <p>Glob</p>
    <iframe data-src="../samples/global-scene.html" ></iframe>
  </div>
</div>

---

### Camera

<div>
   <video controls src="../images/camera.mp4" type="video/mp4" style="max-width: 70%"/>
</div>

---

### Surse de lumină

<img src="../images/lights.png" class="plain" style="max-width:70%"/>

---

<iframe data-src="../samples/daylight.html" ></iframe>

---

### Tipuri de date

---

### Date raster

<img src="../images/elevation.png" class="plain" style="max-width:70%"/>

---

### Suprafață de teren

<div class="two-columns">
  <div class="half-column">
    <img src="../images/elevation-2d.png" class="plain"/>
  </div>
  <div class="half-column">
    <img src="../images/elevation-3d-color.png" class="plain"/>
  </div>
</div>

---

### Date raster tiled

<img src="../images/tiles.png" class="plain" style="max-width:70%"/>

---

### Date vector

<img src="../images/vector-data-ro.png" class="plain" style="max-width:70%"/>

---

### Punct, linie, poligon

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

### Date de tip mesh

<iframe data-src="../samples/berlin-palace.html"></iframe>

---

### Point cloud

<iframe data-src="https://developers.arcgis.com/javascript/latest/sample-code/layers-pointcloud-size-density/live/index.html"></iframe>

---

### Tipuri de simboluri

<img src="../images/symbols_ro.png" class="plain" style="max-width:65%"/>

---

### Software pentru vizualizare web 3D

Software:

[SceneViewer](https://www.arcgis.com/home/webscene/viewer.html) | [Mapbox Studio](https://www.mapbox.com/mapbox-studio/) | [KeplerGL](https://kepler.gl/)

Biblioteci de vizualizare:

[ArcGIS API for JavaScript](https://developers.arcgis.com/javascript/) | [CesiumJS](https://cesium.com/cesiumjs/) | [MapboxGL](https://docs.mapbox.com/mapbox-gl-js/api/) | [DeckGL](https://deck.gl/#/) | [HarpGL](https://www.harp.gl/) | [Potree](http://potree.org/) | [ThreeJS]()

---

## Exemple

---

### Planificare urbană

<div>
  <iframe frameborder="0" scrolling="no" allowfullscreen data-src="https://arcg.is/1yWDGn"></iframe>
</div>

---

### Hartă a unei stațiuni de ski

<div>
  <iframe data-src="https://ralucanicola.github.io/ski-resort-map/"></iframe>
</div>

---

### Vizualizare de cutremure în 2019

<div>
  <iframe data-src="https://ralucanicola.github.io/earthquakes-viz/"></iframe>
</div>

---

### Hartă de drumeții montane

<div>
  <iframe data-src="https://esri.github.io/hiking-trails-app/"></iframe>
</div>

---

### Globul extremelor

<div>
  <iframe data-src="https://ralucanicola.github.io/the-globe-of-extremes/"></iframe>
</div>

---

### Model 3D detaliat al unei clădiri - date BIM

<div>
  <iframe data-src="https://esri.github.io/building-viewer"></iframe>
</div>

---

### Vizualizare schiță a clădirilor din San Francisco

<div>
  <iframe data-src="https://ralucanicola.github.io/JSAPI_demos/sanfranart/"></iframe>
</div>

---

### Hands-on demo - [https://my-travels.glitch.me/](https://my-travels.glitch.me/)

<img src="../images/hands-on.png" style="max-width:70%"/>
<p><small>
Instrucțiuni video (în engleză): <br>https://www.youtube.com/watch?v=rqe2aRbpTGY
</small></p>

---

## Întrebări? 🤔

<p><br/><small>
Versiune live a prezentării: <br>https://raluca-nicola.net/intro-3D-geoviz/ro
</small></p>


