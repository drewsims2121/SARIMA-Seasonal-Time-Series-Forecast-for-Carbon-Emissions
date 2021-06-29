# SARIMA-Seasonal-Time-Series-Forecast-for-Carbon-Emissions
SARIMA Time Series Seasonal Model for Forecasting Future Carbon Emissions

This dataset is from the Mauna Loa Observatory in Hawaii at a Latitude of 19.5 N and Longitude of 155.6 W. The elevation of the data is collected at 3397 m. The dataset measures the amount of In-situ CO2 in the atmosphere from 1958 to present time.

**The purpose of this project is to explore the trends of the CO2 time-series dataset, and forecast future predictions of CO2 levels.**

**The steps of this process include:**

**1.)** Loading in of necessary libraries

**2.)** Loading the csv data in

**3.)** Combining information from multiple columns to create a datetime64 index

**4.)** Determine if the data has seasonality or not

**5.)** Find optimal orders of SARIMAX parameters (P,D,Q)

**6.)** Train/Test Split Data

**7.)** Create model and fit model to data

**8.)** Predict Data

**9.)** Evaluate model performance metrics

**10.)** Forecast Future Predictions

**11.)** Observations
