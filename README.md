# CAR-PRICE-PREDICTION_acmegradePrj2

Summary :

Certainly! In this code, we have performed the following tasks:

    Data Loading and Inspection: Loaded the dataset "audi.csv" and performed exploratory data analysis (EDA) to understand basic statistics, information about the dataset, and check for missing values.

    Feature Selection and Preprocessing: Selected relevant features for the prediction task and handled categorical variables using label encoding and one-hot encoding.

    Splitting Data and Feature Scaling: Split the dataset into training and testing sets, and performed feature scaling using StandardScaler.

    Model Selection and Training: Selected multiple regression models (Random Forest, Linear Regression, CatBoost), performed hyperparameter tuning for Random Forest using RandomizedSearchCV, and trained the models on the training data.

    Model Evaluation: Evaluated the performance of each model using metrics such as R2 Score, Mean Absolute Error, and Mean Squared Error on the testing data.

    Model Saving and Loading: Saved the best Random Forest model to a file using pickle and loaded the saved model from the file.

    Example Prediction: Made an example prediction using the loaded model on a sample data point.

    Saving Model to Disk: Saved a model to a file named 'deploy_GB.pkl' using pickle.

Overall, the code demonstrates the process of building, training, evaluating, and deploying machine learning models for predicting car prices based on various features.
