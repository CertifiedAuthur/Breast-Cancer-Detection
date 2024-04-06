# Breast-Cancer-Detection

The breast Cancer Diagnosis Prediction project utilizes Support Vector Machines (SVM) with a Radial Basis Function (RBF) kernel to build a predictive model for diagnosing cancer patients. The dataset consists of various features related to tumor characteristics, such as radius, texture, perimeter, area, smoothness, and more. The goal is to classify patients into two categories: malignant (cancerous) or benign (non-cancerous) based on these features.

SVM with an RBF kernel is chosen due to its ability to handle non-linear decision boundaries effectively, making it suitable for complex classification tasks like cancer diagnosis. The model is trained on a labeled dataset where each instance is labeled as either malignant or benign.

The project involves several steps:

Data Preprocessing: The dataset is preprocessed, which may include handling missing values, encoding categorical variables, and scaling/normalizing numerical features.

Feature Selection: Features that are highly correlated with the target variable (diagnosis) are selected for model training to improve predictive accuracy.

Model Training: The SVM model with an RBF kernel is trained on the selected features using the labeled dataset.

Model Evaluation: The trained model's performance is evaluated using appropriate evaluation metrics such as accuracy, precision, recall, and F1-score. Cross-validation techniques may also be employed to ensure robustness.

Prediction: Once the model is trained and evaluated, it can be used to predict whether a patient is malignant or benign based on their tumor characteristics.

By accurately predicting cancer diagnosis, this project aims to assist healthcare professionals in making informed decisions regarding patient treatment and management. The predictive model provides valuable insights into identifying patients at risk of cancer, enabling early intervention and improving patient outcomes.
