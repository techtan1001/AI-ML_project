🌍 SustainAI: Predicting and Clustering Global Energy & Literacy Trends

A data-driven approach to uncover global sustainability patterns using machine learning techniques.

📌 Overview

This project explores and analyzes global datasets related to sustainable energy, development indicators, and literacy trends from 2000 to 2020. Our goal is to build predictive models and apply clustering techniques to support global initiatives aligned with the UN Sustainable Development Goals (SDGs) — particularly Goal 7: Affordable and Clean Energy and Goal 4: Quality Education.

🎯 Objectives

📈 Predict future values for literacy rate and energy access.
🔍 Cluster countries based on development and energy similarities.
⚖ Compare performance of linear and non-linear models for better forecasting accuracy.

📂 Dataset

Name: Global Data on Sustainable Energy
Source: Kaggle
Format: CSV
Period: 2000–2020
Key Features:
Country
Year
Access to Electricity (%)
Access to Clean Fuels (%)
Renewable Energy Consumption (%)
Urban Population (%)
Literacy Rate (%)
Electricity Consumption per Capita (kWh)

🧠 Methodology

Understand and preprocess the dataset
Feature selection and target identification
Apply Linear Regression, Ridge Regression, and Random Forest Regression
Use K-Means Clustering to identify country groupings
Evaluate models using metrics like MAE (Mean Absolute Error)
Visualize and interpret results

🛠 Technologies Used

Python
Scikit-learn
Pandas
Matplotlib / Seaborn
Jupyter Notebook

📊 Results

Ridge Regression outperformed basic linear models by handling multicollinearity.
Random Forest captured complex, non-linear patterns more effectively.
K-Means Clustering revealed meaningful global groupings of countries based on development and energy access indicators.
Final MAE (at 100 epochs):
Train MAE ≈ 8
Validation MAE ≈ 10

🚀 Future Work

Update with data from 2021–2025
Include economic and policy-based indicators
Implement time-series models like ARIMA or LSTM
Add geospatial visualization
Target low-cluster countries with deeper analysis

📁 Repository Structure

📦 AI-ML_project
 ┣ 📂 data/              # Raw dataset and any processed versions
 ┣ 📂 notebooks/         # Jupyter Notebooks with analysis and modeling
 ┣ 📂 visuals/           # Generated plots and figures
 ┣ 📄 README.md          # Project overview
 ┗ 📄 requirements.txt   # Python dependencies
 
🔗 Useful Links

🔬 Project Presentation: Case_Study.pptx
💻 GitHub Repo: https://github.com/techtan1001/AI-ML_project.git
📊 Dataset: Kaggle – Global Sustainable Energy Dataset

👥 Team

Team Leader: Tanishka Bhojne
Team Member: Om Bhatkar
Institution: Ajeenkya DY Patil University
