              HEART ATTACK PREDICTION

About this file:
       			This README file provides an overview of the heart attack prediction project, including details about the dataset, attribute information, and the problem statement.

 About the dataset:
       			This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them.
            In particular, the Cleveland database is the only one that has been used by machine learning researchers to date.
            The "target" field refers to the presence of heart disease in the patient. It is integer-valued, where:
            - 0 = no/less chance of heart attack
            - 1 = more chance of heart attack

 Attribute Information:
1.  Age: Age of the patient
2.  Sex: Gender of the patient (0 = female, 1 = male)
3.  Chest pain type: Type of chest pain experienced by the patient (values: 1 =   typical angina, 2 = atypical angina, 3 = non-anginal pain, 4 = asymptomatic)
4. Resting blood pressure: Resting blood pressure of the patient (in mm Hg)
5. Serum cholesterol: Serum cholesterol level in mg/dl
6. Fasting blood sugar: Fasting blood sugar level > 120 mg/dl (1 = True, 0 = False)
7. Resting electrocardiographic  results: Resting electrocardiographic results (values: 0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy)
8. Maximum heart rate achieved: Maximum heart rate achieved during exercise
9. Exercise induced angina: Exercise-induced angina (1 = Yes, 0 = No)
10. Oldpeak: ST depression induced by exercise relative to rest
11. Slope of the peak exercise ST segment: Slope of the peak exercise ST segment (values: 1 = upsloping, 2 = flat, 3 = downsloping)
12. Number of major vessels colored by fluoroscopy: Number of major vessels colored by fluoroscopy (0-3)
13. Thal: Thalassemia (values: 0 = normal, 1 = fixed defect, 2 = reversible defect)
14. Target: Presence of heart attack (0 = less chance of heart attack, 1 = more chance of heart attack)

 Problem Statement:	
  				The main objective of this project is to determine and examine factors that play a significant role in increasing the rate of heart attacks. Additionally, we aim to use the findings to create and predict a model that can effectively predict the likelihood of a heart attack based on the provided attributes.

 Preliminary analysis:	
   				Perform preliminary data inspection and report the findings as the structure of the data, missing values, duplicates, etc.

Performing EDA:
- Identify the data variables which might be categorical in nature.
- Describe and explore these variables using appropriate tools (e.g., count plot).
- Study the occurrence of CVD across different ages.
- Can we detect heart attack based on anomalies in resting blood pressure of the patient?
- Study the composition of overall patients w.r.t. gender.
- People having higher resting blood pressure have lower chance of heart disease as per the data.
		
Performing EDA and Modeling:
- Describe the relationship between cholesterol levels and our target variable.
- What can be concluded about the relationship between peak exercising and occurrence of heart attack?
- Is thalassemia a major cause of CVD? How are the other factors determining the occurrence of CVD?
- Use a pair plot to understand the relationship between all the given variables.
- Perform logistic regression, predict the outcome for test data, and validate the results by using the confusion matrix.
- From both confusion matrix and classification report, it is clear that the model is very good in predicting the data. Sensitivity and specificity are also very good as per the industry standards.

 Conclusion:
This project aims to explore various factors contributing to heart attacks and develop a predictive model for early detection. Through thorough analysis and modeling, we aim to contribute to the understanding and prevention of heart diseases.
Feel free to customize this README file based on your project's specifics and findings!
