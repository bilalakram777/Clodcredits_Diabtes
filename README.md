Diabetes Prediction Using Machine Learning
This project applies machine learning algorithms to predict whether a person has diabetes based on medical diagnostic data. The diabetes dataset contains various features such as glucose levels, blood pressure, BMI, and age to determine the likelihood of a person having diabetes.

Key Steps:
Data Preprocessing:

Loaded the diabetes dataset (diabetes.csv).

Split the data into features (X) and target (y), where the target is the Outcome column indicating diabetes presence.

Scaled the features using StandardScaler to improve model performance.

Model Building:

Trained a K-Nearest Neighbors (KNN) classifier with n_neighbors=5 to predict the outcome.

Evaluated the model's performance based on accuracy, precision, and recall metrics.

Model Evaluation:

The model was evaluated on the test set, and performance metrics (accuracy, precision, recall) were printed for evaluation.

Requirements:
Python 3.x

pandas

scikit-learn
