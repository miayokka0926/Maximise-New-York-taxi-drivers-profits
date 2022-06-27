# MAST30034 Project 1 - Insights on New York taxi drivers' profits maximisation
- Student Name: Yuxin Ma
- Student ID: 1067799

# Dependencies
- Language: _i.e Python 3.8.3 and/or R 4.05_
- Packages / Libraries: pandas, pyspark, folium, matplotlib, geopandas

# Datasets
1. NYC TLC: https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page 
  - training dataset: 2018-01 - 2018-09
  - test dataset: 2019-01
  - features: pickup datetime, drop-off datetime, pickup location, drop-off location, trip distance, passenger count, fare-amount, etc..
2. External dataset 1: https://www.ncei.noaa.gov/orders/cdo/2676651.csv
  - extreme weather data in NYC 2018-01 - 2018-09
4. External dataset 2(for testing): https://www.ncei.noaa.gov/orders/cdo/2684242.csv
  - extreme weather data in NYC 2019-01


# Directory

- `raw_data`: Contains all the raw data files.
- `preprocessed_data`: Contains all the preprocessed data files. 
- `plots`: All my figures in this project.
- `code`: Keep all notebooks and scripts in this folder.
- `deprecated`: A folder to store "old code" that **you do not use anymore** or code that you experimented with, but decided to not go ahead. 

# Objective
- To estimate NY yellow taxi drivers' tips amount for a trip with linear model, thus provide insights on profit maximization, including time and plance to pick-up customers, as well as other possible factors that matter.


# instruction for reading the notebooks
Before running any code, please download the data a), b), c) from specified source
I also put the external data into preprocessed_data folder. 
1. First pre-process data with "yellow data preprocessing.ipynb"
2. Then concat data month by month with "concat monthly data and seasonal visualisation.ipynb". 
3. Run "visualisations with weather data set.ipynb", most plots appear here. This one is important since the sample data set generated here is used in the entire research proocess.
4. Then, the geo-map are plots in "geo-map visualisation.ipynb", I also use the sample set generated in setp 3 to plot.
5. Then "ads_model.Rmd", this one build the GLM and LM model.
6. Test data is generated in "Test set generation.ipynb"
