# Chicago Crime Data Project

#### -- Project Status: Completed

## Project Intro/Objective
The purpose of this project is to take a look into crime data provided by the Chicago Police Department. The goal of this project is to try to find patterns in recorded incidents, charges, arrests, or a combination of the three that might have an effect on 
recidivism. 

### Partner
* Chicago Polie Department, Professor Zubin Jelveh, University of Maryland
* Partner contact: Professor Zubin Jelveh (zjelveh@umd.edu)

### Methods Used
* Inferential Statistics
* Exploratory Data Analysis
* Machine Learning
* Data Visualization
* Predictive Modeling
* Logistic Regression
* Random Forest Classifier

### Technologies
* Python
* Seaborn
* Scikit-learn
* Pandas, jupyter, numpy
* VSCode
* Github

## Project Description

Using steps provided by professor Jelveh, this project is a complete data science project from beginning to end. The datasets provided are sourced from the Chicago Police Department directly from their website (https://home.chicagopolice.org/).

I was prompted with providing deliverables to help choose between two programs aimed at reducing crime in the Chicago area. Is there information from the data that could hint to higher rates of rearrests? If I could find an answer to this question than it would be seemingly possible to find an optimal program that could help reduce crime rates.

The first steps after loading the data was to do exploratory data analysis - looking at recidivism within the Chicago area, as well as rearrests among different demographics. Next step was feature generation. Using the analysis in the previous step, I could create features: data points not given in the original data. In this case, creating a feature that indicated whether the incident was drug or alcohol related. A second feature was to indicate at what age an individual was first arrested. A follow up to feature generation is to see how well the features are related to the outcomes. This can be done through visualizations.

Once the features are generated, the models can be built. I first split the data into test/train, cleaned the data, then set up the parameters. For this project, I chose to use the Random Forest classifier model.

The final steps were to assess the model, then apply the model to the original hypothesis and create the deliverables. Overall this was a great project that dealt with real world data and gave great insight to how to build a data project from start to finish.

## Featured Notebooks/Analysis/Deliverables
* [chicago_crime_data_project.ipynb](https://github.com/mabail6/Chicago-Crime-Data-Project/blob/master/chicago_crime_data_project.ipynb)