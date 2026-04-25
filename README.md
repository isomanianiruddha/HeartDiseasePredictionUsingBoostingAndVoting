# Heart Disease Prediction using Advanced Ensemble Techniques
This project predicts the likelihood of heart disease using advanced ensemble machine learning techniques. It utilizes medical attributes such as age, cholesterol, blood pressure, chest pain type, and other health indicators to classify whether a patient is at risk.

Dataset
* File: `heart.csv`
* Features include:
  * Age
  * Sex
  * Chest Pain Type
  * Resting Blood Pressure
  * Cholesterol
  * Max Heart Rate
  * Exercise Induced Angina
  * Oldpeak
* Target Variable:
  * Heart Disease (0 = No, 1 = Yes)

Technologies Used
* Python
* * Pandas
* NumPy
* Scikit-learn
* XGBoost
* LightGBM
* Matplotlib 
* Seaborn

Data Preprocessing
* Handled missing values
* Encoded categorical variables
* Feature scaling
* Train-test split (80:20)

Models Used
1. Boosting Algorithms
  * AdaBoost
  * Gradient Boosting
  * XGBoost
  * LightGBM

Ensemble Techniques
* Stacking Classifier
* Voting Classifier (Hard Voting & Soft Voting)

Results
* Boosting models significantly improved performance over basic models
* XGBoost and LightGBM provided high accuracy and efficiency
* Stacking further enhanced prediction by combining multiple models
* Voting classifiers improved stability and robustness

Key Insights
* Ensemble learning improves prediction accuracy
* Boosting reduces bias by focusing on misclassified samples
* Stacking leverages strengths of multiple models
* Soft voting often performs better than hard voting

Conclusion
Advanced ensemble techniques such as boosting, stacking, and voting provide highly accurate predictions for heart disease detection. These methods are effective in handling complex medical datasets.

Future Improvements
* Hyperparameter tuning (GridSearchCV)
* Feature engineering
* Real-time deployment using Streamlit/Flask

Author : **Aniruddha Somani**
