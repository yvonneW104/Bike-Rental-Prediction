# Bike-Rental-Prediction

**Dataset:** https://archive.ics.uci.edu/ml/datasets/bike+sharing+dataset

**Introduction:**

There are usually two main question need to be solved for operating a bike-share system at local area. The first one is where to place the bike station and the second one is how many bikes to allocate at different time. Since the dataset provided by Capital bike share did not include the station location, so our main task in this project is to select the most optimal model to predict the number of bikes needed at different season, day, hour. 

To explore the dataset for building a better model. The following task will also be evaluated in this project. 
- outliers’ analysis
- correlation analysis
- Data visualization
- Calculate RMSLE value for each model

Since the count of bike is a huge number and we don’t want to penalize the huge difference when both predicted and actual values are large, we use the RMSLE to measure the ratio between actual and predicted value. 

**Models:**
- Linear Regression Model
- Ridge Regression Model
- Lasso Regression Model
- Random Forest
