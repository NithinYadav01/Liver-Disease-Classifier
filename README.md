# Liver-Disease-Classifier
 In this project,The Indian Liver Patient Records dataset from Kaggle will be used in this project. Based on specific features, we will determine whether or not a patient has liver disease. We will ascertain whether or not the condition is linked to the total proteins, albumin, etc.
# Dataset
The data collection was gathered from the northeast region of Andhra Pradesh, India, and includes 416 records of liver patients and 167 records of non-liver patients. Groups are classified as either liver patients (liver disease) or not (no disease) based on the class label "Dataset" in the column. There are 142 patient records for women and 441 patient records for men in this data collection.

Patients who are older than 89 are identified as being "90" years old
![dataset](https://github.com/NithinYadav01/Liver-Disease-Classifier/assets/152949300/2c223700-fcd3-4a65-977a-c9ddc5272a3c)
# Environment
We used Python 3.6 for this project and implemented the code in Jupyter Notebook
# Code
The code for this project is written in Python . The code is available in the liver-disease-EDA.ipynb file.
# Data Visualisation
![agedist](https://github.com/NithinYadav01/Liver-Disease-Classifier/assets/152949300/74ea8bd1-e50b-486a-86f5-469f1183790d)
# Count Plot
![count1](https://github.com/NithinYadav01/Liver-Disease-Classifier/assets/152949300/6e1cda42-0317-4698-b3c3-3fbc14bde951)
# Correlation
![correlation](https://github.com/NithinYadav01/Liver-Disease-Classifier/assets/152949300/6ea8e144-21f3-4b9d-bee7-f860f9ce46d8)
# Results
The Support Vector Classifier (SVC) has been found to be the most effective for liver disease prediction. Its superior performance over other algorithms such as KNN, random forest, and logistic regression, indicates that SVC is the best choice for live disease prediction. Its ability to efficiently handle large datasets, its robustness to noise, and its high accuracy make it an ideal choice for such applications. With SVC, we can make more accurate predictions in real time, which can help in early detection of diseases and improve patient outcomes
               precision   recall  f1-score   support

           0       0.36      0.47      0.41        38
           1       0.84      0.77      0.80       137

    accuracy                           0.70       175
   macro avg       0.60      0.62      0.61       175
weighted avg       0.74      0.70      0.72       175

       




