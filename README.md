# Siemens Sales Forecasting

This repository contains the project developed within the **Master in Data Science and Advanced Analytics (NOVA IMS)** for the challenge launched by **Siemens**.

## Goal
Build a **monthly sales forecasting model** for the Smart Infrastructure unit (Germany), using:
- Historical sales data (2018–2022)
- Relevant macroeconomic indicators
- The **CRISP-DM** methodology

## Methodology
1. **Business & Data Understanding**  
   - Analysis of sales series (14 product groups)  
   - Integration of macroeconomic indices (production, energy, metals, prices, etc.)  

2. **Data Preparation**  
   - Cleaning (negative values, missing data, outliers)  
   - Feature engineering (lags, COVID impact, year-end effect, Suez Canal disruption)  

3. **Modeling**  
   - Algorithms: **CatBoost**, **Prophet**, **Mean/Median**  
   - Selection based on performance (RMSE)  
   - CatBoost consistently delivered the best results  

4. **Evaluation & Deployment**  
   - Metric: **Root Mean Square Error (RMSE)**  
   - Integrated forecasts into Siemens’ provided template  
   - Proposed a plan for maintenance and monitoring  

## Results
- **CatBoost** achieved the lowest RMSE across product groups  
- Forecasts enable **strategic planning**, inventory optimization, and pricing insights  

## Authors
Group R – NOVA IMS (2024)  
Catarina Rodrigues, Cláudia Beiral, Flávia Rodrigues, Jéssica Vicente, Sophia Mizinski
