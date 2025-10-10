# RealityAI — Real Estate Forecasting Project


<p align="center">
  <a href="https://www.python.org/">
    <img src="https://img.shields.io/badge/Built%20with-Python-3776AB?logo=python&logoColor=white" alt="Python Badge" />
  </a>
  <a href="https://colab.research.google.com/">
    <img src="https://img.shields.io/badge/Made%20in-Google%20Colab-F9AB00?logo=googlecolab&logoColor=white" alt="Google Colab Badge" />
  </a>
  <a href="https://facebook.github.io/prophet/">
    <img src="https://img.shields.io/badge/Forecasting-Prophet-00BFFF?logo=meta&logoColor=white" alt="Prophet Badge" />
  </a>
  <a href="https://streamlit.io/">
    <img src="https://img.shields.io/badge/App-Streamlit-FF4B4B?logo=streamlit&logoColor=white" alt="Streamlit Badge" />
  </a>
</p>

---

## Table of Contents
- [About the Project](#about-the-project)
- [Objectives](#objectives)
- [Tools and Technologies](#tools-and-technologies)
- [Repository Structure](#repository-structure)
- [Features](#features)
- [Installation](#installation)
- [Models](#models)
- [Results](#results)
- [Author](#author)
- [Acknowledgement](#acknowledgement)

---

## About the Project
**RealityAI** is a real estate forecasting project developed as part of my **Infosys Internship (Aug 2025)**.  
It uses machine learning and time series forecasting with Facebook Prophet to analyze and predict real estate market trends across various U.S. regions.

Key goals include:  
- Developing price prediction models based on property features  
- Creating state-wise time series forecasting models  
- Providing an interactive visualization dashboard via Streamlit  

---

## Objectives
- Clean and preprocess real estate datasets  
- Build machine learning models for price prediction  
- Apply Prophet for time series forecasting  
- Visualize and compare historical vs. forecasted data  
- Deliver an interactive app for data exploration  

---

## Tools and Technologies

| Category        | Tools / Libraries               |
|-----------------|-------------------------------|
| Programming     | Python 3.10+, Google Colab      |
| Machine Learning| scikit-learn, BaggingRegressor |
| Forecasting     | Facebook Prophet               |
| Data Analysis   | pandas, numpy                  |
| Visualization   | matplotlib, seaborn, streamlit |
| Version Control | Git, GitHub                   |

---

## Repository Structure

Reality-AI/
├── Models/
│ ├── encoder.pkl # Label encoder for categorical features
│ ├── prophet_models.pkl # Prophet models for multiple states
│
├── Notebooks/
│ ├── RealEstate.ipynb
│ ├── Timeseries.ipynb
│ ├── pipeline.ipynb
│ ├── Streamlit_app.ipynb
│
├── Script/
│ ├── prediction_vs.py
│
├── data/
│ ├── (datasets used for training)
│
└── README.md


---

## Features
**Property Price Prediction**  
- Predict prices using city, location, BHK, total area, price per sqft, bathrooms, and balconies  

**Time Series Forecasting**  
- Generate forecasts with confidence intervals for each state using Prophet  
- Compare forecasts across regions  
- Analyze historical trends and statistics  

**Visualization Dashboard**  
- Interactive and responsive Streamlit app to explore data and predictions  

**Data Processing Pipeline**  
- Includes preprocessing and encoding to support modeling  

---

## Installation

1. Clone the repository  
```bash
git clone https://github.com/BarshaChangdar/Reality-AI.git
cd Reality-AI


Install dependencies

pip install -r requirements.txt


Run the Streamlit dashboard

streamlit run Notebooks/Streamlit_app.ipynb


Alternatively, open and run notebooks directly in Google Colab or Jupyter

Models
File	Description
encoder.pkl	Label encoder for categorical features
prophet_models.pkl	Prophet forecasting models for multiple states
bagging_model.joblib (optional)	ML pipeline for price prediction
Results

Forecasted property prices and trends with confidence intervals

Visualized multi-state comparisons and historical data

Integrated ML models with time series for real-world insights

## Author
**[Barsha Changdar](https://github.com/BarshaChangdar)**  
Infosys RealtyAI Internship (Aug 2025)  

Mentor: **[Aabid MK](https://github.com/AabidMK)**

Acknowledgement

Thanks to my mentor Aabid MK
 for his invaluable support,
and to Infosys for providing the opportunity to work on real-world forecasting and analytics.

<p align="center"> Designed and developed by Barsha Changdar </p> ```
