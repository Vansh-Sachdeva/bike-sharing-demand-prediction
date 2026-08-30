# Bike-Sharing Demand Prediction Using Linear Regression

**Roll No:** BTECH/25174/24
**Assignment:** Linear Regression Series

## Colab Notebook
[Open in Google Colab](https://colab.research.google.com/drive/1owQP7zT3sFNGFTt6EyrNhROUBbjetIF6?usp=sharing)

## Problem Statement
A city bike-sharing company needs to predict the number of bicycles that will be rented
at a particular time, to allocate bikes efficiently and reduce shortages.

## Dataset
UCI Bike Sharing Dataset (hourly data — hour.csv), 17,379 records from 2011-2012,
Capital Bikeshare, Washington D.C.
Source: https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset

## What's done in this project
- Data understanding and cleaning
- Exploratory Data Analysis (hourly/seasonal/weather patterns, correlation)
- Simple Linear Regression (using temperature) — both sklearn (OLSE) and Gradient Descent from scratch
- Multiple Linear Regression (using multiple features)
- Model comparison using MAE, RMSE, R2
- Actual vs Predicted visualization

## Key Findings
- Demand peaks around 8 AM and 5-6 PM (commute hours)
- Higher rentals in Summer/Fall, lower in Spring/Winter
- Temperature has a positive relationship with rentals
- Multiple Linear Regression performs better than Simple Linear Regression (higher R2)

## Files in this repo
- `Bike_Sharing_Assignment2_BTECH25174_24.ipynb` — main code notebook
- `hour.csv` — dataset
- `theory_notes.md` — formulas and references used

## How to run
Open the notebook using the Colab link above, or open the `.ipynb` file from this repo
in Google Colab, and run all cells top to bottom.
