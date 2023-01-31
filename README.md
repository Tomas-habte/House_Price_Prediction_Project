# House Price Prediction Project
## Overview
As our final project, we have decided to predict house prices using historical data and machine learning. We chose this topic because the housing market is widely talked about, especially since the start of the COVID-19 pandemic. We also chose this topic because the housing market affects all of us in one way or another. Our analysis will help to answer two questions: how accurately can a model predict the sale price of a house and what are the most important features that can impact the price of a house? 

**Dataset**
- There are two datasets being used for this analysis: data on houses with their prices sold in Seattle, Washington, USA between August and December 2022 from Kaggle, and data on all houses in the United States with their zip codes and coordinates.
- The data on houses with their prices sold contains both training and testing data with columns 'beds', 'baths', 'size', 'size_units', 'lot_size', 'lot_size_units', 'zip_code', and 'price'. The target column is 'price' and the other columns are the features.
-  Fortunately, the data we found on Kaggle is well-structured (**link**: https://www.kaggle.com/datasets/samuelcortinhas/house-price-prediction-seattle). 
-  The main challenge we faced while choosing the dataset is that we could not find data on the topics we found most interesting, and the data we were able to find was complex and required a lot of cleaning. Therefore, we searched for data that was reasonably easy to work with. While our dataset only contained data spanning 5 months ending in Decemeber 2022, we wanted to use it as this was very recent and can give us good insights. 
-  For our second dataset, we were able to extract the coordinates for the houses in Seattle from Excel (**link**: https://www.listendata.com/2020/11/zip-code-to-latitude-and-longitude.html). Using VLOOKUP, we found the corresponding coordinates (‘lat’, ‘lon’) from the second dataset to the Zip Code in the first dataset (testing and training files)

| Final DataFrame | 
| ------------- |
|![Dataset](https://user-images.githubusercontent.com/111667387/215643247-da31c70f-86f3-4714-892b-ab6897e44dec.jpg)|


| Training File Data Types | Testing File Data Types |
| ------------- | ------------- |
| ![Datatypes 1](https://user-images.githubusercontent.com/111667387/215642689-87ad7c05-c850-4c8f-a192-e4f9667e257f.jpg)|![Datatypes 2](https://user-images.githubusercontent.com/111667387/215642736-b5fdb394-d9c9-40ec-9f32-da7410c99c73.jpg)|

**Technologies**
- Jupyter Notebook 
- Tableau
- Excel 

We are planning to visualize the data of our model in Tableau. Currently, we are working on a simple machine learning model to determine how it will work.
## Results


## Summary 
