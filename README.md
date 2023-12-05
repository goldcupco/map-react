

<!-- PROJECT  -->
<br />
<p align="center">
 

  <h3 align="center">GIS Application Geospatial Anaylisis of major cities by population</h3>

  <p align="center">
    GIS App built with React and  Leaflet using Open Street Map GeoJSON data
    <br />
   
  </p>
</p>


<!-- ABOUT THE PROJECT -->
##  GIS Application
[![Product Name Screen Shot][product-screenshot]](https://map-react2-dusky.vercel.app/)


Data format is GeoJSON  [GeoJSON](https://geojson.org/) .
This is a Front End application using React  [React](https://reactjs.org/)
with Leaflet [Leaflet](https://leafletjs.com/) , and
[Vite](https://vitejs.dev/) is a build tool for javascript.
Spatial data is visualised showing population statistics.




<!-- GETTING STARTED -->
## Getting Started
Below are instructions to run a local copy.

### Installation
Install [Node.js](https://nodejs.org/) and  [yarn](https://yarnpkg.com/) .
 [vite](https://vitejs.dev/) is used as a build tool for fast development. 
 With these  dependencies installed, install the application by running the following command in the root directory of the project:
```bash
$ cd map-react
$ yarn
$ yarn dev
``` 

### Usage
To use the application, GeoJSON files at ./src/data are the ones  to visualize. 
These are cities.jsx , continents.jsx,mountains.jsx

Then start the application with the line command:
```bash
$ yarn dev
```
This will start the application and open the application at http://localhost:5173/  in the web browser.
From there, you can use the various controls to view and manipulate the data in the GeoJSON file.

Geospatial data taken from  https://www.naturalearthdata.com/


### Features
* Show map Marker from the Geospatial Data files
* Filter radius based on Marker (City)
* Custom circle radius (add tooltip for more information)
* Geo filter, filter by continents


<!-- LICENSE -->
## License
This application is licensed under the MIT License. 





