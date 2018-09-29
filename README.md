# Homework 3: Leaflet Maps

By: Min Yan BEH (mbeh)

###  Background and Motivation

I'll be bringing a bunch of Singaporean friends around in NYC this Christmas. The question is: 

* Where should I go sightseeing? 
* How can I get around the city?

Hence, I put together a leaflet map with the following layers:

* Polygons that shows the demarcation of NYC counties
* Circle markers that shows interesting landmarks (with popup descriptions, and colored by scenic/interior landmark types with a helpful legend)
* Polylines that show where the bridges are (many of them are scenic, and provide useful routes for circumventing busy roads)

There is also a layer control function that allows toggling of these overlay groups, and allows the user to choose between 3 basemap themes.

###  Finished Output

![Screeenshot](leaflet-screenshot.png)

###  Datasets

Sources:

* NYC Counties polygons - pulled from `tigris` package
* NYC Bridges polylines - subsetted from [NYC roads data](https://data.cityofnewyork.us/City-Government/NYC-Street-Centerline-CSCL-/exjm-f27b)
* NYC Landmark points - subsetted from [NYC Individual Landmarks data](https://data.cityofnewyork.us/Housing-Development/Individual-Landmarks/ch5p-r223)

The data links are all taken from NYC Open Data.