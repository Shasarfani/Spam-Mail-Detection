# Email Spam Prediction Model

This project focuses on the development of an email spam prediction model using logistic regression. 

## Overview
The initial exploratory data analysis revealed an imbalance in the dataset, with 4825 observations classified as genuine emails and only 747 as spam emails. To address this issue and improve model performance, the SMOTE (Synthetic Minority Over-sampling Technique) oversampling technique was implemented. This resulted in a more balanced dataset with 3371 observations for each class.

## Model Performance
Upon evaluating the model's performance metrics, it was found that the model with SMOTE exhibited slightly higher accuracy and recall, albeit with a slight decline in precision. However, the AUROC (Area Under the Receiver Operating Characteristic) curve performance remained consistent despite the oversampling.

## Metrics Consideration
A higher recall would assist in identifying all spam emails, while a higher precision indicates the model's effectiveness in classifying positive instances. The choice of metric depends on the specific business objectives, aiming to maximize value and cost benefits.

## Predictive System
Additionally, a predictive system was developed to classify emails as spam or genuine based on user input. However, it's important to note that the model's predictive accuracy may be limited by the size of the training data. Continuous training with larger datasets is recommended to improve real-time prediction accuracy.

## Conclusion
This project highlights the effectiveness of logistic regression in spam detection and emphasizes the importance of addressing class imbalance through techniques like SMOTE. Ongoing efforts to enhance the model's predictive capabilities with larger datasets are crucial for achieving more accurate results in real-time spam detection scenarios.
