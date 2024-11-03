# To predict whether the person has heart disease or not using Scikit-Learn and compare the different models
## Heart Disease Prediction using Scikit-Learn 🫀

This project aims to predict the likelihood of a person having heart disease using machine learning models from Scikit-Learn. We explore multiple classification algorithms, compare their performance, and identify the best model for this task.

### Project Overview
- **Objective**: Predict whether a person has heart disease based on medical attributes such as age, blood pressure, cholesterol levels, and more.
- **Models Used**:
  - **Logistic Regression**: A simple yet effective model for binary classification.
  - **K-Nearest Neighbors (KNN)**: A distance-based classifier that is sensitive to feature scaling.
  - **Random Forest Classifier**: An ensemble model known for its accuracy and ability to handle feature importance.

### Model Evaluation Techniques
- **Train-Test Split**: To divide data for training and testing, ensuring model evaluation on unseen data.
- **Cross-Validation**: Applied to assess model robustness and mitigate variance in results.
- **Hyperparameter Tuning**:
  - **RandomizedSearchCV** and **GridSearchCV** are used to optimize model hyperparameters for best performance.
- **Performance Metrics**: Each model is evaluated on:
  - **Confusion Matrix**: Visualizes true positives, false positives, true negatives, and false negatives.
  - **Classification Report**: Provides detailed metrics like precision, recall, and F1-score.
  - **Precision, Recall, F1-Score**: Key metrics for evaluating classification performance, especially useful in healthcare settings where false negatives or positives carry different implications.

### Conclusion
The project identifies the best model for heart disease prediction by comparing accuracy and other metrics, providing valuable insights into model selection for healthcare applications.
