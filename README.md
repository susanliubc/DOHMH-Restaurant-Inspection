# DOHMH-Restaurant-Inspection
Using Python (pandas and NumPy) and Power BI to analyze NYC DOHMH restaurant inspection results downloaded in Aug 4th, 2021

## ETL and data warehouse
The data source was downloaded from https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j as csv file. To clean the data, duplicated rows and records that were not in the range from 2016 to 2021 were removed before data processing.

Given the property of inspection, four dimension tables (restaurant, violation, inspection and date) and two fact tables (grade and visit) were built by extracting the data from source table as well as the table joins except the date demension table.

## Data visualization
Visualizations were carried out using Power BI bar chart, treemap and matrix to demonstrate detail analysis of violation type, restaurant, garde and scores.
