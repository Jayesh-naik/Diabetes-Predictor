# Diabetes-Predictor
This project implements a Machine Learning model to predict whether a person is likely to have diabetes based on medical diagnostic data. The model is built using Python and the Scikit-learn library and is trained on the Pima Indians Diabetes Dataset.

The dataset contains several health-related features such as number of pregnancies, glucose level, blood pressure, skin thickness, insulin level, body mass index (BMI), diabetes pedigree function, and age. These features are used as inputs to predict the target variable, which indicates whether a patient is diabetic (1) or not diabetic (0).

The project follows a standard Machine Learning workflow. First, the dataset is loaded and explored using Pandas and NumPy. Then the data is preprocessed by separating features and labels and applying feature scaling using StandardScaler to normalize the values. The dataset is then divided into training and testing sets using the train_test_split method.

A Support Vector Machine (SVM) classifier with an RBF kernel is used to train the model. SVM is chosen because it performs well for classification problems with complex decision boundaries. After training, the model is evaluated using accuracy score, precision, recall, and F1-score to measure its performance.

The model achieves an accuracy of approximately 76% on the test dataset. The classification report provides additional insights into how well the model identifies diabetic and non-diabetic patients.

This project demonstrates the complete process of building a Machine Learning classification model, including data preprocessing, model training, evaluation, and interpretation of results.

Technologies used in this project include Python, NumPy, Pandas, Scikit-learn, and Google Colab.

This project is intended for learning purposes and serves as an example of how Machine Learning can be applied to healthcare-related prediction tasks.
