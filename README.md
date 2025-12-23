# Customer Lifetime Value (LTV) Prediction

This project focuses on predicting Customer Lifetime Value (LTV) using historical purchase behavior and machine learning techniques.

## Project Overview
Customer Lifetime Value helps businesses understand the long-term value of their customers. In this project, customer transaction data is analyzed to derive behavioral features such as recency, frequency, monetary value, and customer age. A regression-based machine learning model is then used to predict the lifetime value of each customer.

## Objectives
- Analyze customer purchase behavior
- Predict Customer Lifetime Value using machine learning
- Segment customers into Low, Medium, and High value groups
- Support data-driven marketing and retention strategies

## Dataset Description
The dataset contains customer-level behavioral features derived from transaction data, including:
- Recency (days since last purchase)
- Frequency (number of purchases)
- Monetary value (total spending)
- Customer age (relationship duration)

## Methodology
1. Data cleaning and preprocessing
2. Feature engineering (Recency, Frequency, Monetary, Customer Age)
3. LTV calculation
4. Model training using regression techniques
5. Model evaluation
6. Customer segmentation based on predicted LTV

## Tools and Technologies
- Python
- Pandas
- Scikit-learn
- XGBoost
- Jupyter Notebook

**Output**
The project generates a CSV file containing:
- Predicted Customer Lifetime Value
- Customer segments (Low, Medium, High)

**Files in this Repository**
- Customer_LTV_Prediction.ipynb` – Implementation notebook
- Final_LTV_Predictions.csv` – Output file with predicted LTV
- Customer_LTV_Report.pdf` – Project report

## Conclusion
This project demonstrates how machine learning can be applied to predict customer lifetime value and segment customers effectively. The insights gained can help businesses optimize marketing efforts and improve customer retention.
