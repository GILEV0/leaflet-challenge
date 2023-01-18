# leaflet-challenge This Challenge uses both **HTML** and **JavaScript** 
# Module 15 - Leaflet Challenge Assignment

![image](https://user-images.githubusercontent.com/112173540/212465530-cddf344b-fcc5-47bd-93b7-584b1c08b7f9.png)

# Background
The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.
The USGS is interested in building a new set of tools that will allow them to visualise their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, you have been tasked with developing a way to visualise USGS data that will allow them to better educate the public and other government organisations (and hopefully secure more funding) on issues facing our planet.

- In this project we retrieve earthquake data, tectonic data and major earthquakes data for the last seven days and created a visualisation on a map.
# Instructions
The instructions for this activity are broken into two parts:
  - Part 1: Create the Earthquake Visualisation
  - Part 2: Gather and Plot More Data (Optional with no extra points earning)
  
# Part 1: Create the Earthquake Visualisation
Your first task is to visualise an earthquake dataset. Complete the following steps:

### 1. Get your dataset. To do so, follow these steps:
   - The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the <a href="https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php">USGS GeoJSON Feed</a> and choose a dataset to visualise. The following image is an example screenshot of what appears when you visit this link:
    
  ![image](https://user-images.githubusercontent.com/112173540/212465948-637b4bf7-98ef-4505-a9d7-d3822ab2922c.png)

   - When you click a dataset (such as "All Earthquakes from the Past 7 Days"), you will be given a JSON representation of that data. Use the URL of this JSON to pull in the data for the visualisation. The following image is a sampling of earthquake data in JSON format:
    
   ![image](https://user-images.githubusercontent.com/112173540/212465987-dccc287d-531d-411b-908e-eb48e81f7499.png)

### 2.  Import and visualise the data by doing the following:

   - Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.
  
   - Include popups that provide additional information about the earthquake when its associated marker is clicked.

   - Create a legend that will provide context for your map data.

# Part 2: Gather and Plot More Data (Optional with no extra points earning) 
Plot a second dataset on your map to illustrate the relationship between tectonic plates and seismic activity. You will need to pull in this dataset and visualise it alongside your original data. Data on tectonic plates can be found at https://github.com/fraxen/tectonicplates.  

Perform the following tasks:

- Plot the tectonic plates dataset on the map in addition to the earthquakes.

- Add other base maps to choose from.

- Put each dataset into separate overlays that can be turned on and off independently.

- Add layer controls to your map.

The following image is the result:

![image](https://user-images.githubusercontent.com/112173540/212466686-8dbe5a1d-66cc-4db5-bc62-34a42c0debd3.png)


#### Deployed website: https://gilev0.github.io/leaflet-challenge/

## Resources used
- Data Source: <a href="https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php">Earthquake Data</a>
- JSON Formatter: <a href="https://jsonformatter.org/">JSON Formatter</a>
- Software: Visual Studio 1.69.1 
- HTML code: <a href="https://github.com/GILEV0/leaflet-challenge/blob/main/index.html" target="_blank">index.html</a>
- JavaScript code:  <a href="https://github.com/GILEV0/leaflet-challenge/blob/main/static/js/logic.js" target="_blank">logic.js</a>
- Tectonic Plate data: <a href="https://github.com/fraxen/tectonicplates" target="_blank">boundaries.dbf</a>
