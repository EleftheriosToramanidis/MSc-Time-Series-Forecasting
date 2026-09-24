# Time-Series Forecasting in R

This repository contains a business-oriented time-series forecasting project completed as part of the MSc Business Analytics programme at the University of Bath.

## Project overview

The project has two parts:

1. Manual modelling of a quarterly M3 competition time series.
2. Batch forecasting across multiple quarterly time series.

The analysis compares regression, exponential smoothing and ARIMA-based approaches, evaluates model performance, and discusses the practical implications of forecast accuracy for business decision-making.

## Objectives

- Explore the characteristics of quarterly time-series data.
- Select and justify appropriate forecasting models.
- Diagnose model residuals.
- Produce forecasts with 80% and 95% prediction intervals.
- Evaluate forecasting accuracy using out-of-sample data.
- Compare selected models with benchmark methods.
- Translate the results into recommendations for a non-technical business audience.

## Tools and methods

- R
- R Markdown
- `Mcomp`
- `forecast`
- `tidyverse`
- Regression modelling
- Exponential smoothing
- ARIMA
- Residual diagnostics
- Forecast evaluation
- MAE and RMSE

## Repository contents

- `Part_1_Manual_Modelling.Rmd` — R Markdown source for the manual modelling analysis.
- `Part_1_Manual_Modelling.html` — rendered HTML report for Part 1.
- `Part_2_Batch_Forecasting.Rmd` — R Markdown source for the batch forecasting analysis.
- `Part_2_Batch_Forecasting.html` — rendered HTML report for Part 2.
- `Executive_Summary.pdf` — concise summary of the findings and managerial implications.

## Key skills demonstrated

- Time-series data exploration
- Statistical model selection
- Forecast generation
- Prediction intervals
- Residual diagnostics
- Out-of-sample model evaluation
- Benchmark comparison
- Business communication
- Reproducible reporting with R Markdown

## Reproducibility

To run the analyses, install the required R packages and open the relevant `.Rmd` file in RStudio. The HTML files are included as rendered versions of the reports.

Please note that the raw data files are not included in this repository. Users should obtain the relevant M3 data through the appropriate authorised source or R package.
