# Toxic-Comment-Classifier
A Multi-Label Text Classification Project that uses Convolutional Neural Networks to identify different levels of toxicity present in a comment.

# Dataset
Toxic Comment Classification Challenge Dataset([link](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge))

# Code
Model Building and Hyperparamter Tuning Notebook([link](https://www.kaggle.com/abhishek2195/toxic-comment-cnn-modeling-single))
Note: During Hyperparameter Tuning, I have scaled different features of CNN by varying one or two features and keeping others constant so that search space doesn't go into multiple dimensions. Different parameters are tuned in different versions of the same notebook.

Final Notebook with Data Exploration, Data Cleaning, Feature Engineering and Modeling([link](https://www.kaggle.com/abhishek2195/toxic-comment-cnn-modeling-final?scriptVersionId=42997055))

# Evaluation
Metric: AUC-ROC\
Score on Training Data:0.9995045096676135\
Score on Validation Data:0.9742768436815327\
Public Leaderboard Score:0.96715\
Private Leaderboard Score:0.96744
