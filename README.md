==================================================
📁 Project Title: Diabetes Classification & Clustering Using BRFSS 2015 Data
Author: Daniel Miuta
Course: Foundations of Intelligent Systems
==================================================

📊 Dataset:
-----------
Name: diabetes_012_health_indicators_BRFSS2015.csv  
Source: Centers for Disease Control and Prevention (CDC)  
Original Dataset: Behavioral Risk Factor Surveillance System (BRFSS), 2015

This dataset contains anonymized health-related information for individuals, including physical activity, general health, mental health, BMI, smoking, and other behavioral risk factors.

📌 Target Variable:
-------------------
Diabetes_012:
- 0 = No diabetes
- 1 = Prediabetes
- 2 = Diagnosed diabetes

🎯 Project Goals:
-----------------
- Clean and preprocess real-world health indicator data
- Train classification models (Logistic Regression, Decision Tree, MLP)
- Evaluate performance using precision, recall, F1-score, and confusion matrix
- Apply K-Means clustering to discover unsupervised structure in the data
- Visualize clusters and compare to true class labels using PCA

🧪 Features:
------------
- HighBP: High blood pressure (1=yes)
- HighChol: High cholesterol (1=yes)
- CholCheck: Cholesterol check in past 5 years
- BMI: Body Mass Index
- Smoker: Have smoked at least 100 cigarettes in life
- Stroke: Ever had a stroke
- HeartDiseaseorAttack: Coronary heart disease or myocardial infarction
- PhysActivity: Physical activity in past 30 days
- Fruits, Veggies: Daily consumption
- HvyAlcoholConsump: Heavy alcohol use (men >14/week, women >7/week)
- AnyHealthcare: Have any health coverage
- NoDocbcCost: Could not see doctor due to cost
- GenHlth: General health (1=excellent to 5=poor)
- MentHlth: Poor mental health days in past 30
- PhysHlth: Poor physical health days in past 30
- DiffWalk: Difficulty walking or climbing stairs
- Sex: 0=Female, 1=Male
- Age: Age category
- Education: Education level
- Income: Income bracket

📦 Dependencies:
----------------
Install required Python libraries with:

    pip install -r requirements.txt

Required:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

📝 Notes:
---------
- Project implemented in Jupyter Notebook using real dataset
- Notebook file located in `notebooks/diabetes_classifier.ipynb`
- Evaluation metrics and visualizations are included
- Additional clustering performed for deeper insights

✅ Ready for final submission.
