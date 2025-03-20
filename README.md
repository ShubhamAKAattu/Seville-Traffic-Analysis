# Seville Parking Overflow Prediction
**Capstone Project by Shubham Vishal & Raghavendra Vasantham**

## Overview
This project analyzes parking availability in Seville to predict traffic congestion and optimize parking management using machine learning models. The goal is to implement dynamic pricing strategies based on forecasted availability, reducing congestion and improving urban mobility.

---

## Objectives
- Analyze parking data to identify congestion patterns.
- Determine key factors affecting parking availability.
- Cluster parking spots using DBSCAN & K-Means.
- Predict availability using Gradient Boosting & SARIMAX.
- Optimize parking charges using predictive insights.

---

## Methodology & Techniques
### 1️⃣ Data Preprocessing & EDA
- Data Cleaning & Transformation: Removed inconsistencies and missing values.
- Exploratory Data Analysis (EDA):
  - Daily Trends: Analyzed hourly parking patterns.
  - Weekly & Monthly Variations: Identified high-traffic days and seasonal changes.
  - Heatmaps: Visualized parking availability.

### 2️⃣ Feature Engineering
- Applied Random Forest to determine feature importance.
- Found that "Hour" & "Day of the Week" were the only reliable predictors.

### 3️⃣ Clustering Analysis
- K-Means: Unsuccessful in identifying useful clusters.
- DBSCAN: Identified 11 major parking hubs across Seville.

### 4️⃣ Predictive Modeling
- Gradient Boosting: Provided best performance with lagged data.
- SARIMAX (Time Series): Not effective in isolation, but useful with feature engineering.

### 5️⃣ Model Validation
- Cross-validation ensured time-series consistency.
- Prevented overfitting by evaluating model performance on multiple test splits.

---

## Key Insights & Findings
- Early mornings & late nights have higher parking availability.
- Weekdays (midday hours) show peak congestion.
- Clustering identified high-demand parking areas near downtown.
- Gradient Boosting provides the most reliable forecasts when combined with lagged features.

---

## Results & Impact
- Improved traffic flow by understanding congestion patterns.
- Optimized parking utilization using AI-driven insights.
- Dynamic pricing models can reduce congestion & increase revenue.

---

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Seville-Traffic-Analysis.git
   cd Seville-Traffic-Analysis
