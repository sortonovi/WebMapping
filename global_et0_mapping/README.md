# Global ET₀ Mapping

An interactive visualization of global reference evapotranspiration (ET₀), based on long-term average climate data (1970–2000).
This project lets users explore monthly variations in ET₀ worldwide using a dynamic Leaflet-based web map.

## Features

The map shows ET₀ data month by month. A play button lets users watch the changes across the year in a smooth animation.
You can pause the animation at any time and manually check any specific month. A colored legend will help you understand the intensity of the ET₀ values.

- Web map with monthly ET₀ animation
- Color-coded legend and scale bar
- Country borders with tooltips (GeoJSON)
- Custom raster tiles (one per month)

## Technologies

This project uses web technologies like HTML, CSS, and JavaScript. The main mapping library is [Leaflet.js](https://leafletjs.com/), which is used to build the interactive map.
GeoJSON is used to show country borders, and raster tiles (images split by zoom and location) display the actual ET₀ values.

Overview:
- HTML / CSS / JavaScript
- Leaflet.js
- GeoJSON
- Raster tiles

## Data

ET₀ data is derived from satellite-based and climate-model interpolated datasets using the Penman-Monteith method, averaged over 30 years.
The datasets used: Zomer, Robert & Xu, Jianchu & Trabucco, Antonio. (2022). Version 3 of the Global Aridity Index and Potential Evapotranspiration Database. Scientific Data. 9. 10.1038/s41597-022-01493-1. 

## Live Demo

View the map here: [(https://sortonovi.github.io/webmapping/global-et0-mapping/)]

## License

Licensed under the MIT License — free to use with attribution.
