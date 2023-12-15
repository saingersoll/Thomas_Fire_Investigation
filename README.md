# Thomas Fire Investigation
## Overview
The goal of this notebook is to assess the impacts of the 2017 Thomas Fire on Santa Barbara County, CA. We will be exploring the Air Quality Index of SB county between 17/01 - 18/10 to visualize the spike in particulate matter in correspondence to the Thomas Fire (17/12 - 18/01).

![image](https://github.com/saingersoll/Thomas_Fire_Investigation/assets/141206781/5c9d53db-dafe-4228-8ca0-d161e53f816a)

We will also create a false color image using landsat data to display damages caused fire scar of the Thomas Fire in 2017.

![image](https://github.com/saingersoll/Thomas_Fire_Investigation/assets/141206781/71247e31-b986-4dc3-83d9-42219ecc2fef)


### About the data

#### AQI Data
In this notebook we will use [Air Quality Index (AQI)](https://www.airnow.gov/aqi/aqi-basics/) data from the [US Environmental Protection Agency](https://www.epa.gov) to visualize the impact on the AQI of the 2017 [Thomas Fire](https://en.wikipedia.org/wiki/Thomas_Fire) in Santa Barbara County[^1]. 

[^1]: AirNow.gov, U.S. EPA. (n.d.). Aqi Basics. AQI Basics | AirNow.gov. <https://www.airnow.gov/aqi/aqi-basics/>

#### False Color Image Data

A simplified collection of bands (red, green, blue, near-infrared and shortwave infrared) from the Landsat Collection 2 Level-2 atmosperically corrected surface reflectance data, collected by the Landsat 8 satellite. 

The data was accessed and pre-processed in the Microsoft Planetary Computer to remove data outside land and coarsen the spatial resolution ([Landsat Collection in MPC](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2))[^2]. Data should be used for visualization purposes only. 

[^2]: Microsoft Planetary Computer. Planetary Computer. (n.d.). <https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2>

Additionally a shapefile of fire perimeters in California during 2017. 
The [complete file can be accessed in the CA state geoportal](https://gis.data.ca.gov/datasets/CALFIRE-Forestry::california-fire-perimeters-all-1/about)[^3].

[^3]: California fire perimeters (all). California State Geoportal. (n.d.). https://gis.data.ca.gov/datasets/CALFIRE-Forestry::california-fire-perimeters-all-1/about

