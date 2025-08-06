# COVID-19 and Income Analysis in Kentucky

## Objective
Socioeconomic factors have long been linked to disparities in health outcomes across the United States. Communities with lower income levels often experience reduced access to healthcare, higher rates of chronic illness, and increased vulnerability during public health crises. This project aims to explore whether that trend holds true in Kentucky by analyzing the relationship between county-level median household income and the impact of COVID-19.

This analysis compares COVID-19 cases and deaths across all Kentucky counties, grouped into three income tiers based on median household income. The objective is to discover any patterns or associations between income level and COVID-19 outcomes through data visualizations.

## Getting Started

+ Fork the repo and clone it to your own computer
+ Load the clone in your code editor
+ Create and activate a virtual environment in that folder
+ Install the "requirements.txt" file
+ Run "covid_analysis.ipynb"


## Virtual Environment Commands 
| **Command** |           **Windows**                 |            **Linux/Mac**             | 
| ----------  | ------------------------------------- | ------------------------------------ |
|  Create     |    `python -m venv venv`              |   `python3 -m venv venv`             |
|  Activate   |    `source venv/Scripts/activate`     |   `source venv/bin/activate`         |
|  Install    |    `pip install -r requirements.txt`  |   `pip install -r requirements.txt`  |
|  Deactivate |    `deactivate`                       |   `deactivate`                       |

## Project Overview
This project explores the relationship between median household income and COVID-19 impact across Kentucky counties. By merging datasets on county-level COVID-19 cases, deaths, and income levels, the project analyzes whether lower-income areas experienced higher case and death rates from 2020-2022. This project intends to:

+ Clean and prepare the data to confirm it's accurate, consistent, and ready to analyze
+ Combine three different datasets using a shared column (county name) to bring all the data together.
+ Use the combined data to explore whether there’s a connection between income levels and how COVID-19 affected each county.
+ Calculate COVID-19 case and death rates per 1,000 people to fairly compare counties of different population sizes.
+ Categorize counties into income tiers (low, middle, high) to better understand how different economic groups were affected. 
+ Create easy to read visualizations to help uncover patterns or trends between income and COVID-19 cases and deaths.

## Project Summary

This project set out to explore whether there was any noticeable relationship between a county’s median household income and its experience during the COVID-19 pandemic in Kentucky. By combining publicly available data on COVID-19 cases and deaths with income and population data, the analysis aimed to uncover whether income levels influenced the impact of the virus.

Through data cleaning and SQL-based merging, each county’s COVID-19 data was matched with its median income and yearly population estimates. The analysis grouped counties into income tiers and examined both total and per capita cases and deaths from 2020 to 2022.

**Key Findings:**

+ Kentucky counties with different income tiers experienced varying COVID-19 case and death rates per 1,000 people. 
    + Income Tier - cases per 1000 people
        + Low Income: 125.56 cases per 1000
        + Middle Income: 103.74 cases per 1000
        + High Income: 100.99 cases per 1000
    
    +Income Tier - deaths per 1000 people
        + Low Income: 1.93 deaths per 1000
        + Middle Income: 1.58 deaths per 1000
        + High Income: 1.06 deaths per 1000



## Technologies Used
+ **Python** - Primary coding language used for this project
+ **VS Code** - Used as the main code editor for managaing files, running scripts, and editing notebooks
+ **Jupyter Notebook** - Used to create code, equations, visualizations, and explanatory text
+ **Pandas** - Used to load, clean, and manipulate data acros multiple datasets
+ **SQLite (sqlite3)** - Enabled SQL based joins for cleaner merging of data tables
+ **Matplotlip** - Created clear visualizations from the cleaned data for analysis
+ **Git** - Used for version control to track changes to code and manage development history
+ **GitHub** - Used to store and share the project repository, amking the code and documentation accessible for review and collaboration.

