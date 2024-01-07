# Data Analysis Project - Gun Incidents in the USA

## Project Information
- **Authors:** Patxi Juaristi and Marc Villalonga
- **Date:** 08-01-2024
- **Subject:** Data Mining

## Overview
This project involves a comprehensive data analysis using data mining tools, implemented in Python. The analysis covers four main topics: data understanding and preparation, clustering analysis, predictive analysis, and time series analysis. Each task is performed in different files and explained in detail in separate sections of the report.

## Objectives
Project focus is on gun incidents in the USA. The analysis aims to identify the most frequent characteristics of such incidents, analyze their common causes, study the evolution over the years, identify locations with the most frequent incidents, and explore participant characteristics. Additionally, the project aims to enrich the analysis by examining possible correlations with data from the USA congressional election results and poverty percentage data for each USA state and year.

## Files

```
.
├── 110m_cultural
│   └── ne_110m_admin_0_countries.shp           # Script used for geopandas library
│   └── ...
│
├── project_datasets
│   └── incidents.csv                           # Incidents dataset
│   └── incidents_v2.csv                        # Incidents v2 (Created after task 1)
│   └── incidents_v3.csv                        # Incidents v3 (Created after task 3)
│   └── povertyByStateYear.csv                  # Poverty dataset
│   └── povertyByStateYear_v2.csv               # Poverty v2 (Created after task 1)
│   └── year_state_district_house.csv           # Elections dataset
│   └── year_state_district_house_v2.csv        # Elections v2 (Created after task 1)
│
├── DM_16_TASK1 
│   └── DM_16_TASK1.ipynb                       # Data understanding and preparation
│
├── DM_16_TASK2 
│   └── DM_16_TASK2.ipynb                       # Clustering analysis
│
├── DM_16_TASK3
│   └── DM_16_TASK3.ipynb                       # Predictive analysis
│
├── DM_16_TASK4
│   └── DM_16_TASK4.ipynb                       # Time series analysis
└── ...
```

For the project delivery, project dataset folder will be empty, since the datasets can be download from the [web](http://didawiki.cli.di.unipi.it/lib/exe/fetch.php/magistraleinformatica/dmi/gun-data.zip) and copied to the folder.

## Data Sources
- Gun incident data in the USA
- USA congressional election results data
- Poverty percentage data for each USA state and year

## Tools and Technologies
- Programming Language: Python
- Data Mining Tools: *pandas, numpy, matplotlib, seaborn, scipy, geopandas, scikit-learn, kneed, tslearn, stumpy...*
