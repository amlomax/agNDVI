# NDVI vs. Soil Moisture 

## Ava Lomax
github: amlomax

### Summary
For this project I want to utilize NDVI data to assess vegetation health of an agricultural area (Merced, CA). I want to then complete an correlation analysis to determine the impact of Climate Smart initiatives. I am also comparing whether or not topographic differences influence the correlations. I am comparing 2017, 2020, and 2023. 

### Objectives
* Have NDVI as a foundation for agricultural management 
* Do a time series analysis 
* Get an understanding of the relation between vegetation stress and soil mangement 

### Datasets
* USGS Earth Explorer for Landsat images to use

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

