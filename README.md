# Random-Forest-based-Cuisine-Prediction
This repository contains the code and data for a machine learning project aimed at predicting the cuisine type of a dish based on its ingredient list. The dataset includes images of food and information about it. This project focuses on a multi-class classification task to determine the top 5 cuisines from the given ingredient lists.

Introduction
The goal of this project is to build a machine learning model that can accurately predict the cuisine type of a dish based on its ingredients. The original dataset contains a diverse set of cuisines, which makes the classification task challenging. By focusing on the top 5 cuisines with the most data, we aim to improve the model's accuracy.

Dataset
The dataset used in this project can be downloaded from the following link:
https://github.com/MLEndDatasets/Yummy
The dataset contains images labeled with cuisine types and their corresponding ingredient lists. For this project, we only utilize the ingredient information.

Data Preprocessing
Missing values in the dataset were handled appropriately to ensure data quality. Various preprocessing steps were applied to prepare the data for model training, including:

Handling missing values
Normalizing ingredient lists
Encoding categorical variables

Feature Engineering
Feature engineering was performed to transform the ingredient lists into a suitable format for model training.

Model Training
A Random Forest classifier was initially trained on the entire dataset, achieving an accuracy of 53%. Due to the diverse set of cuisines and the imbalance in the number of data points per cuisine, we focused on the top 5 cuisines with the most data. This approach improved the model accuracy to 75%.

To further address class imbalance, we adjusted the class weights to give lower weight to classes with a high number of data points. This adjustment improved the model accuracy by an additional 3%.

Results
The final Random Forest classifier achieved the following performance:

Accuracy: 78%

We welcome contributions to this project! If you have any ideas, suggestions, or bug fixes, please open an issue or submit a pull request.
