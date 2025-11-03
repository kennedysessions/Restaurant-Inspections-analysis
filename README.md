Analysis of Restaurant Inspection Data 

This repository contains data, analytic code, and findings from the New York City Health Department on inspection reports from roughly 40,000 establishments across New York City. 

Data

This analysis uses one spreadsheet of New York City Restaurant Inspection reports from NYC Open Data.
The spreadsheets come from the following sources:
New_York_City_Restaurant_Inspection_Results_20251101: Raw data of inspections

Each of the spreadsheets contains scores, inspection dates, zip codes, borough, census tract, and neighborhood tabulation, among others. The following columns are relevant to the analysis:
Zipcode— The zipcode of establishments 
Score— the score places received after the inspection 

Methodology

The notebook inspections.ipynb performs the following analyses:
Part 1: Find the zipcodes with the highest violations 
Group the zipcode and score columns, and then average the scores and rank them from highest to lowest
Calculate the highest average scores using .head and the lowest using.tail  

Outputs
The notebooks output this spreadsheet, which contains: each restaurant and its inspection score output/NYC inspections.csv.

Running the analysis yourself
You can run the analysis yourself. To do so, you'll need the following installed on your computer:

Python 3
The Python libraries specified in requirements.txt

Licensing
All code in this repository is available under the MIT License. The data file in the output/ directory is available under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. All files in the data/ directory are released into the public domain.

Feedback / Questions?
Contact Kennedy Sessions at kennedysessions42@gmail.com
