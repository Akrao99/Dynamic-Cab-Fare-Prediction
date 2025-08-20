# Uber & Lyft Cab Price Prediction

Price prediction modeling for ride-hailing trips (**Uber & Lyft**) using Python and machine learning.

---

## 📊 Project Overview
This project predicts **cab fares** by combining **ride-hailing trip data** with **weather conditions**.  
It includes:
- Data preprocessing & cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering (time, weather, distance, cab type)
- Machine learning model training
- Model evaluation and insights

---

## 📝 Project Explanation

### Objective
To predict cab fares for Uber and Lyft rides using historical ride data enriched with weather features.

### Data Sources
- `cab_rides.csv` → Trip-level ride-hailing data (Uber & Lyft).
- `weather.csv` → Weather data for the same locations and timestamps.
- `exported-data.csv` → Processed dataset after merging & cleaning.

### Key Steps
1. **Data Cleaning & Merging** – Combine cab and weather datasets.
2. **EDA** – Visualize how fares vary by cab type, time of day, and weather.
3. **Feature Engineering** – Create distance, hour, day, and weather-based features.
4. **Modeling** – Train regression models:
   - Linear Regression  
   - Random Forest Regressor  
   - Support Vector Regressor (SVR)
5. **Evaluation** – Compare models using R², RMSE, and MAE.

### Insights
- Distance is the **strongest predictor** of fare.
- Weather and time of day impact ride pricing.
- Random Forest generally outperforms simpler models.
- Uber and Lyft show slightly different pricing behaviors.

---



## 🧰 Tech Stack
- Python  
- pandas, numpy  
- scikit-learn  
- matplotlib, seaborn, plotly  

---

## 📈 Models & Metrics
Implemented Models:
- Linear Regression
- Random Forest Regressor
- Support Vector Regressor (SVR)

Evaluation Metrics:
- R² (Coefficient of Determination)  
- RMSE (Root Mean Squared Error)  
- MAE (Mean Absolute Error)  
