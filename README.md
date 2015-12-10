# MapboxStudio

mapbox.com
https://www.mapbox.com/tilemill/


http://www.dafont.com/santas-sleigh.font


Once you finish a style you can add it to a mapbox.js map with this code.
Or you can publish a preview from the Styles detail page.

mapboxgl.accessToken = <your access token here>; // your access token
var map = new mapboxgl.Map({
    container: 'map', // container id
    style: 'mapbox://styles/mapbox/streets-v8', // your style URL
    center: [-74.50, 40], // starting position
    zoom: 9 // starting zoom
});
