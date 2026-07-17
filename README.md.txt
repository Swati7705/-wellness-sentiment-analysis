# Wellness App Sentiment & Retention Analysis

## Overview
This project analyzes 1,111 real user reviews from 4 major 
wellness apps on the Google Play Store to understand what 
drives user satisfaction and predict whether a user is 
satisfied or not — using NLP sentiment analysis and 
machine learning.

**Apps Analyzed:** Habitica, Headspace, MyFitnessPal, Fabulous

---

## The Business Question
> "What do user reviews reveal about satisfaction drivers 
> in wellness apps — and can we predict user sentiment 
> automatically?"

This question matters because:
- Product teams spend hours manually reading reviews
- Negative reviews contain early warning signals
- Understanding WHY users are unhappy helps prioritize fixes

---

## Project Structure
wellness_project/
├── data/
│ ├── raw_reviews.csv ← scraped from Play Store
│ ├── clean_reviews.csv ← after cleaning
│ └── sentiment_reviews.csv ← with sentiment scores
├── notebooks/
│ ├── 01_scraping.ipynb ← data collection
│ ├── 02_cleaning.ipynb ← data cleaning
│ ├── 03_eda.ipynb ← exploratory analysis
│ ├── 04_sentiment.ipynb ← sentiment analysis
│ └── 05_ml_model.ipynb ← machine learning
└── outputs/charts/ ← all visualizations