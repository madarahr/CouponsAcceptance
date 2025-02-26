# CouponsAcceptance

## Tools
Python

## Overview
This project aims to contextualize a scenario that a driver is driving through town and a coupon is delivered to their cell phone.  The coupons are issued for a bar, coffee house, restaurants that cost less than $20, retaurants costing $20-$50, and carry away.  Based on the followin attributes analysis is to be made on which of the categories accept the coupon.
- Gender
- Age
- Marital Status
- Number of children as passenger
- Education
- Occupation
- Annual Income
- Number of times the driver visits a bar within a month
- Number of times the driver buys takeaway food
- Number of times the driver goes to a coffee shop
- Number of times the driver eats at a cheap restaurant
- Number of times the driver eats in an average restaurant
- Driving destination
- Location of user
- Weather
- Temperature
- Time
- Passenger
- Time before coupon expires

## Extracting
Data is in the form of a .csv file and is located in the 'data' folder.  This data was extracted as a dataframe.

## Transform
Data was examined for NaN values and replaced with 0 where it made sense.  Dataframe was simplified further by removing the 'Car' column as it was irrelevant to this analysis.

## Load
Histogram Bar Plots were made using Seaborn for the coupons issued for various places.  Additional bar plot was made with Matplotlib to disect the data between accepted coupons and unaccepted coupons.
![image](https://github.com/user-attachments/assets/7caac3ae-6fba-471d-8161-aca6ae35c7df)

Histogram of the tepmerature was also made with Seaborn.  Additional bar plot was made with Matplotlib to disect the temperature data with weather.
The images of the bar plots were saved in the images folder.
![image](https://github.com/user-attachments/assets/72ca5b2b-e75e-4c77-b76a-6f092c06100b)


## Analysis
Exploratory analysis was made to compare criteria of who would accept bar coupons and simimarly for take away coupons.
