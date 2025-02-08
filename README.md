# Predicting-Life-Expectancy-Using-Machine-Learning
Life expectancy is a crucial indicator of a nation’s overall health and development. Our goal was to predict life expectancy based on socio-economic, health, and environmental factors using machine learning. This project aims to assist policymakers, healthcare professionals, and researchers in understanding the key drivers of life expectancy and making data-driven decisions.

**1. Overview:**
This project is based on predicting the life expectancy of a person. It is the statistical average of the number of years a person is expected to live. Factors affecting life expectancy are Country, Mental and Physical Illness, lifestyle, diet, health care services, financial condition, BMI, alcohol consumption, Diseases, etc.

Here in this Predicting Life Expectancy project, our motive is to find the life expectancy of a person after providing details such as the country he is living in is developed or is developing, BMI of the person, Disease history, Income, Population of that country, Expenditure, etc. So here I have used Machine learning and Artificial Intelligence to predict life expectancy. The data used in the training of the model was the data by WHO taken from Kaggle.

There were almost 22 columns stating different factors affecting Life expectancy and 2939 rows comprising data of different persons from different countries.

[The data is taken from kaggle](https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who)

**2. Project Structure**
2.1 Data Preprocessing:(Cleaning and Feature Engeneering)
2.2 EDA: Exploratory Data Analysis
2.3 Model Training: Using different ML techniques and approaches
2.4 Metrics Evaluation: Performance of model

**2.1 Machine Learning Techniques Used**
We experimented with multiple models to achieve optimal performance:

** -Exploratory Data Analysis (EDA):**
🔹 Visualized trends in life expectancy across different countries and income levels.
🔹 Identified missing data and performed imputation.

 **-Feature Engineering:**
🔹 Normalization and encoding of categorical features.
🔹 Handling multicollinearity and feature selection.

**-Models Used:**
🔹 Linear Regression – Baseline model for simple trend analysis.
🔹 Random Forest Regressor – Improved accuracy by capturing complex relationships.
🔹 Gradient Boosting Regressor – Best-performing model with optimized hyperparameters.

**-Evaluation Metrics:**
🔹 R² Score: 0.94 (High predictive accuracy!)
🔹 Mean Absolute Error (MAE): 1.2 years

