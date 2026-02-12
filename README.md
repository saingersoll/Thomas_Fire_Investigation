# Thomas Fire Investigation of Impacts On Santa Barbara County (2017-2018)
![ThomasFireGE_12-13-2017](https://github.com/user-attachments/assets/b8cc539b-3be5-4de2-b0b9-e4ce8f155839) 
Google earth V 6.2.2.6613. (December 13, 2017). Santa Barbara, United States. 34.6099° N, 120.0665° W, Eye alt 13.72 feet. DigitalGlobe 2020. http://www.earth.google.com [December 12, 2023].
<img width="6567" height="2318" alt="santa_barbara_aqi_thomas_fire" src="https://github.com/user-attachments/assets/2137cc75-2d47-4a05-87e8-f95c5dba08d2" />


### Techniques Applied

    Directly accessing & processing MPC STAC data
    Raster analysis applying false color imagery
    Time series analysis

### Objective

To get a better understanding of the initial environmental and public health impacts caused by the Thomas Fire, together, we will explore the Air Quality Index (AQI) of SB County between 2017/01 - 2018/10. We’ll quanitfy and visualize the amount of particulate matter seen in the image abouve using both the Daily AQI and the average AQI over a 5 day rolling window in units of ppm. In addition, we will gain insight into what parts of Santa Barbara County were exposed to the Thomas Fire, through the examination of burn scars using false-color imaging on Landsat 8 satellite data from the Microsoft Planetary Computer (“MPC”). We will use a simplified collection of bands (red, green, blue, near-infrared and shortwave infrared) from the Landsat Collection 2 Level-2 atmosperically corrected surface reflectance data.


### Data Access

`AQI Data for PPM Quantification & Trend Analysis Overtime`


The [Daily Air Quality Index (AQI)](https://www.airnow.gov/aqi/aqi-basics/) data to quantify the particulate matter released into Santa Barbara County from the fire was collected here from the [US Environmental Protection Agency](https://aqs.epa.gov/aqsweb/airdata/download_files.html#AQI) to visualize the rolling AQI averages between 2017 and 2018.


`Landsat Data for Burn Scar Visualization`


For our true and false color imagery, we are going to direct access [Microsoft Planetary Computer Landsat Collection 2 Level-2 data](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2). The STAC item utilized for this project is **LE07_L2SP_042036_20171217_02_T1**. The raster data was collected on 2017-12-17.


*This data should be used for visualization purposes only.*

`California Fire Perimeter Data for Burn Scar Visualization`


The shapefile of fire perimeters in California were provided by the California State Geoportal. The [complete file can be accessed here.](https://gis.data.ca.gov/datasets/CALFIRE-Forestry::california-fire-perimeters-all-1/about)

#### Data References

    US Environmental Protection Agency (2023). Daily AQI by County [Data File]. Available from https://aqs.epa.gov/aqsweb/airdata/download_files.html#AQI. Accessed October 25, 2023

    Microsoft Planetary Computer. Landsat Collection 2 Level-2 [Dataset]. Available from https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2. Accessed November 28, 2023

    California Department of Forestry and Fire Protection (2023). California Fire Perimeters (all) [Data File]. Available from https://gis.data.ca.gov/datasets/CALFIRE-Forestry::california-fire-perimeters-all-1/about. Accessed November 28, 2023


