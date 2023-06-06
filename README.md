# Web Traffic Time Series Forecasting
 
# Introduction

The web traffic is basically the number of sessions in a given time frame, and it varies a lot with respect to what time of the day it is, what day of the week it is, and so on, and how much web traffic of platform can withstand depends on the size of the servers that are supporting the platform.
If the traffic is more than what the servers can handle, the website might show this 404 error, which is something we don’t want to happen. It will make the visitors go away.. This is where forecasting is needed.

A simple example of time series is the amount of year-on-year passenger traffic in the U.S. Formally, time series is just a series of data points arranged in time order or in sequence commonly taken us successive, equally spaced points time.

# Dataset
I have worked with the web traffic dataset. It is a six-month series data set the link is given here[https://www.kaggle.com/datasets/kajal1/web-traffic-forecast-dataset].

# Objectives

Identifying the nature of the phenomenon by establishing a pattern
Forecasting future values.
No low latency requirements but shouldn’t take days.

# Procedure

We will deep dive into the web traffic data set and look at how we can use LSTM(Long Short Term Memory) to solve this time series forecasting problem.

# Conclusion
The forecasted values are almost close to the actual values using LSTM Model. However the model can be improved if we try to change the learning rate.
