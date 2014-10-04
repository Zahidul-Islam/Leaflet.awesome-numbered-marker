# Leaflet.AwesomeNumberMarkers
A plugin that adds number markers for Leaflet.

## Screenshots
![AwesomeNumberMarkers screenshot](https://raw.githubusercontent.com/Zahidul-Islam/Leaflet.awesome-numbered-marker/master/screenshots/leaflet-awesome-number-marker.png "Screenshot of AwesomeNumberMarkers")


## Usage

````xml
<link rel="stylesheet" href="../src/leaflet_awesome_number_markers.css" />
````

````xml
<script src="../src/leaflet_awesome_number_markers.js"></script>
````

````js
var blueMarker = L.marker([51.941196,4.512291], {
                    icon: new L.AwesomeNumberMarkers({
                      number: 1, 
                      markerColor: "blue"
                  })}).addTo(map);
````
