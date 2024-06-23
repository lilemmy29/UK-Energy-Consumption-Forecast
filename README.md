# UK-Energy-Consumption-Forecast
This project forecasts UK energy consumption using historical data from smart meters, weather, and demographics. Utilizing machine learning models, it aims to provide accurate predictions for resource planning and efficient energy use. The dataset, sourced from Our World in Data, includes key metrics on energy consumption and mix.

## Project Description

This project forecasts future energy consumption in the UK using historical data from smart meters, weather conditions, and demographic information. By leveraging advanced machine learning models, we aim to provide accurate predictions to aid in resource planning, cost reduction, and promoting efficient energy usage across the UK.

## About Dataset

### Data on Energy by Our World in Data

Complete Energy dataset is a collection of key metrics maintained by Our World in Data. It is updated regularly and includes data on energy consumption (primary energy, per capita, and growth rates), energy mix, electricity mix, and other relevant metrics.

- **Variables**: The dataset includes variables related to energy consumption, energy mix, electricity mix, and other metrics of interest.

### Data Sources and Processing

The dataset is built upon multiple sources and processing steps:

- **Statistical Review of World Energy (Energy Institute, EI)**
- **International Energy Data (U.S. Energy Information Administration, EIA)**
- **Energy from Fossil Fuels (The Shift Dataportal)**
- **Yearly Electricity Data (Ember)**
- **European Electricity Review (Ember)**
- **Combined Electricity (Our World in Data based on Ember's data)**
- **Energy Mix and Fossil Fuel Production (Our World in Data)**
- **Primary Energy Consumption (Our World in Data)**
- **Electricity Mix (Our World in Data)**

Additional datasets and processing steps include:

- **Regions (Our World in Data)**
- **Population (Our World in Data)**
- **Income Groups (World Bank)**
- **GDP (University of Groningen GGDC's Maddison Project Database)**

### Changelog Highlights

- **July 7, 2023**: Replaced BP's data with the new Energy Institute Statistical Review of World Energy 2023.
- **June 1, 2023**: Updated Ember's yearly electricity data.
- **March 1, 2023**: Updated Ember's yearly electricity data and fixed minor issues.
- **December 30, 2022**: Addressed inconsistencies in BP's dataset.

### License

All visualizations, data, and code produced by Our World in Data are open access under the Creative Commons BY license. Data produced by third parties are subject to the original authors' license terms.

### Authors

- Hannah Ritchie
- Pablo Rosado
- Edouard Mathieu
- Max Roser

Our World in Data makes data and research on the world’s largest problems understandable and accessible. Read more about our mission on [Our World in Data](https://ourworldindata.org).

---

## Insights from the Project

1. **Seasonal Patterns**: Energy consumption exhibits clear seasonal patterns, with higher usage during colder months due to heating requirements.
2. **Demographic Influence**: Areas with higher population densities and urbanization levels tend to have higher energy consumption.
3. **Weather Impact**: Temperature and weather conditions significantly affect energy consumption, with colder temperatures leading to increased usage.
4. **Trend Analysis**: Long-term trends indicate a gradual increase in energy consumption, influenced by population growth and economic activities.
5. **Prediction Accuracy**: The SARIMA model provided accurate short-term forecasts, aiding in better resource planning and management.


## Notebook Contents

1. **Introduction**
   - Project Overview
   - Objective and Motivation

2. **Data Preprocessing**
   - Loading the Dataset
   - Data Cleaning and Preparation

3. **Exploratory Data Analysis (EDA)**
   - Visualizing Historical Energy Consumption
   - Analyzing Seasonal and Demographic Patterns

4. **Time Series Analysis**
   - Decomposing the Time Series
   - Model Selection and Evaluation

5. **Machine Learning Models**
   - Implementing SARIMA for Forecasting
   - Model Training and Testing

6. **Forecasting**
   - Generating Future Energy Consumption Predictions
   - Visualization of Forecast Results

7. **Conclusion**
   - Summary of Findings
   - Future Work and Recommendations
