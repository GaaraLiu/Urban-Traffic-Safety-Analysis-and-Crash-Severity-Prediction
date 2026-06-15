# Urban Traffic Safety Analysis and Crash Severity Prediction

## Project Context

This project was completed as part of the National Student Data Corps (NSDC) Explorer Transportation Data Science Project between December 2024 and February 2025.

The research focused on understanding urban traffic safety patterns in New York City and exploring how machine learning can support data-driven transportation planning and safety interventions.

## Overview

Urban traffic safety remains a critical challenge for cities seeking to reduce injuries and fatalities while maintaining efficient mobility systems. This project investigates traffic crash patterns in New York City using machine learning and geospatial analytics to identify factors associated with severe crashes and evaluate the potential of predictive modeling for transportation safety planning.

By integrating exploratory data analysis, spatial analysis, and Random Forest classification, the project aims to provide data-driven insights that can support evidence-based transportation policy and urban safety interventions.

## Research Questions

- What factors contribute to severe traffic crashes in NYC?
- Which locations pose the highest risk for pedestrians and cyclists?
- Can machine learning accurately predict crash severity?
- How can data-driven insights improve transportation safety policies?

## Dataset

Source: NYC Open Data – Motor Vehicle Collisions Dataset

https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95/about_data

## Data Availability

This project was completed using a January 2025 snapshot of the NYC Open Data Motor Vehicle Collisions dataset.

The original dataset snapshot used for this analysis is no longer available in the author's archive.

Researchers interested in reproducing this work may obtain the latest version of the dataset from the link above.

Because the source database is continuously updated, reproduced results may differ slightly from those reported in the original project.

## Methods

- Data cleaning and feature engineering using Python and Pandas
- Exploratory analysis of temporal and spatial crash patterns
- Geospatial visualization of high-risk locations using GIS techniques
- Random Forest classification for crash severity prediction
- Feature importance analysis to identify key contributing factors
- Comparative evaluation of crash risk across different road users and locations

## Key Findings

- Fatal crashes were concentrated in Manhattan and Brooklyn.
- Pedestrian-involved crashes peaked during rush-hour periods, especially in busy commercial areas.
- High-risk cyclist corridors and intersections were identified.
- Vehicle type and time of day were among the most important predictors of crash severity.
- A Random Forest classifier achieved approximately 85% accuracy in predicting traffic crash severity categories.

## Research Contribution

This project demonstrates how large-scale urban transportation datasets can be combined with machine learning and spatial analytics to support transportation safety assessment. The workflow provides a reproducible framework for identifying high-risk locations and evaluating factors associated with crash severity, with potential applications in urban planning and transportation policy.

## Repository Contents

- `urban_traffic_safety_prediction.ipynb`  
  Jupyter Notebook containing data cleaning, exploratory analysis, geospatial analysis, and machine learning modeling.

- `traffic_safety_project_presentation.pdf`  
  Final project presentation summarizing research questions, methods, findings, and policy recommendations.

## Technologies

- Python
- Pandas
- NumPy
- Scikit-Learn
- GeoPandas
- Matplotlib
- Jupyter Notebook

## Author

LiShun (Gaara) Liu

M.S. Applied Urban Science and Informatics  
Center for Urban Science and Progress (CUSP)  
New York University (NYU)
