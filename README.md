# **Energy Consumption and Production Analysis, Predictions with Bayesian Model**

## Description

This project focuses on analyzing electricity consumption and production data in Romania, spanning from January 1st, 2019, to March 3rd, 2023. The primary goal is to understand energy trends and make informed predictions about future consumption and production patterns, particularly from renewable energy sources such as Hydroelectric and Wind power. A Bayesian modeling approach has been employed to tackle the uncertainty inherent in energy data and to provide a probabilistic framework for predictions.

## Dataset

The dataset is an hourly time series of electricity consumption and production, segmented by production types: Nuclear, Wind, Hydroelectric, Oil and Gas, Coal, Solar, and Biomass. Each row in the dataset represents a specific hour, detailing the total energy consumed and produced during these intervals, measured in Megawatts (MW).

## Analysis

The analysis involves:

- Exploratory Data Analysis (EDA) to understand the dataset's structure and characteristics.
- Visualization of electricity consumption trends over time.
- Comparative analysis of energy production from different sources, focusing on renewable (Wind, Hydroelectric, Solar, Biomass) versus non-renewable sources (Nuclear, Oil and Gas, Coal).

## Why Bayesian Model?

The Bayesian model was chosen for its robustness in dealing with uncertainties and its ability to incorporate prior knowledge into the analysis. This approach is particularly advantageous in scenarios where data might be scarce or noisy, as is often the case with energy consumption and production data. The Bayesian framework facilitates the estimation of distribution parameters and allows for more nuanced and probabilistic forecasting.

### Models Developed

- **Bayesian Model for Electricity Consumption**: Predicts future consumption patterns.
- **Bayesian Model for Hydroelectric Production**: Forecasts production from hydroelectric source.
- **Bayesian Model for Wind Production**: Forecasts future energy production from wind source.

## Conclusion

The project's findings highlight the significant contribution of renewable energy sources, particularly Hydroelectric and Wind power, to Romania's energy matrix. The Bayesian models developed provide a comprehensive understanding of energy consumption and production patterns, enabling more informed decision-making for energy management and production required from non-renewable sources.

The analysis shows that for the year 2024, Hydroelectric and Wind power together are expected to account for a substantial portion of the total energy production. This insight underscores the importance of investing in and focusing on renewable energy sources to meet future energy demands sustainably.
