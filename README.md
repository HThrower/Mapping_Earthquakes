# Mapping_Earthquakes
An interactive earthquake map with JavaScript and Leaflet

## Project Overview
In this module, we used the Leaflet.js Application Programming Interface (API) to populate a geographical map with GeoJSON earthquake data from a URL. Each earthquake was visually represented by a circle and color, where a higher magnitude has a larger diameter and is darker in color. In addition, each earthquake has a popup marker that, when clicked, shows the magnitude of the earthquake and the location of the earthquake.

## Resources
Data Source: Earthquakes GeoJSON, Earthquakes above 4.5mag GeoJSON, Tectonic Plate GeoJSON
Software: HTML/CSS, JavaScript, Visual Studio Code 1.49.1, Leaflet 1.7.1, D3.js 6.2.0

## Objectives
-Use d3.json() to get tectonic plate data and add the data using the L.geoJSON() layer.
-Style the tectonic plate LineString data to stand out on the map.
-Add the tectonic plate data as an overlay with the earthquake data.
-Add a third map style to allow the user to select from three different maps.

## Summary
For the challenge, a third map style is added to the logic.js file and has the following:

-It is added to the baseMaps.
-When selected the map style is present on the map.
-The earthquake and tectonic data are present on the map style.

![image](https://user-images.githubusercontent.com/31675832/151708802-7b0ea899-efee-417a-8d5c-7d9630e41a9b.png)
![image](https://user-images.githubusercontent.com/31675832/151708872-0c4cfc6b-2062-4950-86a5-b003ce9a66b9.png)
![image](https://user-images.githubusercontent.com/31675832/151708914-0828ebdd-a239-4074-a824-54253f5e5096.png)

The tectonic data is added to the challengelogic.js file and has the following:

-It is added to the overlay
-It shows up on any map with the earthquake data by default.
*The lines are styled in a bright dark color.

