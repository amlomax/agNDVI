# NDVI vs. Soil Moisture 

## Ava Lomax
github: amlomax

### Summary
For this project I want to utilize NDVI data to assess vegetation health of an agricultural area (Merced, CA). I want to then complete an correlation analysis to determine the impact of Climate Smart initiatives. 

### Objectives
* Have NDVI as a foundation for agricultural management 
* Do a time series analysis 
* Get an understanding of the relation between vegetation stress and soil mangement 

### Datasets
I'm still in the process of finding datasets that will correlate with eachother, however here are some examples of datasets I plan on using (will be updating this as I work):

* USGS Earth Explorer for Landsat images to use

Climate related:

* Soil Moisture: SMAP data

### Python Packages
* rasterio 
* numpy
* matplotlib
* geopandas
* h5py
* rioxarray
* os
* xarray
* glob

### Planned Approach
1. Download and read soil moisture and NDVI datasets
2. process data and extract values into GDFs
3. Merge data based on geometries
4. Correlation analysis
5. Time series analysis


### Expected Outcomes
* A correlation in the relationship between NDVI, soil, and climate factors
* Stress indicators for vegetation health

### References 

Benos, L., Tagarakis, A. C., Dolias, G., Berruto, R., Kateris, D., & Bochtis, D. (2021). Machine learning in agriculture: A comprehensive updated review. Sensors, 21(11), 3758.

Shah, K. K., Modi, B., Pandey, H. P., Subedi, A., Aryal, G., Pandey, M., & Shrestha, J. (2021). Diversified crop rotation: an approach for sustainable agriculture production. Advances in Agriculture, 2021, 1-9.

### Note
Depending on how challenging this sketched out plan ends up being, I want to maybe plan how a machine learning model could be programmed using the datasets and results to predict areas that may thrive more given adverse conditions. 
