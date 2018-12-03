# Analysis on Citi Bike Trips in NYC
- Group name: Tools 666         

Brief Description
-------------------
The motivation of this project is to improve the location of bike stations by find the least used bike station and the busiest bike station, and to find out the most used bikes and least used bikes to better reallocate them for efficiency. 


Package List
-----------------------
To install numpy package:
- !pip install numpy
- import numpy as np

Install pandas package to work on data frame:
- !pip install pandas
- import pandas as np

Use matplotlib and seaborn packages for plotting:
- !pip install matplotlib
- import matplotlib.pyplot as plt
- !pip install seaborn
- import seaborn as sns

We need json and geojsonio packags to do geospacial plotting:
- !pip install json
- import json 
- !pip install geojsonio
- import geojsonio

To deal with date objects:
- !pip install datetime
- import datetime

folium is installed to draw heat map:
- !pip install folium
- import folium

To cunstruct network of the bikes, we need to install networkx:
- !pip install network
- import network as nx

To analyze centrality of stations, we need import two functions and collections package
- from networkx.algorithms import closeness_centrality
- from networkx.algorithms import communicability
- !pip install collections 
- import collections

For machine learning part, package sklearn is used:
- !pip install sklearn 
- import sklearn

To check the statistical results of regressions, install:
- !pip statsmodels.api 
- import statsmodels.api as sm

To keep the plots showing inline of the Jupyter Notebook:
- %matplotlib inline

Methods Used
------------
- Data Visualization 
  - **Histogram**, **bar chart**, **line chart** on the relationship between time and distance, and give rush hour speed on a day.
  - **Dynamic heat map** to provide a dynamic view of the frequency of bike station using on a weekday per hour. 
  - **GeoJSON** to provide detailed information about a given bike station on the map
- Predictive Modeling
  - **Multiple linear regression**, **polynomial regression** to find out factors affecting trip duration and give a prediction of trip duration. Factors include distance, latitude and longitude of start and end bike station, etc. 


Preview of important results 
------------------
- Dynamic heat map is [here](https://s3.amazonaws.com/tripdata/201810-citibike-tripdata.csv.zip) !
- Bar charts shows the different time schedule of subscriber(mainly local residents with annual pass) and customer(mainly travells) on weekdays.
 <img src="https://github.com/harry0107100/Tools666/blob/master/Screen%20Shot%202018-12-02%20at%209.16.30%20PM.png?raw=true" width="500" height="200">
 <img src="https://github.com/harry0107100/Tools666/blob/master/Screen%20Shot%202018-12-02%20at%209.16.37%20PM.png?raw=true" width="500" height="200">
 
 

Getting Started
------------------
1. Clone this repo
2. Download raw data [here](https://s3.amazonaws.com/tripdata/201810-citibike-tripdata.csv.zip) (the data is too big to upload on github)
3. Data processing - notebook in this repo


Contributors
------------------
|Name     |  
|---------|
|[Yichang Chen](https://github.com/yichangchen1030)| 
|[Rui Han](https://github.com/harry0107100) | 
|[Jiahe Hou](https://github.com/jiahehousherry) | 
|[Dingran Lu](https://github.com/LDRRRR) | 
