# Op.-Management
There are 3 problems on this assignment. The main focus is to sort out the basics of forecasting.

The purpose Problem 1 is to show you how one can create probabilistic forecasts based on historical data – and then evaluate the out-of-sample performance of the resulting models.
We have a dataset that represents the annual sales data for 80 retail products. We assume no demand values were censored, meaning that the sales are exactly equal to the demand. We use the historical data for years from 2010 to 2018 for estimation, and forecast the outcome for the year 2019. Let t denote a time period. For each product, we consider the following two models (assuming that εt are standard Gaussian random variables independent over products and time periods, and μ and σ are the parameters to estimate):
1. IID Gaussian model: Dt = μ + σεt.
2. AR(1) Gaussian model: Dt = μ + φDt−1 + σεt.

The purpose of Problem 2 is to show how the disagreement between experts is related to the forecasting accuracy, and how the data on the historical performance of such experts can be used to improve the quality of probabilistic forecasts.

Problem 3 deals with the data from IARPA’s 4-year geopolitical forecasting tournament. The data presents information for several dozens of individual forecasting problems (IFPs) and the expert predictions that were made 30 days before the outcome became known. The experts are split into two groups: “regulars”, who were not specificially selected or trained, and who were working individually, and “superforecasters”, who were shown to be the top forecasters in one of the previous years, and who worked together in teams. Sheet 3 presents the information on IFPs (IFP_ID being a unique identifier of a forecasting problem) and expert inputs. For expert inputs, each row represents a prediction for a given event by a given expert. 
