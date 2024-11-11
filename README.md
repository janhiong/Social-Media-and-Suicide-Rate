# 📱 Analyze the impact of Social Media on Suicide Rates: 
## A Predictive Modeling Approach

## 🔑 Key Takeaways:
🔑 Learn the data analysis process of wrangling, exploring, analyzing, and communicating data, and work with data in Python, using libraries like NumPy and Pandas.
🔑 Mastered applying PCA and KMeans clustering to simplify data complexity and uncover hidden patterns in social media usage behavior.
🔑 Gained insights on using SHAP for explaining model outputs, highlighting the transparency and trustworthiness of complex machine learning models.

## 1. Motivation and Background
Over the past decade, the exponential growth of social media platforms has reshaped communication, information sharing, and personal interactions. As a social media user, I understand that while these platforms offer numerous benefits, concerns about their impact on mental health and well-being have increased. This project aims to address whether changes in social media user growth can predict changes in suicide rates, highlighting the potential use of predictive models in public health.

## 2. Project Structure

### a. Data Collection

The dataset was obtained from Kaggle, featuring 30 records spanning the years 2010 to 2019. Key columns include:

- Year

- Sex

- Suicide Rate % Change since 2010

- Twitter User Count % Change since 2010

- Facebook User Count % Change since 2010

### b. Exploratory Data Analysis (EDA)

Initial steps involved loading and cleaning the data, ensuring there were no missing values, and displaying summary statistics. The dataset was explored visually through histograms, pair plots, and a correlation heatmap to reveal the distribution and relationships between variables.

### c. Clustering Analysis

Using KMeans Clustering, social media usage patterns were categorized into three distinct groups to better understand user behaviors. The clusters provided insights into different growth patterns, supporting more tailored mental health strategies.

### d. Dimensionality Reduction

Principal Component Analysis (PCA) was applied to reduce dimensionality, allowing for a clearer visual representation of the variance within the data. This approach helped reveal which components (PCA1 and PCA2) were most important in explaining the trends in social media growth and suicide rate changes.

## 3. Machine Learning Model

The project used various machine learning models to predict suicide rate changes, with the Gradient Boosting Regressor delivering the best results.

- Model Training

- Training/Test Split: Data was split into an 80/20 train-test ratio.

- Features: Included both social media growth metrics and PCA components.

- Model Evaluation

  + Mean Squared Error (MSE): 0.5414

  + R² Score: 0.9611

These metrics indicated that the model performed exceptionally well, explaining 96.11% of the variance in suicide rate changes.

## 4. Feature Importance Analysis

To interpret the model’s predictions, SHAP (SHapley Additive exPlanations) was utilized. The analysis identified the following as the most influential features:

- PCA1: Captured the combined influence of Twitter and Facebook growth.

- Twitter User Count % Change: Demonstrated a significant impact on suicide rate changes.

- Facebook User Count % Change: Contributed, but to a lesser extent than Twitter.

- Clustering-Based Social Media Usage Feature: Added value but was less impactful.

## 5. Visualizations and Key Findings

- Histograms showcased distributions of the suicide rate changes and social media user growth.

- Pair plots illustrated relationships between the main variables.

- Heatmaps highlighted correlations, showing a notable relationship between Facebook growth and suicide rates.

- PCA plots provided a clear visual of how social media metrics influenced suicide rate changes.

- SHAP Summary Plots clarified feature contributions to the model.

## 6. Conclusion and Recommendations

The analysis revealed a robust correlation between social media user growth and changes in suicide rates. Twitter growth was found to be a particularly strong predictor, suggesting that the rapid expansion of certain platforms may play a role in influencing mental health trends.

## Future Work

Future research could benefit from:

Integrating additional variables (e.g., demographic, psychological data) for more comprehensive models.

Exploring ethical considerations to ensure responsible use of predictive analytics in public health strategies.
