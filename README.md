# GPU Price Prediction Using RAM Market Trends
### A Macro-Driven Machine Learning Approach

This project explores GPU price prediction by leveraging trends in the RAM market as macro-level indicators.  
Rather than relying solely on GPU-specific data, the study investigates how correlated hardware components influence pricing behavior.

## Overview

GPU prices are influenced by a combination of supply constraints, demand cycles, and broader hardware market dynamics. One of the strongest related components is RAM, which often shares production constraints and market fluctuations with GPUs.

This project frames GPU price forecasting as a regression problem and evaluates whether RAM price trends can serve as meaningful predictive signals.

## Data & Approach

Historical GPU and RAM pricing data are collected and aligned across time. The dataset is cleaned, transformed, and structured to capture temporal trends and relative price movements.

Machine learning regression models are trained to learn relationships between RAM price behavior and GPU price changes, with performance evaluated using standard regression metrics.

## Methodology

The workflow includes data preprocessing, feature engineering, model training, and evaluation.  
Emphasis is placed on interpretability and stability rather than overfitting or short-term accuracy.

## Technology

The project is implemented using:
- Python for data processing and modeling  
- Pandas and NumPy for data manipulation  
- Scikit-learn for machine learning models  
- Matplotlib for visualization and analysis  

## Purpose

This project demonstrates applied data science skills in regression modeling, feature engineering, and macro-level reasoning. It highlights how indirect indicators can be incorporated into predictive models for real-world pricing problems.

## Future

Future work may include additional macro indicators, time-series–specific models, and deeper evaluation of causal relationships between hardware markets.
