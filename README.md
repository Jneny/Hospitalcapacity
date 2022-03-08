# Predicting The Daily Occupancy Demands of Ontario's Critical Care Units During the Covid Pandemic
This repository includes the data, codes and documents for "Predicting The Daily Occupancy Demands of Ontario's Critical Care Units During the Covid Pandemic". 
Project is developed for the CIND 820 Big Data Analytics Project course.

The tentative stages of the project are as follows:
Step 1: The data is obtained from [Availability of adult and pediatric ICU beds and occupancy for COVID-related critical illness (CRCI)](https://data.ontario.ca/dataset/availability-of-adult-icu-beds-and-occupancy-for-covid-related-critical-illness-crci)
Step 2: I conducted transformations of data type, checks for missing values and subsetted the data to the relevant variables to clean the data for analysis.
Step 3:For the Exploratory Data analysis, I implemented graphing of the variable of interest, breaking it down to its components to check for trends, seasonality, and error, and 
Step 4:To preprocess the data for analysis I performed stationarity checks using Dickey-Fuller test and separated the data into training and test sets
Step 5:I implemented the following machine learning algorithms to train a model to fit on the train set and predict the test set as well as into the future and evaluted the accuracy of the prediction model as compared to the test set using MSE

# Objectives
The objectives of is project are:

- To explore and analyze hospital ICU occupancy during the pandemic in Ontario
- To identify patterns and trends in ICU hospitalizations along the progression of the virus
- To develop machine learning models that predict the daily occupancy demands of Ontario's critical care units using patterns found in earlier stages of the pandemic
- Provide recommendations for hospitals to increase their preparedness for high patient volumes and needs in the future

# Significance
By examining Ontario's availability of ICU beds and occupancy for COVID-related critical illness (CRCI) dataset, we will identify the important patterns and trends in ICU hospitalizations, and use machine learning models with which hospitals can use as a reference to modify their responses in anticipation of upcoming volumes. 

# Project Folder Directory
This project folder consists of the following sub-folders:

- Data contains the raw [Availability of adult and pediatric ICU beds and occupancy for COVID-related critical illness (CRCI)](https://data.ontario.ca/dataset/availability-of-adult-icu-beds-and-occupancy-for-covid-related-critical-illness-crci) data from the Ontario Ministry of Health and the subsetted data for machine learning
- Codes contains the Jupyter notebooks which have the codes for data cleaning, EDA, statistical inference and machine learning
- Technical Reports contains the technical reports in PDF format for my runs
- Documents contains the reports for each stage of the project such as abstract, literature review, and final report
- Results contains the results of the analysis
