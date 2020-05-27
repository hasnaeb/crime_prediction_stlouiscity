# Crime prediction in St Louis City, Missouri

Based on a dataset containing crime information in St Louis, Missouri from 2008 to 2015, the project aims to predict which category of crimes is most likely to occur given a set of time and location features. Data cleaning notebook transforms raw data into two .npy files for attributes and class labels. Classification notebook explores different classification algorithms.

Then using LSTM architecture, the number of crimes per day per category is made based on the count for each of the previous 7 days.

Raw data can be found under the filename 'stl-crime-data_2008-2015.tsv' on https://data.world/kylesykes/st-louis-city-crime-data
