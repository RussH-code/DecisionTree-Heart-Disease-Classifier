# Decision Tree - Heart Disease Classifier

Heart disease occurs when the heart's blood supply is blocked by a build-up of plague (fatty substances) in the coronary arteries. It is a leading cause of death worldwide. It is also a treatable and preventable disease, given the appropriate medication and life style changes. Therefore, prediction of heart disease is of great social value and can facilitate early treatment of patients. 

## Data
The heart disease data can be obtained from the <a href="https://archive.ics.uci.edu/ml/datasets/heart+disease">UCI Machine Learning Repository</a>. The full dataset has 76 attributes. In this notebook we use the processed version, which containes a subset (14) of the attributes, to train our model. 

### Attributes
1. Age
2. Sex
3. CP - Chest Pain Types (total of 4 types)
4. trestbps - Resting Blood Pressure (mmHg)
5. chol - Serum Cholesterol Level (mm/dl)
6. fbs - Fasting Blood Sugar > 120 mg/dl (0 for false, 1 for true)
7. restecg - Resting Electrocardiogram results
8. thalac - Maximum Heart Rate
9. exang - Exercise Induced Angina (0 for false, 1 for true)
10. oldpeak - ST depression induced by exercise relative to rest
11. slope - Slope of peak exercise ST segment
12. ca - Number of major vessels (0-3) colored by flourosopy
13. thal - 3 = normal; 6 = fixed defect; 7 = reversable defect
14. num - the predicted attribute (0 for no heart disease, 1 for heart disease)


