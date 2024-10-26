# Air Quality Analysis in Seoul

## Overview
This project focuses on analyzing air quality in Seoul, utilizing data from two monitoring stations (Station 101 and Station 102). The analysis aims to understand the levels and trends of various pollutants, assess the impact of these pollutants on urban health, and identify correlations and insights to support environmental policy-making.

## Dataset
The dataset is sourced from [Kaggle’s Air Pollution in Seoul dataset](https://www.kaggle.com/datasets/bappekim/air-pollution-in-seoul/data) and includes the following parameters:
- **Pollutants**: SO2, NO2, O3, CO, PM10, PM2.5
- **Other features**: Measurement date, Station ID

## Project Structure
- **Data Cleaning**: Handled missing values, managed outliers, and formatted the measurement date to support time series analysis.
- **Statistical Summary**: Calculated mean, median, standard deviation, and variance for each pollutant across both monitoring stations.
- **Time Series Analysis**: Visualized pollutant levels over time using time series plots, with emphasis on peak hours.
- **Histograms**: Analyzed pollutant distributions, identifying positive skew for most pollutants, indicating more frequent lower concentration levels.
- **Correlation Analysis**:
  - Within-station correlations: Identified strong relationships between certain pollutants (e.g., PM2.5 and PM10).
  - Between-station correlations: Found high correlations for all parameters, suggesting consistent pollution patterns city-wide.

## Key Findings
1. **High Correlations in Particulate Matter**: PM2.5 and PM10 showed strong correlations within and across both stations, indicating similar emission sources like traffic.
2. **Distinct Behavior of Ozone (O3)**: Ozone exhibited weak correlations with other pollutants, pointing to secondary formation processes in the atmosphere.
3. **Consistent City-Wide Patterns**: High between-station correlations suggest similar air quality trends across Seoul, likely influenced by macro-level factors.

## Requirements
To run the analysis, you will need:
- Python with libraries: `pandas`, `matplotlib`, `seaborn`

## Usage
1. **Data Preparation**: Load and clean the dataset to handle missing values and format date columns.
2. **Statistical Analysis**: Run summary statistics and time series analysis scripts to analyze pollutant trends and correlations.
3. **Visualizations**: Generate time series, histograms, and correlation heatmaps for comprehensive insight into Seoul’s air quality.

## Insights and Implications
This analysis highlights critical pollution trends in Seoul and supports the need for targeted measures to control particulate matter emissions. Further studies could incorporate additional data sources and advanced modeling for more precise pollution source identification.

## Author
Dency Claris Thomas
