# Dairy Products Consumption Analysis (India, 2019-2022)

This repository contains a Python-based data analysis project focused on dairy product sales, pricing, revenue, and inventory patterns in India. The work is organized as a collection of Jupyter notebooks that clean data, explore relationships, and build statistical and machine learning models.

## Project Overview

The project uses an open-source dairy sales dataset to analyze:
- product and brand sales patterns
- pricing and revenue behavior
- inventory and stock-related trends
- clustering of similar observations
- regression and time-series analysis

The repository is primarily an analytics and experimentation project rather than a production web application or API service.

## Repository Structure

- data/
  - Original data/Dairy_dataset.csv: raw dataset
  - Prepared data/Cleaned_data.csv: cleaned data
  - Prepared data/Clusters.csv: clustered results
  - Prepared data/Dairy Data Cleaned.csv: prepared analysis dataset
- notebooks/
  - Dairy data cleaned.ipynb: data cleaning and preparation
  - Regression Analysis.ipynb: regression modeling
  - Regression analysis using r2 values.ipynb: additional regression evaluation
  - Time Series analysis.ipynb: time-series exploration
  - Unsupervised Machine Learning.ipynb: clustering with KMeans
- visualization/
  - charts and HTML outputs generated during analysis
- lib_version_check.py
  - simple script to verify installed Python data science library versions

## Dataset

The project uses an open-source dataset from Kaggle:
- https://www.kaggle.com/datasets/suraj520/dairy-goods-sales-dataset

## Tech Stack

- Python
- Jupyter Notebook
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- statsmodels

## Setup Instructions

1. Create and activate a Python environment.
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Start Jupyter:
   ```bash
   jupyter notebook
   ```
   or
   ```bash
   jupyter lab
   ```
4. Open the notebooks in the notebooks/ folder and run them in order.

## Requirements

The main Python dependencies are listed in requirements.txt and include:
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- statsmodels

## How to Use

- Begin with the cleaning notebook to understand the data preparation steps.
- Then explore the regression, clustering, and time-series notebooks.
- Review the visualization files in the visualization/ folder for generated charts and plots.

## Notes

- This repository is focused on analysis and reporting.
- There are no web APIs, databases, or deployment configurations in the current project structure.
- The notebooks rely on relative paths and are intended to be run from the project root.

## Future Scope

Potential next steps for this project include:
- expanding the analysis to more years or additional dairy product categories
- building a reusable data pipeline for cleaning and preparing the dataset automatically
- adding predictive models for demand, revenue, or stock forecasting
- creating interactive dashboards for business stakeholders
- integrating the analysis into a web app or reporting tool for easier access
