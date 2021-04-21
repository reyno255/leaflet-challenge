# Data Visualizing with Leaflet

## Background

Welcome to the United States Geological Survey. The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.

## Technologies

The USGS provides earthquake data in a number of different formats, updated every 5 minutes through API. I picked the API with endpoint with data from the past 7 days to pull the data for the visualization (https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson), as well as the data from anther API endpoint (https://github.com/fraxen/tectonicplates) to illustrate the relationship between tectonic plates and seismic activity.

## Results

1. The circle size reflects magnitude strength of the earthquake and depth of the earthquake which is reflected by the gradient color scheme.

![Map](https://github.com/reyno255/leaflet-challenge/blob/main/static/images/popup_snapshot.jpg)

2. There is a correlation between fault lines, where tectonic plates converge or diverge, and earthquake location.

![Map](https://github.com/reyno255/leaflet-challenge/blob/main/static/images/map_snapshot.jpg)


 
