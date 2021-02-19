# Mapping_Earthquakes

## Summary 

- The Leaflet.js API was used to populate a geographical map from a URL with GeoJSON earthquake info. Each earthquake is depicted visually by a circle and color, where a greater magnitude has a larger diameter and the color would be darker. Moreover, each earthquake has a pop-up marker that will indicate the magnitude of the earthquake and the location of the earthquake when pressed.

![Screen Shot 2021-02-19 at 9 30 14 AM](https://user-images.githubusercontent.com/16258584/108524957-3502c680-7295-11eb-961e-d616966f790c.png)

## Overview of Analysis

### Tectonic Plate Data

- Used knowledge of JavaScript, Leaflet.js, and geoJSON data, added tectonic plate data using d3.json(), added the data using the geoJSON() layer, set the tectonic plate LineString data to stand out on the map, and added the tectonic plate data to the overlay object with the earthquake data.

### Major Earthquake Data

- Used knowledge of JavaScript, Leaflet.js, and geoJSON data, added major earthquake data to the map using d3.json(), and a color and set the radius of the circle based on the magnitude of earthquake, and created a popup marker for each earthquake that displays the magnitude and location of the earthquake using the GeoJSON layer, geoJSON()

### Created an Additional Map

- Used knowledge of JavaScript and Leaflet.js add a third map style to your earthquake map.

