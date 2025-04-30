# Diabettes-prediction-using-machine-learning
# Diabetes Prediction using Machine Learning

This project aims to predict whether a person is diabetic or not using medical diagnostic data. A feedforward neural network is built using TensorFlow/Keras, trained on the popular Pima Indians Diabetes dataset.

---

## Project Highlights

-  Achieved ~85% accuracy using a Neural Network model
-  Preprocessing with KNN Imputer and feature scaling
-  Balanced dataset using SMOTE (Synthetic Minority Oversampling)
-  Trained model for 30 epochs with accuracy & loss visualization
-  Dataset: [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

---

##  Dataset Information

The dataset consists of 768 records and 8 medical attributes:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age
- Outcome (0 = Non-diabetic, 1 = Diabetic)

---

##  Technologies Used

- Python
- TensorFlow / Keras
- scikit-learn
- imbalanced-learn (SMOTE)
- Matplotlib / NumPy / Pandas

---

##  Model Architecture

```plaintext
Input Layer (8 features)
↓
Dense(32, activation='relu')
↓
Dense(16, activation='relu')
↓
Dense(1, activation='sigmoid') → Output (0 or 1)
