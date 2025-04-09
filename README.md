# Exploratory-Data-Analysis-and-Machine-Learning-with-Python

This project focuses on performing regression analysis on a dataset containing detailed specifications of CPUs and GPUs. The dataset includes features such as base clock speed, maximum clock speed, TDP (Thermal Design Power), memory, architecture, manufacturer, and pricing in both USD and INR. The primary objective is to understand how these hardware specifications influence the overall pricing of a product and to build predictive models that can estimate price based on these attributes.

To prepare the data for analysis, missing values were handled using mean imputation, and the features were scaled using normalization techniques such as StandardScaler and MinMaxScaler. Categorical features were encoded appropriately to ensure compatibility with regression algorithms. After preprocessing, feature selection techniques like SelectKBest were used to identify the most influential features contributing to price prediction.

The dataset was then split into training and testing subsets to validate model performance. Several regression algorithms were applied, including Linear Regression, Decision Tree Regressor, Random Forest Regressor, and Support Vector Regressor. Each model was trained and tested to evaluate its ability to predict prices accurately.

To measure model effectiveness, evaluation metrics such as R² Score, Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE) were calculated. These metrics provided insights into the prediction accuracy and generalization capability of each model. Among the tested models, Random Forest Regressor demonstrated robust performance due to its ability to handle complex, non-linear relationships.

This project highlights the importance of data preprocessing and feature selection in building effective regression models. By analyzing the pricing patterns of CPUs and GPUs, the project provides a foundational understanding of how specific hardware features impact market value. It also serves as a practical example of applying machine learning regression techniques to real-world datasets for predictive analytics.
