Employee Salary Classification using Machine Learning

This project predicts whether an individual earns ≤50K or >50K per year based on demographic and work-related attributes from the Adult Income Dataset. The main goal is to build a reliable classification system by applying different machine learning models, comparing their performance, and selecting the best one for deployment.

The dataset is first cleaned and preprocessed by handling missing values, removing irrelevant categories, encoding categorical features, and scaling numerical features using MinMaxScaler. After preprocessing, multiple machine learning algorithms such as K-Nearest Neighbors, Logistic Regression, Support Vector Machine, Multi-Layer Perceptron, Random Forest, and Gradient Boosting are trained and evaluated. Based on accuracy and other evaluation metrics, the Gradient Boosting Classifier is selected as the best-performing model with approximately 86% accuracy.

The final model is saved using joblib and deployed through a Streamlit web application, which allows users to input data for real-time prediction and also upload CSV files for batch prediction. The application is designed to be simple, interactive, and easy to use.

Tech Stack: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Streamlit, Joblib, Pyngrok.
