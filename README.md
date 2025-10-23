# Pharmacy-Sales-Forecasting-Project
Built time-series forecasting model in Python to forecast the sales of pharmacy, fine-tuned them with grid search cross-validation, to generate insight from a pharmacy sales dataset. 

# Description of each file:
healthcare_product_sales.csv -> dataset of pharmacy sales

Pharmacy_TimeSeries_XGBoost.ipynb -> jupyter notebook containing construction, fine-tuning, and usage of XGBoost

TimeSeriesXGClass.py -> python file containing the XG_TimeSeries and XGBoostCV classes, classes that are utilized in Pharmacy_TimeSeries_XGBoost.ipynb to streamline model creation, fine-tuning, data analysis, and visualization

# How to run
To run, the following python libraries must be installed: pandas, numpy, matplotlib, seaborn, xgboost, sklearn, prophet.

# Summary of Findings
Overall, findings indicate relatively healthly growth in all drug categories for the pharmacy. While there are clear seasonal trends for pain relievers, cold remedies, vitamins, and skin care, the seasonal trends for first aid are less clear. However, slight negative trends for cold remedies and skin care signify the need to anticipate seasonal peaks in sales for these categories and change business strategy.
