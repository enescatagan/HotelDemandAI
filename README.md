Hotel Management AI Models
==========================

## Overview

This project leverages real hotel reservation data to build artificial intelligence models that assist hotel management in optimizing operations, increasing customer satisfaction, and maximizing profit margins.

## Key Applications

1. **Customer Segmentation:** Identifies different types of customers to enhance personalized marketing strategies.
2. **Booking Cancellation Prediction:** Predicts which reservations are likely to be canceled to reduce revenue loss.
3. **Dynamic Pricing:** Adjusts room prices dynamically based on demand and other factors to optimize revenue.

Project Organization
------------
    ├── data                        <- Data
    ├── models                      <- Trained Models
    ├── notebooks
    │   ├── prep                    <- Only necessary Notebooks for model production; data preparation, pipeline creation, parameter tuning etc.
    │   ├── test                    <- Every notebook for quick test; dump and test notebooks
    │   └── main.ipynb              <- Main Notebook
    ├── requirements.txt            <- The requirements file, generated with `pip freeze > requirements.txt`
    └── Readme.md                   <- Project Explanation, notes etc. 

## Features & Workflow

- Data Loading & Exploration
- Data Cleaning & Feature Engineering
- Outlier Analysis & Handling Missing Values
- Exploratory Data Analysis (EDA)
- Model Training & Hyperparameter Tuning
- Evaluation & Deployment Considerations

## Technologies Used

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, LightGBM, etc.)
- Machine Learning (Clustering, Classification, Regression)
- Jupyter Notebook for interactive development

## Dataset

The dataset used is based on real hotel reservation data, publicly available [**here**](https://www.sciencedirect.com/science/article/pii/S2352340918315191).

## Installation & Usage

1. Clone the repository:
    ```
    git clone https://github.com/enescatagan/HotelDemandAI.git
    cd hotel-management-ai
    ``` 


2. Install dependencies:
    ```
    pip install -r requirements.txt
    ```
3. Run the Jupyter Notebook:
    ```
    jupyter notebook notebooks/main.ipynb
    ```