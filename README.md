# West Nile Virus

In disease prevention, ease and quick detection are essential to avoiding a health crisis.  
This is a project that seeks to predict where in Chicago the outbreaks of the West Nile Virus will take place. 
The data is collected by health officials at the Health Department in Chicago. 
Moreover, there are also weather data and GIS (mosquito spraying) data.  

In this project, we will use the weather data to make predictions on where the West Nile Virus will turn up in Chicago, Illinois. 

Here is how to navigate the files in this repository:

1. Project-Writeup-Part2 - This file gives you some information about the project. It provides a description of the problem, the dataset, as well as some of my questions throughout the process. 
2. Data-Exploration-Preliminary - This file begins the process of loading the data into the dataframe for analysis. 
3. EDA (Exploratory Data Analysis) - This file does an in-depth processing of the weather data and the main dataset. Moreover, some background statistics like mean, median, and mode and the correlations were run. 
4. Date_Analysis - This file contains a brief analysis of dates in the dataset. A time series was not used because the dataset contains data from summer months and so seasonal changes cannot be oberved and since the timeframe is small, there is little reason to use it in the analysis. 
5. Visualization-Heat+Map - This file contains some visualizations of Temperature, Heat, as well as a map of where the virus is present based on the training data.
6. TestData - Similar to the train dataset, the test data was processed into a dataframe. 
7. Random_Forest_Baseline - A baseline model was obtained first with Random Forest just to get an idea of what the accuracy and feature importances look like. 
8. Modeling-Data - This file contains a test of pulling in other files with a script. 
9. Modeling_Part_1 - This file contains the first part of the modeling, analysis, parameter tuning...
10. Modeling_Part_2 - This file contains a second part prepared using the LabelEncoder. 
11. Geographic_Analysis - To visualize the results, the predicted results were plotted on the map. 
