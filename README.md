# Analyze the impact of Social Media on Suicide Rates: 
## A Predictive Modeling Approach

## Project Overview
Investigating the relationship between social media growth and changes in suicide rates (2010-2019).

## Motivation and Background
Exploring the impact of social media on mental health and public well-being.

## Project Structure
- **Data Collection**: Kaggle dataset covering 2010-2019.
- **EDA**: Visual analysis of data.
- **Clustering**: KMeans for social media usage patterns.
- **Dimensionality Reduction**: PCA for variance analysis.

## Machine Learning Model
Gradient Boosting Regressor yielded the best performance:
- **MSE**: 0.5414
- **R² Score**: 0.9611

## Feature Importance
Top features using SHAP:
- **PCA1**
- **Twitter User Count % Change**
- **Facebook User Count % Change**

## Visualizations
- Histograms, pair plots, and heatmaps.
- PCA and SHAP summary plots.

## Conclusion and Recommendations
Strong correlation between social media growth and suicide rate changes.

## Technical Requirements
- Python libraries: `pandas`, `seaborn`, `matplotlib`, `sklearn`, `xgboost`, `lightgbm`, `shap`

## How to Run
1. Install libraries.
2. Load and verify data.
3. Run EDA.
4. Train models.
5. Visualize results.

## Acknowledgments
Leveraging data for public health insights.
