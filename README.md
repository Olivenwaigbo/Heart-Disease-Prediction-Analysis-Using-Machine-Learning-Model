# Heart Disease Prediction Analysis Using Machine Learning Model

This repository contains code for analyzing and predicting heart disease using a Random Forest Classifier model. After evaluating several machine learning algorithms, including Logistics Regression, Support Vector Machines (SVM), K-Nearest Neighbors Classifier, and Decision Tree Classifier, we have determined that the Random Forest Classifier is the best fit for this specific task.


## Introduction
Heart disease is a significant health concern affecting millions of people worldwide. Early detection and accurate prediction of heart disease can help in timely intervention and improved patient outcomes. Machine learning techniques provide an effective approach to analyze heart disease data and predict the presence or absence of the disease based on various features.
In this project, we have employed the Random Forest Classifier model to analyze and predict heart disease. The Random Forest algorithm combines the predictions of multiple decision trees to produce accurate and robust results.

## Features
The dataset used for this project contains various features that are relevant to heart disease analysis. Some of the key features include:

Age: The age of the patient.
Sex: The gender of the patient (1 = male, 0 = female).
Chest Pain Type: The type of chest pain experienced by the patient.
Resting Blood Pressure: The patient's resting blood pressure.
Cholesterol: The patient's cholesterol level.
Fasting Blood Sugar: Whether the fasting blood sugar is higher than 120 mg/dl or not (1 = true, 0 = false).
Resting Electrocardiographic Results: Results of the resting electrocardiogram.
Maximum Heart Rate Achieved: The maximum heart rate achieved during exercise.
Exercise Induced Angina: Whether the patient experienced angina during exercise (1 = yes, 0 = no).
ST Depression Induced by Exercise: ST depression induced by exercise relative to rest.
Slope: The slope of the peak exercise ST segment.
Number of Major Vessels: The number of major vessels colored by fluoroscopy.
Thal: A blood disorder called thalassemia.
These features help in understanding the factors that contribute to heart disease and aid in predicting the presence of heart disease in patients.


## Dataset
The dataset used for training and testing the heart prediction model is  included in this repository. The dataset  includes features such as age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, Resting Electrocardiographic Results, Maximum Heart Rate Achieved,Exercise Induced Angina, ST Depression Induced by Exercise Relative to Rest, Number of Major Vessels Colored by Fluoroscopy, and Thalassemia.

## Model Selection
After careful evaluation and comparison of several machine learning algorithms, we have selected the Random Forest Classifier as the best fit for this heart disease analysis and prediction task. The Random Forest algorithm provides the following advantages:
- Ensemble Method: The Random Forest algorithm combines multiple decision trees, reducing the risk of overfitting and improving prediction accuracy.
- Feature Importance: Random Forest provides a measure of feature importance, allowing us to understand which features contribute the most to the prediction.
- Robustness: Random Forest is less sensitive to noise and outliers in the data, making it more robust than some other algorithms.
By employing the Random Forest Classifier model, we aim to achieve accurate predictions for heart disease and contribute to early detection and intervention, ultimately improving patient outcomes.
Please refer to the code files and documentation for more details on the implementation and analysis.

## Usage
Dataset Usage
To conduct the heart disease analysis and prediction, we utilized a pre-existing dataset that contains information on various attributes related to heart disease. The dataset was obtained from a reliable source and has been preprocessed to ensure its quality and consistency.

The dataset is split into two subsets: a training set and a test set. The training set is used to train the Random Forest Classifier model, while the test set is used to evaluate the model's performance. By analyzing the patterns and relationships within the training set, the model learns to make accurate predictions on unseen data.
## Requirements
run this project, you need the following dependencies:
Python (version 3.6 or later)
NumPy
Pandas
scikit-learn
Ensure that these dependencies are installed in your environment before running the code.

## Summary
In this project, we have successfully analyzed and predicted heart disease using a Random Forest Classifier model. By considering various features related to heart health, the model can provide valuable insights and predictions to assist in medical diagnoses.

The Random Forest Classifier model demonstrates robust performance in terms of accuracy and generalization. However, it is essential to note that no model is perfect, and further research and validation are necessary to ensure its reliability in practical medical settings.

We hope that this heart disease analysis and prediction system can contribute to improving patient care and assisting healthcare professionals in making informed decisions.
Note: This project is for educational and research purposes only and should not be used as a substitute for professional medical advice or diagnosis. Always consult a healthcare professional for medical concerns or decisions.

## AUTHOR
👤 **Nwaigbo Olive**
- Github:  [@olivenwaigbo](https://github.com/Olivenwaigbo?tab=following)    

- LinkedIn:  [olive nwaigbo](https://www.linkedin.com/in/olive-nwaigbo-95707a151)

## 🤝**Contributing**
Contributions to this project are welcome. If you find any issues or have ideas for improvements, please open an issue or submit a pull request. We appreciate your feedback and collaboration.


## **Show your support**
Give a ⭐️ if you like this project

## **Acknowledgements**
- Thank you Data Thinkers  for guiding me through this project.
## 📝 License 
This project is [MIT](./MIT.md) licensed

