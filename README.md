# project3
AIML_Clickstream-Customer Conversion
# 🛒 Clickstream Conversion Analysis

Welcome to the Clickstream Conversion Analysis project! This Streamlit-powered dashboard explores how users interact with an e-commerce platform, predicting conversion likelihood, segmenting user behavior, and uncovering revenue-driving patterns. Built with modular ML pipelines and Tamil-flavored design flair 🌶️.

## 📦 Project Structure
clickstream_conversion/ │ ├── data/                  # Raw and processed clickstream data ├── models/                # Saved classification, regression, clustering models ├── notebooks/             # EDA and model development notebooks ├── app/                   # Streamlit dashboard code ├── utils/                 # Helper functions (feature engineering, preprocessing) └── README.md   

## 🎯 Objectives

- **Classification**: Predict whether a user will convert (binary outcome)
- **Regression**: Estimate potential revenue per user
- **Clustering**: Segment users based on behavior patterns (e.g., bounce rate, dwell time, page depth)

## 🧠 Features Used

- Session duration, page views, scroll depth
- Referral source, device type, time of day
- Previous visits, cart abandonment rate
- Custom engineered features like "hesitation score" and "scroll-to-click ratio"

## 🚀 Deployment

The dashboard is deployed using **Streamlit**, with MLflow integration for model tracking and pickle-safe loading.

To run locally:

```bash
pip install -r requirements.txt
streamlit run app/dashboard.py
