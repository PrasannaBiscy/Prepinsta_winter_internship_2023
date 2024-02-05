# FitBit Fitness Tracker App Analysis

## Project Overview

This project involves analyzing FitBit Fitness Tracker App data to gain insights into how consumers are using the FitBit app. The goal is to discover trends and insights that can inform the marketing team's strategies.

## Business Objectives

- Identify trends in FitBit app usage.
- Understand how identified trends may apply to customers.
- Provide insights to help influence the marketing strategy.

## Data Sources

The dataset was generated through a distributed survey via Amazon Mechanical Turk. It includes minute-level data for physical activity, heart rate, and sleep monitoring. The dataset is spread across 18 different files, including dailyActivity, dailyCalories, hourlySteps, etc.

## Data Cleaning and Manipulation

1. **Merging Data:**
   - Combined daily, hourly, and minutes activity data for a comprehensive analysis.
   - Separated datasets for daily activity, hourly activity, minutes activity, sleep data, weight log, and heart rate were merged appropriately.

2. **Handling Missing Values:**
   - Checked for and handled missing values in the dataset.
   - Imputed or dropped missing values as necessary.

## Analysis and Visualization

1. **Daily Activity Merged (EDA, Plots):**
   - Explored and visualized trends in daily activity.
   - Identified patterns, peaks, and variations in daily activities.

2. **Hourly Activity Merged (EDA, Plots):**
   - Analyzed and visualized hourly activity patterns.
   - Identified peak activity hours and overall trends throughout the day.

3. **Minutes Activity Merged (EDA, Plots) - Dashboard:**
   - Created a dashboard with filters for daily, hourly, and minutes activity.
   - Visualized minute-level data trends and provided interactive filters.

4. **Sleep Data (EDA, Plots):**
   - Investigated sleep patterns and durations.
   - Identified factors influencing sleep quality and duration.

5. **Weight Log (EDA, Plots):**
   - Analyzed weight log data for trends and changes.
   - Identified any correlations with activity or other variables.

6. **Heart Rate (EDA, Plots):**
   - Explored heart rate data for variations and trends.
   - Identified factors affecting heart rate and potential correlations.

## Deliverables

1. Clear summary of the business task.
2. Description of data sources used.
3. Documentation of cleaning and manipulation of data.
4. Summary of the analysis.
5. Supporting visualizations and key findings.
6. High-level content recommendations based on the analysis.

## Tools

- Python for data cleaning, transformation, visualization, and analysis.
- Pandas Profiling for a detailed analysis of the dataset.

