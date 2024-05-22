# Crop Management Using NDVI Data

## Ava Lomax
github: amlomax

### Summary
For this project I want to utilize NDVI data to assess vegetation health of agricultural areas, specifically areas with stress. I want to then complete an analysis on soil and look at factors such as fertilizer, overall tempeature, precipitation, etc. 

### Objectives
* Have NDVI as a foundation for agricultural management 
* Do a time series analysis 
* Get an understanding of the relation between vegetation stress and soil mangement 

### Datasets
I'm still in the process of finding datasets that will correlate with eachother, however here are some examples of datasets I plan on using (will be updating this as I work):

* USGS Earth Explorer for Landsat images to use

Climate related:

* Precipitation 


https://cds.climate.copernicus.eu/cdsapp#!/dataset/satellite-precipitation?tab=form

* Temperature 

https://cds.climate.copernicus.eu/cdsapp#!/dataset/insitu-gridded-observations-global-and-regional?tab=form

### Python Packages
* rasterio 
* numpy
* matplotlib
* geopandas

### Planned Approach
1. Research more on different indicators of successful (or unsuccessful) agricultural production to gather the needed datasets. 
2. Find 3-5 areas to focus on (primarily agricultural regions) and maybe find 3 time periods to analyze
3. Get the NDVIs for each area, get data on healthiest and most stressed areas
4. Compare this data to soil data 


### Expected Outcomes
* A correlation in the relationship between NDVI, soil, and climate factors
* Stress indicators for vegetation health

### References 

Benos, L., Tagarakis, A. C., Dolias, G., Berruto, R., Kateris, D., & Bochtis, D. (2021). Machine learning in agriculture: A comprehensive updated review. Sensors, 21(11), 3758.

Shah, K. K., Modi, B., Pandey, H. P., Subedi, A., Aryal, G., Pandey, M., & Shrestha, J. (2021). Diversified crop rotation: an approach for sustainable agriculture production. Advances in Agriculture, 2021, 1-9.

### Note
Depending on how challenging this sketched out plan ends up being, I want to maybe plan how a machine learning model could be programmed using the datasets and results to predict areas that may thrive more given adverse conditions. 
