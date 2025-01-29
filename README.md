# Climate change impacts on extreme temperatures

## Introduction

This repository analyzes the impact of the observed climate warming over the past decades on local temperature extremes in Germany. It contains three jupyter notebooks:

1. data_preprocessing.ipynb  
In this notebook, observations of maximum daily temperature (Tmax) are checked for consistency and pre-processed.

2. data-analysis_Tmax.ipynb  
This notebook analyzes pre-processed timeseries of Tmax with respect to observed trends, frequency of occurences, and heat waves.

3. weather_types  
The goal of this notebook is to analyse the (thermo-)dynamic processes that led to the increase of
temperature extremes. Here, a weather type classification is performed using sea level pressure fields
from a reanalysis product.

## Datasets

The analysis is performed using the following datasets:

1. Meteorological station data from the German Weather Service (DWD). These datasets are available
on the open data platform of the DWD (https://opendata.dwd.de/climate_environment/CDC/observations_germany/climate/daily/kl/).  

2. Daily sea leve pressure from the reanalysis product ERA5 of the ECMWF (https://cds.climate.copernicus.eu/datasets/reanalysis-era5-single-levels).


## Instructions

Make sure you have Jupyter Notebook and the required Python libraries (e.g. Pandas, sklearn, cartopy) installed, and clone or download this repository to your local machine. In case of errors related to the installation of Cartopy, ensure that the required shape files are downloaded to your local machine. For starters, I recommend running the three notebooks sequentially, using Tmax of station with ID 04336
(Saarbruecken). Feel free to experiment with data from other stations provided in this repository. Additional stations will be uploaded soon. If pre-processed data is available (files ending with *prepr.csv), you can skip ata_preprocessing.ipynb. 

## License

This project is licensed under the MIT-Licence.
