# Prescriptive Analytics Dashboard — Olist E-Commerce

A Power BI dashboard built as part of my MSc Business Analytics, using the Olist Brazilian e-commerce dataset to move beyond descriptive reporting into prescriptive, action-oriented analytics for customer retention and revenue growth.

🔗 **[View the live interactive dashboard](https://app.powerbi.com/view?r=eyJrIjoiYjE3YTRjMTUtNDc1Mi00OTIyLThjZjgtZTZlODg5ZmJjZTNmIiwidCI6IjEzZTNiMTg2LWM0NDYtNGFhYi05YzZkLTlhYjliYjc2ODE2YyIsImMiOjh9)**

## Overview

The dashboard combines predictive modelling with business decision rules to recommend specific retention actions, rather than just visualizing historical metrics.

## Key Features

- **XGBoost churn modelling** - predicts customer churn risk from transaction and behavioural data
- **RFM segmentation** - segments customers by Recency, Frequency, and Monetary value to identify high-value and at-risk groups
- **DAX rules engine** - a prescriptive layer built in DAX that translates model outputs and segments into recommended actions
- **Voucher ROI analysis** - evaluates the return on investment of voucher/discount campaigns across customer segments

## Screenshots

![Executive Overview](screenshots/01-overview.png)

![Churn Prediction & RFM](screenshots/02-churn-rfm.png)

![Voucher ROI Analysis](screenshots/03-voucher-roi.png)

![Category & Margin Analysis](screenshots/04-category-margin.png)

![Geographic Revenue Breakdown](screenshots/05-revenue-by-state.png)

![Customer Journey Funnel](screenshots/06-customer-funnel.png)

## Tech Stack

- Power BI (data modelling, DAX, visualization)
- Python (XGBoost for churn prediction)
- Olist Brazilian E-Commerce public dataset

## About

Built as part of my MSc in Business Analytics at the University of Galway.

**Author:** Mubeena Shaikh
