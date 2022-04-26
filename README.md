# Rain-Prediction
A project on predicting whether it will rain tomorrow or not by using the Rainfall in Australia dataset
This project is tested over lot of ml models like catboost, xgboost, random forest, support vector classifier, etc..
Out of these models catboost performed very well giving an AUC score around and ROC score of 89 far better than others.
Here due to my system compatibility is very low. So I havent done hyperparameter tuning. But it is highly recommended to do it if possible.

# Testing values

# Rainy Day: 
![Predictor Values for Rainy Day]
# Sunny Day:
![Predictor Values for Sunny Day]

# Tech Stack
* Front-End: HTML, CSS, Bootstrap
* Back-End: Flask
* IDE: Jupyter notebook, VS Code

# Workflow

# Data Collection: 
[Rainfall Prediction in Australia dataset](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package) from Kaggle
# Data Preprocessing: 
* Missing Values Handled by Random Sample imputation to maintain the variance
* Categorical Values like location, wind direction are handled by using Target guided encoding
* Outliers are handled using IQR and boxplot
* Feature Selection and was done but didnt perform well it can be seen in testing_notebook/Prediction.ipynb
* Feature Scaling didnt give a lot of difference it also can be seen in testing_notebook/RainPrediction1.ipynb
* Imbalanced Dataset was handled using SMOTE(synthetic minority oversampling technique)
# Model Creation:
* Different types of models were tried like catboost, random forest, logistic regression, xgboost, support vector machines, knn, naive bayes.
* Out of these catboost, random forest and support vector machines were top 3
* The conclusion were made using classification metrics. roc curve and auc score
# Model Deployment
* The model is deployed using Flask at Heroku server at the [link]

# If you like this project please do give a star. I am also giving my LinkedIn profile. If you want we can connect there too
[https://www.linkedin.com/in/metta-venkata-chaitanya-bharadwaj-bb814b208](https://www.linkedin.com/in/metta-venkata-chaitanya-bharadwaj-bb814b208/)
[https://www.linkedin.com/in/yashwanth-kommuri-b36392229/](https://www.linkedin.com/in/yashwanth-kommuri-b36392229/)



