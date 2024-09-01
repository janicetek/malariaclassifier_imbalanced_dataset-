[Cell Image Classification with CNN]

[Model Details:]
Framework: TensorFlow
Model Type: 2D Convolutional Neural Network (CNN)
Purpose of model: Classify images as parasitised or uninfected
Purpose of project: To investigate the impact of dataset imbalance on the model's performance, particularly focusing on how it affects classification Accuracy for the minority class (infected cells).


[Overview of project:]
This project involves the development of a Convolutional Neural Network (CNN) Image Classification model using TensorFlow to classify cell images into two categories: parasitised and uninfected. 


[Dataset Information:]
The dataset used in this study is intentionally imbalanced:

Infected cells: Approximately 25% of the dataset
Uninfected cells: Approximately 75% of the dataset

This imbalance is designed to test whether an imbalanced dataset results in lower accuracy for the minority class.


[Objective:]
The key research question addressed in this study is:

"Should accuracy be the sole metric for determining a model's performance, especially in cases of dataset imbalance?"

Given the imbalance in the dataset, we anticipate that the model might exhibit a classification bias towards the majority class (uninfected cells). 

This study aims to evaluate this hypothesis and explore the effectiveness of alternative performance metrics like Precision instead of Accuracy, particularly in cases of dataset imbalance.

