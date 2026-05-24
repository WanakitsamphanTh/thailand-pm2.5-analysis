# Bangkok PM2.5 Analysis

## Contents
- [Source](https://aqicn.org/city/bangkok/en/)
- [Data](#Data)
- [Correlation analysis](#Correlation-analysis)
- [Autocorrelation](#Autocorrelation)
- [Monthly and Seasonal distribution](#Monthly-and-Seasonal-distribution)
- [Forecasting with ARIMA](#Forecasting-with-ARIMA)

## Data
The data consist of PM2.5, PM10, O₃, and NO₂ concentrations measured from 2016-01-01 to 2026-05-01. The graphs below show the trends over the 10-year period. \
![graph](graphs/time-series.png) \
The following figures show boxplots for each pollutant concentration. \
![boxplot](graphs/boxplot-by-year.png) \
The pairplots below illustrate the relationships among the pollutants. From the graphs, it can be observed that all pollutants are positively correlated with one another. \
![pairplot](graphs/pairplots.png)

## Correlation analysis
As the results of correlation analysis, PM2.5 concentration correlates with PM10, O₃ and NO₂ concentrations positively with correlation coeffecients of 0.54, 0.51 and 0.4 respectively. No pollutants exhibit negative correlation with another. The correlation matrix is shown in the figure below. \
![correlations](graphs/corr-matrix.png)

## Autocorrelation
?

## Monthly and Seasonal distribution
?

## Forecasting with ARIMA
?
