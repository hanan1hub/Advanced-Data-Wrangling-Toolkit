# Exploratory Data Analysis and Preprocessing Pipeline

## 📌 Project Overview
This project demonstrates an end-to-end data preprocessing and Exploratory Data Analysis (EDA) pipeline. It focuses on cleaning, wrangling, and visualizing raw data to extract meaningful statistical insights. The repository utilizes two distinct datasets to showcase different analytical techniques, including missing value imputation, feature engineering, and outlier detection.

**Author:** Hanan Majeed

## 📊 Datasets Analyzed
* **Titanic Passenger Dataset:** Utilized for demographic analysis, survival rate correlation, and categorical feature engineering.
* **Airbnb Pricing Dataset:** Utilized specifically for numerical distribution analysis and anomaly/outlier detection in market pricing.

## 🚀 Core Features & Methodology

### 1. Data Ingestion & Auditing
* Implemented robust data loading mechanisms using Pandas.
* Conducted initial data audits to inspect schemas, data types, and summary statistics.
* Evaluated missing data points (e.g., Age, Cabin, Embarked variables) and formulated strategies for data retention versus imputation.

### 2. Data Wrangling & Feature Engineering
* **Imputation:** Systematically handled missing numerical values using median-based imputation to preserve data distribution integrity.
* **Data Transformation:** Filtered noisy data (e.g., zero-value fares) and extracted specific demographic subsets for targeted analysis.
* **Feature Creation:** * Engineered a synthetic `family_size` feature by aggregating sibling/spouse and parent/child data.
  * Derived a boolean `travel_alone` feature to analyze independent traveler statistics.

### 3. Statistical Visualization & Analysis
* **Categorical Insights:** Generated comprehensive visualizations of survival probabilities across different demographics and socio-economic classes.
* **Distribution & Outliers:** * Modeled age distributions using histograms with central tendency overlays.
  * Deployed box plots on the Airbnb dataset to visually isolate pricing outliers and market anomalies.
* **Correlation Modeling:** Computed a correlation matrix and visualized feature relationships using a Seaborn heatmap to drive predictive modeling insights.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## ⚙️ Local Setup & Installation

1. Clone this repository:
   ```bash
   git clone [https://github.com/hanan1hub/Advanced-Data-Wrangling-Toolkit.git](https://github.com/hanan1hub/Advanced-Data-Wrangling-Toolkit.git)
