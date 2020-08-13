# Food-Demand-Forecasting-Analytics-Vidhya
A food demand forecasting challenge was hosted by Analytics Vidhya in which we got placed in the top 50 out of 1433 participants. The challenge was to help a food delivery business forecast the food demand for the upcoming weeks so that they can plan the stock of raw materials efficiently.

## Overview
Demand forecasting is a key component to every growing online business. Without proper demand forecasting processes in place, it can be nearly impossible to have the right amount of stock on hand at any given time. A food delivery service has to deal with a lot of perishable raw materials which makes it all the more important for such a company to accurately forecast daily and weekly demand.

Too much inventory in the warehouse means more risk of wastage, and not enough could lead to out-of-stocks — and push customers to seek solutions from your competitors. In this challenge, get a taste of demand forecasting challenge using a real dataset.

## Problem Statement
Your client is a meal delivery company which operates in multiple cities. They have various fulfillment centers in these cities for dispatching meal orders to their customers. The client wants you to help these centers with demand forecasting for upcoming weeks so that these centers will plan the stock of raw materials accordingly.

The replenishment of majority of raw materials is done on weekly basis and since the raw material is perishable, the procurement planning is of utmost importance. Secondly, staffing of the centers is also one area wherein accurate demand forecasts are really helpful. Given the following information, the task is to predict the demand for the next 10 weeks (Weeks: 146-155) for the center-meal combinations in the test set:

Historical data of demand for a product-center combination (Weeks: 1 to 145) Product(Meal) features such as category, sub-category, current price and discount Information for fulfillment center like center area, city information etc.

## Meta Data
Weekly Demand data (train.csv): Contains the historical demand data for all centers, test.csv contains all the following features except the target variable

Variable Definition<br>
id - Unique ID <br>
week - Week No <br>
center_id - Unique ID for fulfillment center <br>
meal_id Unique - ID for Meal <br>
checkout_price - Final price including discount, taxes & delivery charges <br>
base_price - Base price of the meal <br>
emailer_for_promotion - Emailer sent for promotion of meal <br>
homepage_featured - Meal featured at homepage <br>
num_orders (Target) - Orders Count<br>

fulfilment_center_info.csv: Contains information for each fulfilment center

Variable Definition<br>
center_id - Unique ID for fulfillment center<br>
city_code - Unique code for city <br>
region_code - Unique code for region <br>
center_type - Anonymized center type <br>
op_area - Area of operation (in km^2)<br>

meal_info.csv: Contains information for each meal being served

Variable Definition<br>
meal_id - Unique ID for the meal <br>
category - Type of meal (beverages/snacks/soups….)<br>
cuisine - Meal cuisine (Indian/Italian/…)<br>

## Evaluation metric
100*RMSLE

## Submission Score
49.79
