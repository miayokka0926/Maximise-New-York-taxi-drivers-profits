# MAST30034 Project 1 - Insights on New York taxi drivers' profits maximisation
- Student Name: Yuxin Ma
- Student ID: 1067799

# Dependencies
- Language: _i.e Python 3.8.3 and/or R 4.05_
- Packages / Libraries: pandas, pyspark, folium, matplotlib, geopandas

# Datasets
a) NYC TLC: https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page 
  training dataset: 2018-01 - 2018-09
  test dataset: 2019-01
  features: 
b) External dataset 1: https://www.ncei.noaa.gov/orders/cdo/2676651.csv
c) External dataset 2(for testing): https://www.ncei.noaa.gov/orders/cdo/2684242.csv


# Directory
_Change this to fit your needs when you have started the project._
- `raw_data`: Contains all the raw data files. You may add this folder to `.gitignore` if your files are too large, but you **must** provide code to automatically download or links so that we may manually download them. 
- `preprocessed_data`: Contains all the preprocessed data files. You may add this folder to `.gitignore` if your files are too large, but your script should automaticaally generate files here given the correct dataset in `raw_data`.
- `plots`: Output and save all your figures here.
- `code`: Keep all notebooks and scripts in this folder. Ensure that you have notebooks for each _stage_ of code. Here's an example:
- `deprecated`: A folder to store "old code" that **you do not use anymore** or code that you experimented with, but decided to not go ahead. This is useful in case you ever need to come back to an older iteration of code or to express your other approaches to the problem.

# instruction for reading the notebooks
Before running any code, please download the data a), b), c) from specified source
I also put the external data into preprocessed_data folder. 
1. first pre-process data with "yellow data preprocessing.ipynb"
2. Then concat data month by month with "concat monthly data and seasonal visualisation.ipynb". There are several plots generated in this notebook, but they do not appear in the report.
3. run "visualisations with weather data set.ipynb", most plots appear here. This one is important since the sample data set generated here is used in the entire research proocess.
4. Then, the geo-map are plots in "geo-map visualisation.ipynb", I also use the sample set generated in setp 3 to plot.
5. Then "ads_model.Rmd", this one build the GLM and LM model.
6. Test data is generated in "Test set generation.ipynb"
