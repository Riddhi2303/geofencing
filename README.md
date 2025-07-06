# Geofencing Barrier Island Demo

This project is a simple web application that demonstrates geofencing using Leaflet.js for mapping and Turf.js for geospatial analysis. Users can check if a given latitude and longitude are inside a defined barrier island polygon.

## Features

- Interactive map display using Leaflet.js
- Draws a sample barrier island polygon on the map
- Form to input latitude and longitude
- Uses Turf.js to check if the point is inside the polygon
- Displays result and marks the location on the map

## How to Use

1. Open `index.html` in your web browser.
2. View the map and the polygon representing the barrier island.
3. Enter a latitude and longitude in the form below the map.
4. Click **Check Location**.
5. The result will display whether the point is inside or outside the barrier island, and a marker will appear on the map.

## Dependencies

- [Leaflet.js](https://leafletjs.com/) (for interactive maps)
- [Turf.js](https://turfjs.org/) (for geospatial calculations)

Both dependencies are loaded via CDN in the HTML file.

## Customization

- To use your own polygon, replace the `barrierIslandPolygon` coordinates in the script section of `index.html` with your GeoJSON polygon.

## License

This project is for demonstration and educational purposes only.
