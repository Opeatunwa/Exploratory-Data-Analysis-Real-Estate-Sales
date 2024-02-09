Exploratory Data Analysis for Real Estate Dataset (2001-2020) Overview This repository contains code and documentation for performing exploratory data analysis (EDA) on a real estate dataset spanning from 2001 to 2020. The dataset provides information on various aspects of real estate transactions, property types across various towns over the specified time period.

Dataset Description Dataset Name: Real Estate Dataset Time Period: 2001-2020 Source: The Office of Policy and Management Variables: The dataset includes variables such as: Property type Town Assessed Value Sale Amount Sales Ratio List Year Date Recorded Address OPM Remarks Non Use Codes Assessor Remarks

File Structure: data/: This directory contains the raw real estate dataset file(s). notebooks/: This directory contains Jupyter notebooks for performing exploratory data analysis. README.md: This file provides an overview of the repository and instructions for running the code.

Project steps
1) Importing python libraries
2) Importing the Real Estate Data set into Python
3) Data Insoection- This is to understand the data ie first 5 rows, last 5 rows, shape of the data, data types, list of columns, check for duplicates and missing values. I visualized teh missing values using the Heatmap
4) Data Wrangling/Data Processing-identified the actions necessary to clean the data such as 
   -convert the 'Date Recorded' to a 'datetime' data type
   -convert the integer to categorical by replacing with 'unknown'
    -fill the missing values of 'Property Type' with its mode
   -fill the missing values of 'Residential Type' with its mode
    -replace missing values of 'Location', 'Non Use Code','Assessor Remarks' and 'OPM remarks' with 'unknown'
5)Data Manipualtion and Validation -above identified steps are carried out
6)Exploratory Analysis- Using visualization tools such as Bar Chart, Box Plot, Scatter Plot, Correlation matrix and Scatter Plot with Regression to analyse the 6 set objectives to provide insights
7)Expected Outcomes- Giving recommendations based on insights generated from the Exploratory Analysis.

Challenges include the following;
-how to handle missing data especially under Property Type, Non Use code, OPM remarks and Assessor Remarks as they were above 30% and therefore significant
-using the right visualization codes to generate insights
