Flight Price Prediction with Random Forest 🚀
Overview
This project aims to predict flight prices using a Random Forest Regressor. By leveraging the power of ensemble learning and applying k-fold cross-validation, the model is optimized for accuracy and robustness. The dataset is preprocessed and imputed for missing values, and the model's performance is evaluated based on the R-squared score.

Key Features
✅ Random Forest Regressor: A powerful ensemble learning model used for predicting continuous variables like flight prices.
✅ Cross-Validation: Implements 5-fold cross-validation to evaluate model performance and prevent overfitting.
✅ R-squared Metric: Uses R-squared to assess the quality of predictions and model fit.
✅ Efficient Model Training: The model is trained on imputed data for better accuracy and handling of missing values.
✅ Scalable: The Random Forest algorithm is suitable for large datasets and can easily be extended to other use cases.
Technologies Used
Python 3.x
scikit-learn: For machine learning models and evaluation metrics
pandas and numpy: For data manipulation and preprocessing
Random Forest Regressor: For predicting flight prices
Cross-validation: For model evaluation
Results & Insights
📌 Cross-validated R-squared scores: The model demonstrates high predictive accuracy across multiple folds, with R-squared scores ranging from 0.82 to 0.88.
📌 Final R-squared score: After training on the entire dataset, the Random Forest model achieved an R-squared score of 0.8542, indicating that it can explain 85.42% of the variance in flight prices.
📌 Imputed Data Handling: The model uses imputed data to handle missing values effectively, ensuring that the predictions are not biased by incomplete information.
Future Work
🔹 Hyperparameter Tuning: Explore tuning the Random Forest parameters like n_estimators and max_depth to improve model performance further.
🔹 Feature Engineering: Experiment with additional features like flight duration, airline, or departure time to enhance the model’s predictive power.
🔹 Comparison with Other Models: Compare the performance of Random Forest with other models like Gradient Boosting or XGBoost to assess which provides the best results for flight price prediction.
Installation
Prerequisites
Python 3.x
pip (Python package installer)
