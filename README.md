# justinGrimesGeojson
Scripts to convert Justin Grimes' Icon from SVG to geoJSON

I used http://vectormagic.com/home to convert Justin Grime's Icon into SVG, then used the method [outlined here](http://whaticode.com/2012/02/01/converting-svg-paths-to-polygons/) to convert it to geojson.
Also in this script are x and y scales and offsets to "dial in" the resulting geoJSON to sit over Washington, DC. Justin's beloved city.

The resulting geojson is valid, but contains some overlapping polygons, so a bit more processing was necessary in QGIS to cut out the eye and mouth holes, etc.

The geojson included in repo was exported from cartodb, where these polygons have been beautifully styled: http://cdb.io/1E6H5HA
