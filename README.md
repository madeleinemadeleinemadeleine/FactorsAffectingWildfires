# FactorsAffectingWildfires
A global scale study of the factors affecting wildfires' distribution over the past 10 years. We used Google Earth Engine for retrieving data and Python to analyse it.

This project is the premise of a larger study, aiming at understanding what are the factors affecting wildfire distribution around the globe.
We propose two different methods to extract information on wildfires from multispectral satellite imagery, in order to study what are the factors that are affecting wildfires' distribution at a global scale. An image containing all the factors will be created using Google Earth-Engine, and we will randomly extract points from both the burnt and unburnt areas, to analyze them through machine learning classification tools (Random Forest, Adaptative Boosting, dimension reduction analysis,etc.).

In order to extract points from the image, we propose two different methods. The first approach, more straightforward consists of applying a mask over the area of interest in order to extract points from it. This solution leads to interesting and fast first results.
The second approach is using a hexagon tiling to extract the points in a particular area of the globe, which is being distinguished by its amount of burned pixels. This method leads to a higher flexibility in the point extraction, and allowed us to reach higher accuracy in the classification process.
Our work sets the scene and material for further analysis of these factors, while already providing some preliminary experiments on the data.


Keywords : *Google Earth-Engine*, *Remote Sensing*, *wildfires global distribution*

## First approach 
see **first approach**  folder for the raw codes and information on how to use them 

GEE code link : 
https://code.earthengine.google.com/?scriptPath=users%2Fmadeleinesarahabbes%2FGeoInfProject%3Afirst_approach

## Second approach 
see **second approach**  folder for the raw codes and information on how to use them

GEE code link :

https://code.earthengine.google.com/?scriptPath=users%2Fmadeleinesarahabbes%2FGeoInfProject%3AHexagon_method_burned_pixels

https://code.earthengine.google.com/?scriptPath=users%2Fmadeleinesarahabbes%2FGeoInfProject%3AHexagon_method_unburned_pixels

## Data analysis
Check the **notebook** folder in this repository.

## Results
Read the fourth chapter of **Project Technical Report** in this repository.
