Analysis of Economic Instability in Pakistan (1990–2023)
📌 Project Overview
This project provides a comprehensive analysis of Pakistan's economic landscape over the last three decades. By utilizing Random Forest Machine Learning models and Time-Series Cross-Validation, the analysis identifies the primary drivers of GDP growth and economic instability.

The project transitions from raw data cleaning to advanced statistical EDA, culminating in a predictive model that evaluates the impact of variables like Inflation, Debt-to-GDP, and Political Stability.

🚀 Key Features
Time-Series Modeling: Uses TimeSeriesSplit to respect the chronological order of economic data.

Predictive Analytics: Implements a Random Forest Regressor to forecast GDP growth.

Feature Importance: Quantifies which economic indicators (e.g., Exchange Rate, CPI) most heavily influence the national economy.

Economic Roadmap: Includes a data-driven 3-phase recommendation report for economic recovery.

📊 Visualizations Included
The analysis generates several critical graphs:

Top 12 Feature Importance: A bar chart showing what truly drives GDP growth.

Correlation Heatmaps: Visualizing the relationship between Debt, Inflation, and Currency value.

Actual vs. Predicted GDP: A time-series comparison showing model accuracy.

Economic Crisis Detection: Identification of negative growth periods.

🛠️ Technology Stack
Language: Python

Data Analysis: Pandas, NumPy

Machine Learning: Scikit-Learn (Random Forest, TimeSeriesSplit)

Visualization: Matplotlib, Seaborn

📂 Dataset
The analysis is based on pakistan_clean.csv, which contains monthly observations from June 1990 to December 2023 (403 months).

Target Variable: GDP_Growth

Key Features: Inflation_CPI, Debt_to_GDP, Exchange_Rate_PKR/USD, Political_Stability_Index.

📈 Summary of Insights
Primary Volatility Drivers: The model suggests that Political Stability and Exchange Rate fluctuations are the strongest predictors of economic shifts.

Phase 1 Recommendation: Focus on Immediate Stabilization (Inflation control and PKR support).

Phase 2 Recommendation: Structural Reforms (Tax broadening and export initiatives)
