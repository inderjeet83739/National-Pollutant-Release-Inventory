📌 NPRI - Environmental Spill Risk Classification Using Machine Learning

🔬 Predicting Industrial Spill Risks to Improve Environmental Monitoring & Compliance

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🏆 Project Overview

Environmental spills pose a significant risk to ecosystems and public health. The National Pollutant Release Inventory (NPRI) tracks these spills, but manual classification of spill risks is inefficient. This project builds a machine learning model to automate spill risk classification, categorizing incidents into Low, Medium, or High-risk spills using Logistic Regression (97% accuracy). By leveraging feature engineering, hyperparameter tuning, and advanced preprocessing, this project provides accurate and actionable insights for environmental agencies and industries.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🚀 Key Features

✔️ Predicts Spill Risk: Classifies incidents as Low, Medium, or High risk
✔️ Advanced Data Processing: Handles missing values, categorical encoding, and outlier detection
✔️ Exploratory Data Analysis (EDA): Identifies trends in spill locations, causes, and severity
✔️ Feature Engineering: Utilizes Total Releases, Air Spill, Land Spill, and Water Spill for better predictions
✔️ Optimized Logistic Regression Model: 97% accuracy with GridSearchCV for hyperparameter tuning
✔️ Risk-Based Insights: Helps industries & policymakers mitigate future environmental hazards

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📊 Exploratory Data Analysis (EDA) Insights

📌 Spill Severity & Industry Trends:
	•	Industries with higher chemical waste production have more frequent spills
	•	Some substances contribute disproportionately to high-risk spills

📌 Regional Spill Patterns:
	•	Certain regions have higher environmental risks due to industrial density
	•	Air and water spills are more common in specific geographic areas

📌 Correlation Between Chemical Types & Spill Severity:
	•	Some chemical categories are high-risk due to their environmental impact
	•	Waterborne spills are often linked to hazardous waste disposal

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🤖 Machine Learning Model - Logistic Regression

✔️ Algorithm Used: Logistic Regression
✔️ Problem Type: Multi-Class Classification (Low, Medium, High Risk)
✔️ Target Variable: Spill Risk Classification

🔹 Feature Engineering for Better Predictions:
✔️ Total Releases + Breakdown into Air, Land, Water Spills
✔️ Industry Type (NAICS Code) and Chemical Composition

🔹 Model Performance:
✔️ Accuracy: 97%
✔️ Optimized using: GridSearchCV for hyperparameter tuning
✔️ Class Imbalance Handling: SMOTE (Synthetic Minority Oversampling)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🛠 Tech Stack

🚀 Python | Scikit-Learn | Pandas | Matplotlib | Logistic Regression
