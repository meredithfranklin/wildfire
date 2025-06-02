Wildfire Project

The aim of this summer project is to predict PM2.5 air pollution in British Columbia with wildfire information and meteorology. 

The dataset merged csv dataset contains 50 monitoring stations in BC with data collected between 2003 and 2020. These data have been spatially linked with satellite wildfire detections and smoke plumes from [NOAA HMS](https://www.ospo.noaa.gov/products/land/hms.html).

Goals:

- create summary statistics of the key variables (PM2.5, meteorology, heavy, medium, light smoke, distance to fire)
- create a table of PM2.5 concentrations under light, medium, and heavy smoke
- create a table to summarize how many smoke days per year
- create visualizations: maps, bar plots, box plots (concentrations by year, by smoke plume type)
- create feeatures for month, season, julian date, year
- machine learning models to predict PM2.5 (GAM, random forest, xgboost, neural network)
- focus on training and testing strategies (80-20 split, 10 fold, leave on site out)

