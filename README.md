This project builds a predictive model for daily café sales by joining 3 years of internal POS transaction data with NOAA weather records to identify how weather conditions drive revenue and order volume.
Dataset: Internal café POS data (2021–2023) joined with NOAA daily weather observations — ~3 seasons of daily records. Source data not included in this repo as it contains proprietary business records.
What's in this project:

Data merging and feature engineering across POS and weather data sources
Predictive modeling for both daily order count and net sales
Model comparison across linear regression, polynomial regression, and Random Forest
Feature importance analysis identifying daily max temperature as the strongest revenue predictor
Best result: Random Forest R² of 0.71 on held-out test data

Key finding: Daily maximum temperature was the single strongest predictor of both order volume and net sales, outperforming precipitation and wind speed — actionable for staffing and inventory planning.
Tools & Libraries: Python, scikit-learn, pandas, matplotlib, NumPy
