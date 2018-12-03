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

We need json and geojson packags to 

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


Getting Started
------------------
1. Clone this repo
2. Download raw data [here](https://s3.amazonaws.com/tripdata/201810-citibike-tripdata.csv.zip) (the data is too big to upload on github)
3. Data processing - notebook in this repo


Contributors
------------------
|Name     |  
|---------|
|[Yichang Chen](https://github.com/[yichangchen1030])| 
|[Rui Han](https://github.com/[harry0107100]) | 
|[Jiahe Hou](https://github.com/[jiahehousherry]) | 
|[Dingran Lu](https://github.com/[LDRRRR]) | 
