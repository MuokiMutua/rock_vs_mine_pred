# Sauna Rock vs Mine Rock Classification Project

## Problem Statement

In this project, we aimed to compare **sauna rocks** and **mine rocks** based on their thermal properties (such as heat retention and durability). The primary objective was to classify these two types of rocks based on their features using machine learning techniques. The data collected includes various physical properties of both types of rocks, such as temperature retention and durability.

Given the increasing need for efficient materials in various industries (e.g., sauna construction, mining, and material science), understanding how different rocks perform under high temperatures can offer insights into their practical applications. This project addresses the gap in comparing the performance of sauna rocks and mine rocks using machine learning.

## Dataset

The dataset used in this project consists of various features related to the physical properties of both sauna and mine rocks, such as:
- **Heat Retention**: The amount of heat the rock retains over time.
- **Durability**: The resistance of the rock to cracking or breaking.
- **Cracking**: A binary variable indicating whether the rock cracks under high temperatures.

These features are used to classify whether a rock is a **sauna rock** or a **mine rock**.

## Approach

### 1. Data Preprocessing
- **Data Cleaning**: Missing values were handled, and any irrelevant columns were removed.
- **Feature Engineering**: The dataset was explored to identify important features that contribute to classification.
  
### 2. Model Selection
Several classification algorithms were tested, and performance metrics were compared. We chose to use **NuSVC (Support Vector Classification)** for its ability to perform well in high-dimensional spaces and its efficiency in binary classification tasks.

### 3. Model Evaluation
The models were trained on the training set (`X_train` and `y_train`) and evaluated on the test set (`X_test` and `y_test`). The performance of each model was summarized using key metrics such as accuracy, precision, recall, and F1-score. 

## Solution

We achieved an accuracy of **98%** using the **NuSVC** classifier. The high accuracy indicates that the model effectively distinguishes between sauna rocks and mine rocks based on their thermal properties.

### Why NuSVC?
NuSVC was chosen for the following reasons:
- **High performance**: NuSVC performs well with binary classification tasks and handles non-linear relationships between features effectively.
- **Flexibility**: It allows tuning the trade-off between the classification error and margin size, which is important when the dataset might have some noise or overlaps between classes.
  
### Results
- **Accuracy**: 98%  
This shows that the model is highly effective in classifying the two types of rocks based on the provided features.

## Conclusion

This project demonstrates the effectiveness of machine learning, specifically the **NuSVC** classifier, in solving a real-world problem of classifying rocks based on their thermal properties. The high accuracy achieved suggests that **NuSVC** is a good model for this classification task. Future improvements could involve testing additional classifiers, tuning hyperparameters, or using more advanced feature selection techniques to further enhance the model's performance.


