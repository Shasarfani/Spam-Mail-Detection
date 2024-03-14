In this project, logistic regression was employed to construct a email spam prediction model. The exploratory data analysis revealed an imbalance in the original dataset's outcome variable, with 4825 observations classified as genuine and 747 as spam emails. To address this issue, the SMOTE oversampling technique was implemented, resulting in a more balanced dataset with 3371 observations for each class.

Upon comparing performance metrics, it was observed that the model with SMOTE exhibited slightly higher accuracy and recall, albeit with a slight decline in precision. Remarkably, the AUROC curve performance remained consistent despite the oversampling. 

A higher recall would assist us in identifying all the spam emails, while a higher precision indicates how effectively the model performed with respect to the positive classes. Depending on the business objective, we can choose a metric that offers the most value and cost benefit.

Furthermore, I created a predictive system to classify emails as spam or genuine based on user input. However, it is essential to note that the training data's size may limit the model's ability to accurately predict all spam emails. To improve real-time prediction accuracy, continuous training with larger datasets is recommended.

In summary, the study underscores the effectiveness of logistic regression in spam detection and highlights the importance of addressing class imbalance through techniques like SMOTE. Additionally, ongoing efforts to enhance the model's predictive capabilities with larger datasets are crucial for achieving more accurate results in real-time spam detection scenarios.
