# Fulfillment Rate Analysis for Supply Chain Optimization

## Overview
This project analyzes the fulfillment rate for Supply Chain Optimization, with a current rate of **73.65%**, which is below industry benchmarks. The goal is to identify possible factors driving low fulfillment rates using available operational data.

## Dataset
- **Source:** [Kaggle - Supply Chain Data](https://www.kaggle.com/datasets/harshsingh2209/supply-chain-analysis)
- **Key Features:** Order Quantities, Stock Levels, Availability (used as proxy for fulfillment), Lead Time, Shipping Time.

## Tools & Libraries
Python, Pandas, Matplotlib, Seaborn, Looker Studio (Google Data Studio)

## Key Insights
- **No strong relationship** between fulfillment rate and lead time.
- **High stock levels don’t guarantee** high fulfillment — e.g., stock levels of 80 and 60 still showed low fulfillment rates (10.4% and low teens).
- **Shipping time** also shows no clear link to fulfillment.
- Correlation values between fulfillment rate and the tested factors are below **1%**.
- A likely driver could be **low warehouse or order processing utilization**, which could not be tested with the available dataset.

## Dashboard
[**View Interactive Dashboard on Looker Studio**](https://lookerstudio.google.com/reporting/d66c89c4-75d7-49a8-b05b-cd51bcda3ba7)

![Dashboard Preview](Dashboard_Preview.png)

## Project Files
- [Notebook](fulfillment-rate-analysis-in-a-beauty-supply-chain.ipynb)
- [Presentation](Fulfillment%20Rate%20Analysis%20in%20a%20Beauty%20Supply%20Chain.pptx)

## Author
Ahsan Mubarak
