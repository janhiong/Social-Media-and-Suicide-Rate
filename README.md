# 📱 Analyze the Impact of Social Media on Suicide Rates: 
## A Predictive Modeling Approach

## 👩‍⚕️ Goals of the project
The primary goal of this project was to determine if social media user growth could predict changes in suicide rates and identify which social media metrics had the strongest impact. This predictive approach aimed to enhance understanding of potential links between digital behavior and mental health trends, contributing valuable insights for public health research.

## #️⃣ Conclusions
- There is a robust correlation between social media user growth and changes in suicide rates, with Twitter growth being a particularly strong predictor.
- The Gradient Boosting Regressor model performed exceptionally well, with an R² score of 0.9611, indicating that the model could explain over 96% of the variance in suicide rate changes.
- These results highlighted the potential of using social media metrics for mental health trend predictions but also underscored the need for responsible application.
  
## 🧠 Challenges
One of the main challenges I faced was managing the limited dataset size (30 records), which required careful handling to avoid overfitting and ensure meaningful results. Additionally, balancing the interpretability of the model with its predictive power posed another challenge, particularly when integrating complex features like PCA components and clustering results.

## 👩‍💻 Cool Techniques Used
- KMeans Clustering: This technique was employed to segment social media usage patterns into behavioral clusters, revealing distinct user growth patterns that informed the analysis.
- Principal Component Analysis (PCA): Used to reduce dimensionality and highlight key variance components, making the data more manageable and enhancing model performance.
- SHAP (SHapley Additive exPlanations): Applied to explain the model’s feature importance and ensure transparency in predictions, aiding in a clear understanding of which social media metrics were most influential.

## 🔑 Key Takeaways:
- Learned the data analysis process of wrangling, exploring, analyzing, and communicating data, and work with data in Python, using libraries like NumPy and Pandas.
- Mastered applying PCA and KMeans clustering to simplify data complexity and uncover hidden patterns in social media usage behavior.
- Gained insights on using SHAP for explaining model outputs, highlighting the transparency and trustworthiness of complex machine learning models.
  
## 🔖 Future Work
- Integrating more comprehensive data sources, such as demographic and psychological factors, to enhance model accuracy.
- Applying additional machine learning models or ensemble techniques for comparison.
- Addressing ethical considerations to ensure responsible use of predictive analytics in public health interventions.



