# Geostationary Satellite Visualization Project

## Group Members
- Michael Chiaramonte
- Liam O'Donovan
- Kaelan Purcell
- Eric Green

## Description
This project is dedicated to mapping and visualizing geostationary satellite data, leveraging NASA's API. Our objective is to create an interactive 3D globe visualization that dynamically displays the positions of geostationary satellites and their respective distances from Earth. The visualization will allow users to see the spatial distribution of these satellites, offering insights into global satellite coverage and space utilization.

## Project Tasks
1. **Data Sourcing and Parsing:**
   - Source geostationary satellite data from NASA's API. Process and refine the data for visualization purposes.
   - **Data Source:** 
     - sscsw.py Package for accessing NASA's Satellite Situation Center (SSC) web services: [SSC Web Services](https://sscweb.gsfc.nasa.gov/WebServices/REST/)
   - **SSCSW.py Documentation:** 
     - [SSCWS Python Library](https://sscweb.gsfc.nasa.gov/WebServices/REST/py/sscws/index.html)
     - [SSCWS on PyPI](https://pypi.org/project/sscws/)

2. **Database Creation:** 
   - Develop a SQL database to store and manage the satellite data effectively.

3. **API Development:** 
   - Create a Flask API to interface with the SQL database, ensuring smooth data retrieval and handling for the frontend.

4. **Frontend Development:** 
   - Design and implement the frontend using JavaScript (with WebGL or Three.js for 3D rendering), HTML, and CSS. This includes the development of the 3D interactive globe and the mechanisms to display satellite positions and distances from Earth.

    ### Recommended Libraries for 3D Globe Visualization
    - **Three.js**: For creating and manipulating the 3D globe.
    - **D3.js**: To assist in data-driven transformations and visualizations.
    - **WebGL**: For rendering interactive 3D graphics.
    - **Leaflet.js**: To provide additional mapping functionalities if needed.
    - **Turf.js**: For advanced geospatial processing and data manipulation.



