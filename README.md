# Decision Tree - Heart Disease Classifier

Heart disease occurs when the heart's blood supply is blocked by a build-up of plague (fatty substances) in the coronary arteries. It is a leading cause of death worldwide. It is also a treatable and preventable disease, given the appropriate medication and life style changes. Therefore, prediction of heart disease is of great social value and can facilitate early treatment of patients. 

## Data
The heart disease data can be obtained from the <a href="https://archive.ics.uci.edu/ml/datasets/heart+disease">UCI Machine Learning Repository</a>. The full dataset has 76 attributes. In this notebook we use the processed version, which containes a subset (14) of the attributes, to train our model. 

### Attributes
1. Age
2. Sex
3. CP - Chest Pain Types (total of 4 types)
4. Trestbps - Resting Blood Pressure (mmHg)
5. Chol - Serum Cholesterol Level (mm/dl)
6. Fbs - Fasting Blood Sugar > 120 mg/dl (0 for false, 1 for true)
7. Restecg - Resting Electrocardiogram results
8. Thalac - Maximum Heart Rate
9. Exang - Exercise Induced Angina (0 for false, 1 for true)
10. Oldpeak - ST depression induced by exercise relative to rest
11. Slope - Slope of peak exercise ST segment
12. Ca - Number of major vessels (0-3) colored by flourosopy
13. Thal - 3 = normal; 6 = fixed defect; 7 = reversable defect
14. Num - the predicted attribute (0 for no heart disease, 1 for heart disease)

We do not neccessarily have to understand what every metrics mean medically, but it's important to know if it's a continuous or categorical variable as it will influence how we process the data. 

## Decision Trees
![](https://github.com/RussH-code/DecisionTree-Heart-Disease-Classifier/blob/main/dt.png)

Source: (https://medium.com/swlh/decision-tree-classification-de64fc4d5aac)

A decision tree resembles how human make decisions with flowcharts. In each nodes there is a criteria or question, and the answer to that will route the decision process to the left or right node. Leaf refers to the bottom layer of the tree where the decision has been reached, in classification problems, leaf stores the class labels.
