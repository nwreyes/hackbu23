#Crowdsourcing Biodiversity Data

## Inspiration
This project was inspired by a biology related brainstorming session a few days before the hackathon between four brilliant minds. It further evolved throughout the hackathon into what it is now.

## What it does
This code displays a biodiversity heatmap of New York State (NYS) based on crowdsourced data from the Global Biodiversity Information Facility. Interestingly, this heatmap is an inverse of an official NYS biodiversity heatmap. This showcases a potential weakness in crowdsourced data, excessive representation of urban communities. This is particularly harmful when trying to view data largely irrelevant to urban communities, such as statewide biodiversity data. Our project functions as an example of this weakness.

## How we built it
We built this in Jupyter Notebook using python libraries such as Numpy and Gmaps. The map is rendered in a web browser.

## Challenges we ran into
By far the greatest challenge we faced was project setup. Trying numerous tools such as MapBox and OsgEarth, we struggled to find a setup that would run on any of our machines. This was largely due to build failures outside our control and slow download speeds preventing us from testing our ideas and data for hours on end. Finding quality data to visualize was also a challenge.

## Accomplishments that we're proud of
We are proud of not giving up. Spending hours failing to make progress was immensely demoralizing. However, we have still managed to learn a lot and have presentable material by the end of the 24-hour mark.

## What we learned
Generally, we learned a lot about hackathon strategies and task delegation. We also learned a lot about Numpy, dependency management, Docker, and the Google Maps api. 

## What's next for Visualization of Biodiversity in New York State
Moving forward, were our group to continue to use what we've created, we would further explore the weaknesses of crowdsourced data in different contexts, and compare them to population data.

## How to use with data
Pull git repo and use file in a Jupyter Notebook. To get the data, download from the [GBIF website](https://www.gbif.org/occurrence/download?dataset_key=50c9509d-22c7-4a22-a47d-8c48425ef4a7&has_coordinate=true&has_geospatial_issue=false&year=2019,2023&geometry=POLYGON((-75.52013%2045.261,-76.2741%2044.25052,-79.4299%2043.27891,-79.54649%2042.22957,-75.07708%2041.7321,-74.01996%2040.41848,-71.52486%2041.20354,-73.06389%2041.08695,-72.85403%2045.261,-75.52013%2045.261))&geometry=POLYGON((-79.547%2042.2028,-75.0855%2041.7359,-74.04794%2040.50121,-71.55116%2041.17884,-73.02478%2041.09846,-72.84616%2045.26033,-75.52128%2045.2636,-76.28907%2044.23642,-79.47437%2043.30262,-79.547%2042.2028))&occurrence_status=present). Rename the .cvs according to the name in the .ipynb file and enjoy the heatmap!
