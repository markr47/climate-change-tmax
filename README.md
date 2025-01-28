
# Climate hange impacts on extreme temperatures

## Introduction

In this repository the impact of the observed climate warming of the last decades on local temperature
extremes in Germany is analysed. It contains three jupyter notebooks:

1.) data_preprocessing.ipynb  
In this notebook observations of maximum daily temperature (Tmax) are checked on consistency and pre-processed.

2.) data-analysis_Tmax.ipynb  
This notebook analysis timeseries of Tmax with respect to observed trends, frequency of occurences,
and heat waves.

3.) weather_types  
The aim of this notebook is to analyse the (thermo-)dynamic processes that led to the increase of
temperature extremes. Here, a weather type classification is performed using sea level pressure fields
from a reanalysis product.

## Datasets

The analysis is performed using the following datasets:

1.) Meteorological station data from the German Weather Service (DWD). These datasets are available
on the open data platform of the DWD (https://opendata.dwd.de/climate_environment/CDC/observations_germany/climate/daily/kl/).  

2.) Daily sea leve pressure from the reanalysis product ERA5 of the ECMWF (https://cds.climate.copernicus.eu/datasets/reanalysis-era5-single-levels).

## Analysis Overview

The notebook covers the following topics:

1. Data Cleaning and Preprocessing: Handling missing values, converting data types, and creating new columns for death rate and recovery rate.

2. Exploratory Data Analysis: Visualizing COVID-19 trends using bar charts, line plots, pie charts, and bubble charts.

3. Geospatial Visualization: Visualizing COVID-19 cases on a world map using Plotly's Choropleth.

4. Comparing Countries: Comparing COVID-19 statistics between different countries using side-by-side bar charts and box plots.

5. Heatmap: Creating a heatmap to show the correlation between confirmed, death, and recovered cases across different countries or regions.

6. Treemap: Visualizing countries with the highest active cases using Plotly's Treemap.

## Interactive Visualizations

The notebook uses Plotly and Plotly Express to create interactive visualizations. These interactive plots allow users to hover over data points, zoom in and out, and see detailed information on COVID-19 cases for each country.

## Instructions

1. Make sure you have Jupyter Notebook and the required libraries installed.

2. Clone or download this repository to your local machine.

3. Open the Jupyter Notebook file `https://github.com/Subiya101/COVID-19-Data-Analysis/tree/main`.

4. Run the notebook cells to see the visualizations and analysis results.

5. Feel free to explore and modify the code to perform additional analyses or customize the visualizations.

## Note

This analysis is based on the COVID-19 datasets available at the time of writing (up to September 2021). Newer data may not be included, so the analysis might not reflect the most recent COVID-19 statistics.

## License

This project is licensed under the [MIT License](LICENSE).

### Note about Visuals

Due to limitations in displaying dynamic content directly in the Jupyter Notebook on GitHub, some of the visualizations may not be visible in the notebook preview. However, you can find all the visualizations and interactive plots in the [Jupyter Notebook](https://github.com/Subiya101/COVID-19-Data-Analysis/blob/main/covid-19.ipynb) file.

In the Jupyter Notebook, you will be able to see the complete analysis, including all the charts and visuals that may not be visible in the GitHub preview. To view the notebook, click on the "Open in Jupyter Notebook" button above. Alternatively, you can download the notebook and run it on your local machine to view the visuals interactively.

For any questions or clarifications, feel free to reach out. Happy exploring!


## Introduction

This repository contains a Jupyter Notebook that performs data analysis on COVID-19 data. The notebook is written in Python using libraries like Pandas, NumPy, Seaborn, and Plotly. The analysis provides insights into COVID-19 cases, deaths, recoveries, and other related statistics for different countries.

## Datasets

The analysis is performed using the following datasets:

- **COVID-19 Clean Complete**: Contains COVID-19 data, including confirmed cases, deaths, recoveries, and more, by country/region and date.

- **Full Grouped**: Contains COVID-19 data grouped by date, country/region, and WHO region.

- **Worldometer Data**: Contains COVID-19 data, including total cases, new cases, total deaths, new deaths, total recoveries, and more, by country/region.

## Analysis Overview

The notebook covers the following topics:

1. Data Cleaning and Preprocessing: Handling missing values, converting data types, and creating new columns for death rate and recovery rate.

2. Exploratory Data Analysis: Visualizing COVID-19 trends using bar charts, line plots, pie charts, and bubble charts.

3. Geospatial Visualization: Visualizing COVID-19 cases on a world map using Plotly's Choropleth.

4. Comparing Countries: Comparing COVID-19 statistics between different countries using side-by-side bar charts and box plots.

5. Heatmap: Creating a heatmap to show the correlation between confirmed, death, and recovered cases across different countries or regions.

6. Treemap: Visualizing countries with the highest active cases using Plotly's Treemap.

## Interactive Visualizations

The notebook uses Plotly and Plotly Express to create interactive visualizations. These interactive plots allow users to hover over data points, zoom in and out, and see detailed information on COVID-19 cases for each country.

## Instructions

1. Make sure you have Jupyter Notebook and the required libraries installed.

2. Clone or download this repository to your local machine.

3. Open the Jupyter Notebook file `https://github.com/Subiya101/COVID-19-Data-Analysis/tree/main`.

4. Run the notebook cells to see the visualizations and analysis results.

5. Feel free to explore and modify the code to perform additional analyses or customize the visualizations.

## Note

This analysis is based on the COVID-19 datasets available at the time of writing (up to September 2021). Newer data may not be included, so the analysis might not reflect the most recent COVID-19 statistics.

## License

This project is licensed under the [MIT License](LICENSE).

### Note about Visuals

Due to limitations in displaying dynamic content directly in the Jupyter Notebook on GitHub, some of the visualizations may not be visible in the notebook preview. However, you can find all the visualizations and interactive plots in the [Jupyter Notebook](https://github.com/Subiya101/COVID-19-Data-Analysis/blob/main/covid-19.ipynb) file.

In the Jupyter Notebook, you will be able to see the complete analysis, including all the charts and visuals that may not be visible in the GitHub preview. To view the notebook, click on the "Open in Jupyter Notebook" button above. Alternatively, you can download the notebook and run it on your local machine to view the visuals interactively.

For any questions or clarifications, feel free to reach out. Happy exploring!