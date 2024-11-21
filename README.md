# leaflet-challenge

# Earthquake Visualization Map

## Overview
This project visualizes real-time earthquake data from the USGS GeoJSON feed on an interactive map using Leaflet.js. The map displays earthquake locations, magnitudes, and depths with markers whose sizes and colors represent the earthquake's magnitude and depth, respectively.

## Features
Interactive Map:
Displays earthquake locations worldwide using the Leaflet.js library.

## Dynamic Marker Styling:
Size: Reflects the earthquake's magnitude (larger magnitude = larger marker).
Color: Represents the earthquake's depth (deeper earthquakes = darker colors).

## Popups:
Click on any marker to view detailed earthquake information:

Location
Magnitude
Depth
Legend:
A legend provides context for the marker colors based on depth intervals.

## Technologies Used
- `HTML`: For structuring the page.  
- `CSS`: For styling the map and legend.  
- `JavaScript`: To handle logic, interactivity, and data fetching.  
- `Leaflet.js`: To create and display the interactive map.  
- `USGS GeoJSON Feed`: For accessing real-time earthquake data.

## Setup Instructions
Clone or download the repository.
Open the earthquake_map_with_legend.html file in any modern web browser.
Ensure an active internet connection for loading external libraries and GeoJSON data.

## Data Source
USGS GeoJSON Feed:
URL: Earthquake GeoJSON Feed

## Customization
Map Center: Update the setView() coordinates in the script to change the initial map center.
Tile Layer: Replace the OpenStreetMap URL in the L.tileLayer() function to use a different tile layer.
Marker Styles: Modify the getRadius() and getColor() functions to adjust marker size and color logic.

## Acknowledgments
Leaflet.js: Open-source JavaScript library for maps.
USGS: For providing earthquake data.
