# Leaflet Surveying

## Background
The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it.

## Instructions
The instructions for this activity are broken into two parts:

Part 1: Create the Earthquake Visualization

Part 2: Gather and Plot More Data

## Part 1: Create the Earthquake Visualization
1. Get your dataset: Visit the USGS GeoJSON Feed page and select a dataset to visualize.
2. Import and visualize the data:
   
    2.1. Utilize Leaflet to create a map that plots earthquakes based on their latitude and longitude.
   
    2.2. Size the markers according to earthquake magnitude and color them based on depth.
   
    2.3. Include popups for additional earthquake information and a legend for context.

## Part 2: Gather and Plot More Data
1. Plot additional data: Optionally, plot a second dataset illustrating the relationship between tectonic plates and seismic activity. This dataset can be found at fraxen/tectonicplates.
2. Plot the tectonic plates dataset alongside earthquakes.
3. Include multiple base maps to choose from.
4. Organize each dataset into separate overlays for independent toggling.
5. Add layer controls to the map.

## Resources
- USGS GeoJSON Feed
- fraxen/tectonicplates
