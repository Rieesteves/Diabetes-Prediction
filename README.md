# Diabetes-Prediction

1. Loading the Dataset : The code begins by loading a diabetes dataset using pandas. This
dataset contains information about patients, including features like "Number of Pregnancies,"
"Glucose level," "Blood Pressure," and others. The dataset also includes an "Outcome" column,
where 1 indicates diabetes, and 0 indicates no diabetes.
2. Training the Naive Bayes Classifier :
- It initializes a Naive Bayes classifier of the Gaussian Naive Bayes type using `GaussianNB()`
from scikit-learn.
- The classifier is trained using the features (X) and target labels (y) from the dataset. The
features (X) are all columns except the "Outcome" column, and the target labels (y) are the
"Outcome" column.
3. Input and Prediction :
- The code defines a GUI interface where users can input values for various features, such as
the number of pregnancies, glucose level, blood pressure, and so on. The user's input values
are collected and used to make a prediction.
4. Making Predictions :
- When the user clicks the "Predict" button, the input values are collected and used to form a
feature vector for a patient.
- The trained Naive Bayes classifier (`clf`) is used to predict whether the patient is diabetic or
non-diabetic based on the feature vector.
- If the prediction is 1, it means the patient is predicted to be diabetic; if it's 0, the patient is
predicted to be non-diabetic.

_The Naive Bayes classifier, in this case, is used as a machine learning model to make
predictions based on the provided patient data. It's trained on historical data to learn patterns
and relationships between the input features and the diabetes outcome, and then it uses that
knowledge to make predictions for new patient data._
