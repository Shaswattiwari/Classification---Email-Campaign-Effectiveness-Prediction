# Predictive Power for Email Campaigns
This repository provides a framework for predicting email campaign performance using customer data. It leverages machine learning models to analyze various campaign attributes and forecast success metrics.

## Key Predictive Features:
### Categorical Features:
Email type, source type, campaign type, customer location (optional for privacy concerns).

### Numerical Features: 
Subject line hotness score, total past communications, time category (weekday morning, etc.), word count, total links, total images.

## Model Selection:

The repository implements two well-established models:

### Deep Learning Model: 
A powerful, non-linear model capable of identifying complex relationships within the data.
### Random Forest Model: 
A robust ensemble method known for handling various data types and offering interpretability.

## Running the Analysis:

### Prerequisites: 
Python (v3.6+), TensorFlow, scikit-learn, scikeras (installable via pip).

### Execution Options:
Jupyter Notebook (email_campaign_prediction.ipynb) for interactive exploration and visualization.

Python script (email_campaign_prediction.py) for direct prediction.

Output: Accuracy scores for each model, indicating their ability to predict campaign effectiveness.
