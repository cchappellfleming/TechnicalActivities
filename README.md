# Leaflet
Leading open-source Java Script Library for interactive maps. Designed with simplicity, performance and usability in mind. Within the quick start tutorial, Leaflet basics such as setting up the page, Leaflet map, markers, polylines, popups and events were explored.
## Preparing the page
1. Include Leaflet CSS reference in head section of html page
```
 <link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css"
   integrity="sha512-xodZBNTC5n17Xt2atTPuE1HxjVMSvLVW9ocqUKLsCC5CXdbqCmblAshOMAS6/keqq/sMZMZ19scR4PsZChSR7A=="
   crossorigin=""/>
```
2. Include leaflet JavaScript reference after CSS reference
```
 <script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js"
   integrity="sha512-XQoYMqMTK8LvdxXYG3nZ448hOEQiglfqkJs1NOQV44cWnUrBc8PkAOcXy20w0vlaXaVUearIOBhiXZ5V3ynxwA=="
   crossorigin=""></script>
```
3. div element with id 'map' within the body. Additional css included in the style element to facilitate the desired size of the map on the page. 

## Displaying the map


