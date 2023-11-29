# Thomas Fire Investigation
## Overview
The goal of this notebook is to assess the impacts of the 2017 Thomas Fire on Santa Barbara County, CA. We will be exploring the Air Quality Index of SB county between 17/01 - 18/10 to visualize the spike in particulate matter in correspondence to the Thomas Fire (17/12 - 18/01).

![AQI-Assessment.png](attachment:3a5644eb-c51b-4efd-afa5-650df3160e82.png)

We will also create a false color image using landsat data to display damages caused fire scar of the Thomas Fire in 2017.

![image](https://github.com/saingersoll/Thomas_Fire_Investigation/assets/141206781/4ae22dc7-d31b-4dde-b8a8-183a2595ddbd)

### About the data

#### AQI Data
In this notebook we will use [Air Quality Index (AQI)](https://www.airnow.gov/aqi/aqi-basics/) data from the [US Environmental Protection Agency](https://www.epa.gov) to visualize the impact on the AQI of the 2017 [Thomas Fire](https://en.wikipedia.org/wiki/Thomas_Fire) in Santa Barbara County. 

#### False Color Image Data
**First dataset**

A simplified collection of bands (red, green, blue, near-infrared and shortwave infrared) from the Landsat Collection 2 Level-2 atmosperically corrected surface reflectance data, collected by the Landsat 8 satellite. 

Information about Landsat bands from USGS:

- [What are the band designations for the Landsat satellites?](https://www.usgs.gov/faqs/what-are-band-designations-landsat-satellites)

-[Common Landsat Band Combinations](https://www.usgs.gov/media/images/common-landsat-band-combinations)

-[How do I use a scale factor with Landsat Level-2 science products?](https://www.usgs.gov/faqs/how-do-i-use-a-scale-factor-landsat-level-2-science-products)


The data was accessed and pre-processed in the Microsoft Planetary Computer to remove data outside land and coarsen the spatial resolution ([Landsat Collection in MPC](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2)). Data should be used for visualization purposes only. 
Read more about false color images here:
[NASA Earth Observatory - Why is that Forest Red and that Cloud Blue?
How to Interpret a False-Color Satellite Image](https://earthobservatory.nasa.gov/features/FalseColor)

**Second dataset**

A shapefile of fire perimeters in California during 2017. 
The [complete file can be accessed in the CA state geoportal](https://gis.data.ca.gov/datasets/CALFIRE-Forestry::california-fire-perimeters-all-1/about).
