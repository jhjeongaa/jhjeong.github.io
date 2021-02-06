---
layout: page
---
roadlink test

<script src='https://api.mapbox.com/mapbox-gl-js/v2.1.0/mapbox-gl.js'></script>
<link href='https://api.mapbox.com/mapbox-gl-js/v2.1.0/mapbox-gl.css' rel='stylesheet' />

<div id='map' style='width: 700px; height: 400px;'></div>
<script>
mapboxgl.accessToken = 'pk.eyJ1IjoiamhqZW9uZ2FhIiwiYSI6ImNra2RuajU3NjAwOXcycW85NDZxZGF5aWcifQ.V-xid8C9HSSl_7T1B6ERlg';
var map = new mapboxgl.Map({
container: 'map',
style: 'mapbox://styles/mapbox/streets-v11', // stylesheet location
center: [-74.5, 40], // starting position [lng, lat]
zoom: 9 // starting zoom
});
</script>
