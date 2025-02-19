# Diabetes Data Engineering Comprehensive Analysis

## Overview
This project conducts a thorough analysis of the Diabetes dataset from the UCI repository, which encompasses data from 130 US hospitals between 1999 and 2008. The project's goal is to uncover significant patterns and insights through robust data engineering techniques including data cleaning, statistical analysis, and advanced visualizations.

## Objectives
- **Visualize and understand relationships** within the dataset through comprehensive plotting.
- **Identify predictive attributes** that could aid in future medical studies or treatments.
- **Enhance data quality** by addressing issues like missing values, outliers, and redundancies.

## Files
### diabetes_data_engineering_part_1.py
- **Visualizes each attribute**: Generates histograms, box plots, and scatter plots to reveal distribution and relationships.
- **Target attribute identification**: Analyzes potential target variables for prediction based on the dataset's characteristics and clinical relevance.

### diabetes_data_engineering_part_2.py
- **Missing data analysis**: Classifies missing data into MCAR, MAR, and MNAR, providing a basis for informed imputation strategies.
- **Statistical significance analysis**: Evaluate each attribute using statistical metrics to determine their impact and relevance in the dataset.
- **Redundancy elimination**: Identifies and removes highly correlated attributes to simplify the model without sacrificing accuracy.

### diabetes_data_engineering_part_3.py
- **Data cleaning**: Outlines strategies for handling outliers and missing data, either through removal or imputation, and rationalizes these choices.
- **Data transformation**: Applies normalization, encoding, or other transformations to make the data suitable for analysis.
- **Re-analysis and final plotting**: Post-cleaning, conduct a second round of analysis to validate changes and update visualizations accordingly.
- **Data profile creation**: Develops comprehensive profiles for each attribute, detailing their role, statistics, and any transformations applied.

