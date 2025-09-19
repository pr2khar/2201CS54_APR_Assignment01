#### Created by : Prakhar Shukla
#### Roll Number : 2201CS54

## Diabetes Classification using Logistic Regression & SVM

This project trains and evaluates two supervised machine learning models, Logistic Regression and a Support Vector Machine (SVM) with an RBF kernel, for the task of diabetes classification. The goal is to compare their performance on a clinical dataset.

#### Workflow
* **Dataset**: The models were trained on a public diabetes dataset with 1,000 patient records and 11 predictive features. The objective is to classify patients as Diabetic (Y), Non-diabetic (N), or Pre-diabetic (P).
* **Preprocessing**: The data was rigorously cleaned by removing outliers using the Interquartile Range (IQR) method, encoding categorical features, scaling numerical data with `StandardScaler`, and imputing missing values.
* **Training**: `GridSearchCV` with 5-fold cross-validation was used to find the optimal hyperparameters for both models.

#### Results
The models were evaluated on a clean, unseen test set, yielding the following results:
* **RBF SVM**: Achieved the highest accuracy at **97.04%**.
* **Logistic Regression**: Performed well with
