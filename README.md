# DOHMH-Restaurant-Inspection
Using Python (pandas and NumPy) and Power BI to analyze NYC DOHMH restaurant inspection results downloaded in Aug 4th, 2021

## ETL and data warehouse
The data source was downloaded from https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j as csv file. To clean the data, duplicated rows and records that were not in the range from 2016 to 2021 were removed before data processing.

Given the property of inspection, four dimension tables (restaurant, violation, inspection and date) and two fact tables (grade and visit) were built by extracting the data from source table as well as the table joins except the date demension table.

## Data visualization
Visualizations were carried out using Power BI bar chart, treemap and matrix to demonstrate detail analysis of violation type, restaurant, garde and scores.

Critical violation type and counts:
![critical violation](https://github.com/susanliubc/DOHMH-Restaurant-Inspection/blob/main/Critical%20violation%20analysis.png)

Non critical violation type and counts:
![Non critical violation](https://github.com/susanliubc/DOHMH-Restaurant-Inspection/blob/main/Non%20critical%20violation%20analysis.png)

Restaurant violation counts:
![restaurant violation](https://github.com/susanliubc/DOHMH-Restaurant-Inspection/blob/main/Restaurant%20violation%20analysis.png)

Critical violation type treemap:         

![critical violation type](https://github.com/susanliubc/DOHMH-Restaurant-Inspection/blob/main/Critical%20violation%20main%20type%20analysis.png)

Action, grade and score counts:
![action grade score](https://github.com/susanliubc/DOHMH-Restaurant-Inspection/blob/main/Action%2C%20grade%20and%20score%20analysis.png)

Violation score, percentage of violation and action:
![violation code score and percentage of violation and action](https://github.com/susanliubc/DOHMH-Restaurant-Inspection/blob/main/Violation%20code%20score%2C%20percentage%20of%20violation%20and%20action.png)

Citation and inspection:
![citation and inspection](https://github.com/susanliubc/DOHMH-Restaurant-Inspection/blob/main/Citation%20and%20inspection.png)

Inspection type, grade and score:
![inspection type grade and score](https://github.com/susanliubc/DOHMH-Restaurant-Inspection/blob/main/Inspection%20type%2C%20grade%20and%20score.png)
