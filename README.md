# Modeling the Influenza Virus for 2022-2023

## Project Overview

This project analyzes influenza transmission and vaccination dynamics during the 2022-2023 season using CDC data and the SIR (Susceptible-Infected-Recovered) epidemiological model. The project develops a baseline SIR model, refines it to integrate vaccination data, and explores the impact on disease containment.

## Key Features

1. Baseline SIR model using infection data
2. Optimized SIR model with curve fitting
3. SIR model incorporating vaccination data
4. Comparison of flu spread between states (Florida and Massachusetts)

## Data Sources

- CDC clinical data on weekly number of positive cases and total specimens tested
- CDC data on cumulative flu vaccine doses distributed
- CDC data on weekly cumulative influenza vaccination coverage by state

## Methods

- SIR model implementation
- Parameter optimization using scipy.optimize's curve_fit function
- Root Mean Squared Error (RMSE) for model evaluation

## Key Findings

- Significant reduction in RMSE from baseline to optimized model
- Further reduction in RMSE when incorporating vaccination data
- Insights into transmission and recovery rates
- State-level comparisons revealing unexpected patterns in infection rates and vaccination coverage

## Limitations

- Data quality and availability constraints
- Lack of consideration for behavioral factors and population heterogeneity

## Future Work

- Incorporate more complex modeling frameworks (e.g., SEIR model)
- Improve data quality and availability
- Integrate behavioral and socio-economic factors
- Explore advanced models such as Agent-Based Models and Seasonal ARIMA models

## Collaborators 

- Samia Afrose
- Mari Kikuta

## Acknowledgements

This project was completed as part of Applied Math 115 at Harvard University.
