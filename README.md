# Time-Series-Forecasting-Using-FbProphet
This project is based on time series forecasting of Sunspots using the FBProphet model.

The forecasting model should be able to predict the Sunspots (see below) by using Facebook’s Prophet Time Series Forecasting model. Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, daily seasonality. Sunspots are temporary phenomena on the Sun's photosphere that appear as spots darker than the surrounding areas. They are regions of reduced surface temperature caused by concentrations of magnetic field flux that inhibit convection. Sunspots usually appear in pairs of opposite magnetic polarity. Their number varies according to the approximately 11-year solar cycle.

Procedure
For each type of dataset that is daily, monthly and yearly we have created three separated models which are capable of predicting the sunspots in the future for upto 20 years. We have calibrated the models with time acquistion input which makes the model much more reliable due to removal of specific time input constraint. After that we have trained and tested the model based on all kinds of future predictions that are days, months and years with the three datasets.

To run the code using Daily Dataset;
Use the term 'daily_df' as directory.

To run the code using Month Dataset;
Use the term 'month_df' as directory.

To run the code using the Yearly Dataset;
Use the term 'year_df' as directory.
