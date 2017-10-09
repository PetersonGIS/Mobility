# Mobility [![License](https://img.shields.io/badge/License-BSD%202--Clause-orange.svg)](https://opensource.org/licenses/BSD-2-Clause)
This is a map style that uses a publically available [Tegola](https://github.com/terranodo/tegola) extract of OpenStreetMap for the world. It is currently still under development and is primarily styled using [Maputnik](https://maputnik.github.io/editor).

<img align="right" alt="TegolaMobility" src="logo.png" />

## Viewing the map in the browser
- [Rendered with OpenLayers:](http://htmlpreview.github.io/?https://github.com/PetersonGIS/Mobility/blob/master/live-map.html)
Note that the road labels and tilt functionality are missing from this map, which displays the mobility.json style.
- [Rendered with Mapbox:](http://www.gretchenpeterson.com/live-map-mapbox-mobility.html) 
  Note that road labels and tilt are working in this map, which displays the mobility3d.json style. Test the tilt (pitch)   functionality by holding ctrl while clicking and dragging. The building extrusions are not yet functional on mobile devices.

## Map Design

The mobility basemap has a subdued color scheme to accomodate data overlays and is in the same style family as other light basemaps. Use mobility.json for OpenLayers or mobile and mobility3d.json for Mapbox implementations. Use either mobility.json or mobility3d.json in Maputnik for building your own style with Tegola data.

[![mobility3d.json map demo in a mapbox renderer](demo.gif)](http://www.gretchenpeterson.com/live-map-mapbox-mobility.html#14.66/50.7173/7.1318/-52/60)

## Editing this style in Maputnik

Editing this style to create your own style.json file is fairly straightforward. Point your browser to Maputnik at  [https://maputnik.github.io/editor](https://maputnik.github.io/editor), click Open > Upload and point to either mobility.json or mobility3d.json, which you have saved locally. Change the style to suit you, then go to Export > Download to save your newly re-styled json file locally. This can then be used in a renderer like OpenLayers or Mapbox for browser display. Note that mobility.json and mobility3d.json use data extracted from OSM and hosted using Tegola. You may want to explore using other open tilesets as well.
