# Earthquake-Magnitude-Prediction
ML project using USGS earthquake data to predict seismic magnitudes and identify hotspots.

# Earthquake Magnitude Prediction Using Machine Learning

This project uses historical seismic data from the USGS Earthquake Hazards Program to build a machine learning model that predicts earthquake magnitudes based on geographic and seismic parameters. The goal is to enhance early warning systems and disaster preparedness by identifying high-risk zones with predictive modeling.

## 📊 Project Overview

- Course**: MIS 637 – Data Analytics and Machine Learning  
- Institution: Stevens Institute of Technology  

## 🧠 Objectives

- Predict the magnitude of seismic events using real USGS data
- Analyze spatial-temporal patterns and hotspots
- Compare model performance (KNN vs Decision Tree)
- Provide actionable insights for risk forecasting

## 📁 Dataset

- Source: [USGS Earthquake Hazards Program](https://earthquake.usgs.gov/earthquakes/feed/v1.0/csv.php)
- Data fields: Time, Latitude, Longitude, Depth, Magnitude, Gap, RMS, and more

## 🧰 Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn, Plotly Express)
- Jupyter Notebook / Google Colab
- Machine Learning: K-Nearest Neighbors (KNN), Decision Tree Regressor
- Evaluation Metrics: R² Score, Mean Squared Error (MSE)
- Deployment Suggestions: Streamlit + Heatmaps

## 🔍 Key Outcomes

- Achieved **R² = 0.8483** using KNN (MSE = 0.00289)
- Achieved **R² = 0.8028** using Decision Tree (MSE = 0.00376)
- Identified geospatial risk zones and optimized feature scaling
- Implemented MinMaxScaler, handled outliers, and engineered key seismic features

## 📈 Visualizations

- Magnitude distribution over time and geography
- Depth vs magnitude scatter plots
- Heatmaps of seismic hotspots

## 📦 Files Included

- `Main_Earthquake_Prediction_Projec.ipynb` – Model notebook  
- `earthquake.csv` – Cleaned USGS dataset  
- `all_month_2024.csv` – Extended dataset from USGS  


## 🚀 Future Scope

- Integrate model with real-time data via API  
- Deploy dashboard with Streamlit  
- Add clustering for geographic risk segmentation  
- Expand models with ensemble methods (Random Forest, XGBoost)

