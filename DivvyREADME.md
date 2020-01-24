# DIVVY Ridership Statistical Analysis By: Dan Corley, Ibrahim Patel, & Jeff Lindberg

## Executive Summary
We first gathered our data from a couple different sources such as the DIVVY and Open Weather Map API. With this data we began to answer the many questions we had about Divvy, and how Divvy's ridership is affected by weather. We found statistical differences in ridership due to temperature and weather.

## Contents
1. [Introduction](#introduction)
    - [Problem Statement](#problem_statement)
    - [Dataset](#dataset)
2. [Analysis](#analysis)
    - [Data Cleaning](#data_cleaning)
    - [Exploratory Analysis](#exploratory_analysis)
    - [Modeling](#modeling)

## Introduction <a name="introduction"></a>

### Problem Statement <a name="problem_statement"></a>
We formulated some hypothesis on some questions we came up. We used the data to answer the questions we had. Our hypothesis are:
H1: Bad weather affects the number of rides
H2: Bad weather affects customers more than subscribers
H3: Temperature affects the number of rides
H4: Customers ride less than subscribers in colder temperatures
H5: Stations see different ridership depending on weather.

### Dataset <a name="dataset"></a>
Open Weather Map API
https://openweathermap.org/api

Divvy Data
https://www.divvybikes.com/system-data

## Analysis <a name="analysis"></a>

### Data Cleaning <a name="data_cleaning"></a>

We merged 2 different dataframes, dropped null and missing values, and we dropped any duplicated or unwanted values. 

### Exploratory Analysis <a name="exploratory_analysis"></a>

We found that weather and temperature both have an effect on Divvy Bike Ridership. We also found out that Divvy is very seasonal as we saw the trends repeat themselves over the years. We also saw how different stations were affected by weather and temperature.

### Modeling <a name="modeling"></a>

We used Z test, T-Test, boxplots, and anova to find statistical significance and visualize our data.



