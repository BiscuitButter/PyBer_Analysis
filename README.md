# Ride Sharing Analysis

## Overview of Project

Analysis of ride-sharing data.

## Purpose

The purpose of this analysis is to create a summary of ride-sharing data by city type.

## Results

Based on the table below, a correlation can be seen between ridership and population density. We can also see a scalar correlation between drivers and population density, however, it does not align with ridership and the result is an excess of drivers to riders. This imbalance makes driving in high population areas much less lucrative.

##### Ride-Sharing Summary (Jan - Apr)
| | Rides by City Type | Drivers by City Type | Fares by City Type | Average Fare per Ride | Average Fare per Driver |
| :--- | :---: | :---: | :---: | :---: | :---: |
|Rural   | 125 | 78 | $4,327.93 | $34.62 | $55.49 |
|Suburban| 625 | 490 | $19,356.33 | $30.97 | $39.50 |
|Urban	 | 1625 | 2405 | $39,854.38 | $24.53 | $16.57 |

##### Fare Summary
![Fare Summary](https://github.com/BiscuitButter/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

## Summary

Drivers in the urban environment are earning considerably less than their counterparts in rural and suburban settings because there are simply too many of them. Setting a cap on how many drivers are allowed to operate will increase the average fares per driver. Alternatively, promoting urban ride-sharing may help alleviate the rider shortage.
