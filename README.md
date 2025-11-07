# Crisis Recovery Analytics – QuickBite Express

## 📌 Project Overview
This repository contains a comprehensive analytics solution developed to diagnose and address the operational and reputational fallout from a dual-crisis event at QuickBite Express (food safety incident + delivery outage). The project integrates customer segmentation, sentiment modelling, operational diagnostics, and incentive-based recovery simulations to guide strategic decision-making.

## 🧠 Objectives
- Quantify customer churn and behavioural shifts across Recency, Frequency, and Monetary (RFM) dimensions
- Identify operational breakdowns in SLA compliance, delivery delays, and cancellation patterns
- Model return probability for lapsed users based on incentive type and behavioural profile
- Simulate ROI across recovery strategies segmented by customer archetypes
- Benchmark Customer Acquisition Cost (CAC) against competitors (Swiggy, Zomato)

## 🧰 Tools & Technologies
- Python: Data preprocessing, modelling, and visualisation
- Pandas, NumPy: Data wrangling and feature engineering
- Matplotlib, Seaborn: Visual storytelling and trend analysis
- Scikit-learn: Predictive modelling and probability estimation
- NLTK: Sentiment extraction and keyword parsing

## 📊 Key Deliverables
- RFM segmentation and churn diagnostics
- Monthly ratings and sentiment trend analysis
- SLA and cancellation heatmaps
- Restaurant-level performance decline
- Return probability model with incentive mapping
- ROI simulation by customer segment and strategy
- CAC benchmarking dashboard

## 📈 Methodology Highlights
- RFM Scoring: Used to segment customers based on pre-crisis engagement
- Sentiment Modelling: Monthly score trends extracted from review text using NLP
- Return Probability Estimation: Logistic regression and decision trees applied to predict reactivation likelihood
- ROI Simulation: Incentive cost vs reactivation yield modelled across archetypes
- Benchmarking: CAC multipliers derived from simulated ad inflation, seasonal demand, and saturation factors

## 📌 Limitations
- Post-crisis data beyond September 2025 not included
- Sentiment analysis is limited by unstructured or missing review text
- ROI estimates based on simulated incentive costs and modelled probabilities
- SLA attribution not vendor-specific due to data granularity constraints

## 📣 Author
**Bitan Sarkar**
MSc Business Analytics, University of Bristol
Data Analyst | Strategic Storyteller | Dashboard Designer
