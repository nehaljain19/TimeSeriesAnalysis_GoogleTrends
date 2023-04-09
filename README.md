# TimeSeriesAnalysis_GoogleTrends

# The Goal: Better Understand Search Interest
The goal of this project is to assess and better understand the patterns of search interest we observe for Chipotle Mexican Grill.

Datasets used:
1. The weekly Google search interest for Chipotle using Google Trends (Chipotle Mexican Grill). 
2. The weekly adspend for Chipotle.

![image](https://user-images.githubusercontent.com/23355712/230747662-6bd95eba-e6a2-41ad-99b3-0092759f2d4b.png)

## Pull data using Google Trends

Use the Google trends GUI to pull 5 years of weekly trends data for Chipotle.

## The time series analysis

For your search interest data, you're going to fit two models. One using Facebook Prophet, and other using SARIMAX.
Fit a Prophet Model

Decompose your time series using facebook prophet. I'll ask you to translate the contents of this decomposed model in business terms:

    What is the overall trend? Is the search interest for your brand steadily growing?
    What does the seasonality look like for this brand?
        Look at weekly and monthly seasonality
            When does search interest peak?
            Why does search interest peak?
                Do some secondary research.
                    Does seasonality appear to be driven by the product or consumers? 

Then, create a forecast using Facebook's Prophet forecasting tool

Fit the model, and graph a residual plot. Then, answer the following questions:

    How good does the model seem to fit the training data?
    Are the residuals consistent across time? If not, why do you think it varies?

Use the tool to forecast next year's google's search interest. 

    Create a graph of the forecast
    What does the forecast predict
        Increased search interest
        Decreased search interest
    How certain does the prediction seem to be?

# SARIMAX Modeling

For your search interest data, fit an SARIMAX model using proper fit techniques taught in class. Fit at least one adspend variable as an exogenous regressor (X variable).
Fit Comparison

Compare absolute squared residuals of the Prophet and SARIMAX approach.

    Which model fits the data better?
    Do residuals seem to be more evenly distributed in one graph versus another?

Inspect your exogenous regressor (ad spend data)

    Does advertising expenditures improve the prediction of Google Search interest?



