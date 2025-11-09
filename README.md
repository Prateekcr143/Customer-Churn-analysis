# Customer-Churn-analysis


# Project Overview

This project performs an exploratory and analytical study of customer churn for a telecom (or subscription-based) business. The goal is to understand what drives customers to leave (“churn”), identify key patterns and segments, and provide actionable insights to reduce churn risk and improve customer retention.

# Problem Statement

Churn is a critical issue for businesses with recurring revenue models: retaining an existing customer is typically less expensive than acquiring a new one. By analysing historical customer data, this project aims to answer questions such as:

Which customer segments are most likely to churn?

What factors (demographics, contract type, service usage, payment method, etc.) are strong predictors of churn?

How can business stakeholders proactively identify at-risk customers and intervene accordingly?

Data Description

The dataset used is Customer Churn.csv. Key attributes include (but may not be limited to):

Customer demographic data (gender, age, etc.)

Service usage and account information (contract type, tenure, monthly charges, total charges)

Churn indicator (whether the customer has churned)

Payment method, service add-ons, etc.

The notebook (TCA.ipynb) performs data cleaning, exploratory data analysis (EDA), visualisations and segmentation analysis to derive insights.

# Methodology & Workflow

Data Loading & Cleaning – loading the CSV, handling missing values and formatting issues, converting data types appropriately.

Exploratory Data Analysis (EDA) – summarising distributions, identifying relationships between features and churn, using visualisations (histograms, bar plots, correlation heatmaps, etc.).

Segment Analysis / Feature Importance – segmenting customers by contract type, tenure, payment method, etc., and examining churn rates across these segments.

Insights & Recommendations – summarising actionable findings for retention strategies.

Executive Summary – a condensed PDF report (executive_summary.pdf) to present key results to stakeholders.

# Key Findings & Insights

Some of the major takeaways from the analysis (as reflected in the notebook and summary) include:

Contract type (e.g., month-to-month vs. long-term) shows strong association with churn.

Higher monthly charges or lower tenure often correlate with higher churn rates.

Usage of certain add-on services and payment methods may influence churn risk.

Customer demographics or service combinations reveal segments that require targeted retention strategies.

These insights can guide business actions such as offering incentives for customers in high-risk segments, redesigning contract offers, or improving service bundles to boost retention.

#Getting Started
Prerequisites
Python 3.x
Jupyter Notebook
Common data-science libraries: pandas, numpy, matplotlib, seaborn

# Usage

Open the TCA.ipynb notebook in Jupyter Notebook or JupyterLab.
Run the notebook cells from top to bottom.
Review the visualisations and the executive summary PDF for insights.
If you wish to extend the work, you can add predictive modelling (e.g., logistic regression, decision trees) to build a churn-predictive model.

# Authors 
Author: Prateek 
Thank you to any contributors, dataset providers or mentors who supported this work.

