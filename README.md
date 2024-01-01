# Diabetes-130-US-Hospitals

# Classifying Readmissions using Diabetes Data (Diabetes 130-US Hospitals)

## 1. Summary
Utilizing the Jupyter Notebook interactive web application and the programming language Python, the machine learners group of the CS 178 course at the University of California Irvine explored the Diabetes 130-US Hospitals dataset. We investigated four classification methods: Feedforward Neural Networks, K Nearest Neighbors, Logistic Regression, and Gradient-Boosted Decision Trees. Gradient-Boosted Decision Trees were the most effective, achieving a classification accuracy of 61.3%.

## 2. Data Description
The "Diabetes 130-US hospitals for years 1999-2008" dataset contains 50 columns of data with 101,766 rows/instances. During exploration, we visualized data, generated summary statistics, and performed feature engineering to enhance dataset quality for modeling.
<img width="554" alt="tQ2gfTda7ERBKd_Av6cX7wyoa4vD9s7XLrvkJxEPgQpGO1K4H0-Di_-SzY1htrL-Ov78v-Wj2wlQyhU1CM4AQikln3kqoMWDP7U4CW_tn5njKHB-3klmb15BX0vg" src="https://github.com/jpyoo/Diabetes-130-US-Hospitals/assets/58375171/5d8e92de-fe2e-4f5b-82a1-3010dbc439d9">

## 3. Classifiers
We explored four classifiers: Feedforward Neural Networks, K Nearest Neighbors, Logistic Regression, and Gradient-Boosted Decision Trees. Detailed hyperparameter information is available in our [Jupyter Notebook](https://github.com/sebseb100/DiabetesReadmissionClassificationModels).

## 4. Experimental Setup
We addressed missing data, replaced categorical values, and performed feature engineering. Dataset partitioning was done with training-test splits (70:30), (75,25), and (80,20). Columns with over 80% missing values were dropped. We explored hyperparameters for each classifier.

## 5. Experimental Results
- KNN: Accuracy - 54.24% (test), 54.39% (train)
- GBDT: Accuracy - 65.4% (test), 61.3% (train)
- Logistic Regression: Accuracy - 57.4% (test), 57.67% (train)
- Neural Networks: Accuracy - 60.18% (test), 59.37% (train)

## 6. Insight
Understanding dataset, feature processing, and effective visualization were crucial. Achieving low accuracy across models indicated the complexity of predicting diabetes readmission, emphasizing the abstract nature of medical data.

## 7. Team Contribution
- Sebu Eisaian: Logistic Regression, Feedforward Neural Network, Report Compilation.
- Jay Phil Yoo: Data Processing, Feature Engineering, GBDT Model Training.
- Jimmy Jin: K Nearest Neighbors, Model Analysis.

## Appendix
- Data missing values barchart
<img width="589" alt="Missingness" src="https://github.com/jpyoo/Diabetes-130-US-Hospitals/assets/58375171/6ad988ed-3a08-45cf-89bd-1a8cafd4ce57">

- Gradient boost min_leaf_sample exploring result
<img width="589" alt="0 394 -" src="https://github.com/jpyoo/Diabetes-130-US-Hospitals/assets/58375171/f12f7708-3b2d-49b6-bbde-e968d03ba671">

- Gradient Boosting max_depth exploring result
<img width="589" alt="Training Set" src="https://github.com/jpyoo/Diabetes-130-US-Hospitals/assets/58375171/1fd1d649-7efd-40cb-9a38-e92006b0a92b">

- Decision Tree paired features exploring results
<img width="589" alt="numb_features train_error" src="https://github.com/jpyoo/Diabetes-130-US-Hospitals/assets/58375171/539fb744-b437-4111-bed4-b6f8a098fd20">

- Gradient Boosting n_estimators exploring result
<img width="589" alt="Training Set" src="https://github.com/jpyoo/Diabetes-130-US-Hospitals/assets/58375171/5b9d47c4-ea92-4159-922a-39b8e52c8ba0">

- kNN Classifier Confusion Matrix
<img width="589" alt="True label" src="https://github.com/jpyoo/Diabetes-130-US-Hospitals/assets/58375171/c0fbdd49-61ef-4297-9dde-c1ce7b7e54b1">

- Gradient Boosting Classifier Confusion Matrix
<img width="589" alt="True label" src="https://github.com/jpyoo/Diabetes-130-US-Hospitals/assets/58375171/66a33b77-ef30-4401-9a5a-55f1a7ae8e4c">

- Logistic Regression Classifier Confusion Matrix
<img width="589" alt="True label" src="https://github.com/jpyoo/Diabetes-130-US-Hospitals/assets/58375171/0906e691-17a2-4ed3-b60a-b8ff8292023f">

- Neural Network Classifier Confusion Matrix
<img width="589" alt="F-GDpTO66ItEAOoAZrC6vHzHsuZq7ze1iYJTkdHJ1RwFXRUy_ipjwzn55cuctOd_-qGB1t3dRdj9H2bLnxlKlMCrrxXs8GLY7Auld6RR-0Jm57FfUOnDA6vbjEal" src="https://github.com/jpyoo/Diabetes-130-US-Hospitals/assets/58375171/25cba5cf-b07b-49dc-90a0-30a7bdaceffa">

