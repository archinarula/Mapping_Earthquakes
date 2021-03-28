# Written Analysis of the Earthquake Leaflet challenge Module 13

## Overview of Analysis
This project purpose is to build an interactive dashboard using Leaflet.js to gather earthquake JSON data from the USGS API. The earthquake data is presented on the interactive dashboard in relation to the tectonic plates location on the earth and according to the event magnitude.  This dashboard is used by the researcher to create and explore interactive maps of earthquake around the world.The viewer is given option to toggle between Sattelite, Street and Dark views and can make selection to see data between the all earthquakes, major earthquakes and tectonic plate locations around the world. The project also focusses on using the GIT Branching functionality to publish code betwen the Main and Dev branches. 

Data Source: 
![Earthquakes GeoJSON data](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson)
![Major Earthquakes GeoJSON data](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson)
![Tectonic Plate GeoJSON data](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json)
![Mapbox API Key generated from Mapbox site](https://mapbox.com)

## Deliverable: 
This analysis consists of three technical analysis deliverables and a written report:

- Deliverable 1: Add Tectonic Plate Data 

- Deliverable 2: Add Major Earthquake Data 

- Deliverable 3: Add an Additional Map 



## Results

The logic for Deliverable 1, 2 and 3 is in the challenge_logic.js file

Please note the config.js has the Mapbox API key removed due to security reasons and  user needs to add his/her key to view the complete deliverable data

The interactive dashboard looks like below and is in the repository: https://github.com/archinarula/Mapping_Earthquakes/tree/Earthquake_challenge

![Interactive_dashboard_withLeaflet](https://github.com/archinarula/Mapping_Earthquakes/blob/Earthquake_challenge/Interactive_Dashboard_withLeaflet.png)

