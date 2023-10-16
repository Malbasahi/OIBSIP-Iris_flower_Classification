# Iris_flower_Classification
The project is focused on building and evaluating machine learning models for the classification of iris flower species using the Iris dataset. This dataset contains measurements of four features (sepal length, sepal width, petal length, and petal width) for three different iris species (setosa, versicolor, and virginica). The main objective is to develop, fine-tune, and assess the performance of various classification models.

# key components and tasks in the project:

Data Preprocessing:
=
The project begins by loading the Iris dataset from a CSV file.
Feature scaling is applied to standardize the feature values.
Data is visualized through box plots and a pair plot to gain insights into feature distributions and relationships among the species.

Model Selection and Hyperparameter Tuning:
=
Three different classification models are considered: Random Forest, Decision Tree, and Support Vector Machine (SVM).
Hyperparameter tuning is performed for the Random Forest model to optimize its performance.

Cross-Validation and Evaluation:
=
Cross-validation is conducted to assess the generalization performance of each model.
The models' accuracy is evaluated on a test dataset to gauge their predictive power.

Feature Importance Analysis:
=
The feature importance of the Random Forest model is determined using permutation importance.
Visualization of feature importance is presented to understand which features contribute the most to the classification task.
Confusion Matrix and Visualization:

A confusion matrix is visualized to comprehend how well the models perform in terms of true positives, true negatives, false positives, and false negatives.

Learning Curves
=
Learning curves are generated to study the relationship between training set size and model performance. This aids in identifying overfitting or underfitting issues.

Principal Component Analysis (PCA):
=
Principal Component Analysis is applied to reduce the dimensionality of the dataset to two principal components.
Decision boundaries for both Decision Tree and Random Forest models are visualized using PCA-transformed data.
Comprehensive Model Evaluation:

In addition to accuracy, precision, recall, and F1-score metrics are computed for each model.
The performance of the models is systematically compared.

Visualization of Model Decision Boundaries:
=
The decision boundaries of the Decision Tree and Random Forest models are visually represented after applying PCA.

# Result: 

The results from the evaluation of the three machine learning models are as follows:
=
Random Forest:

Accuracy: 95.56%
Precision: 0.9615
Recall: 0.9556
F1-Score: 0.9553
Decision Tree:

Accuracy: 93.33%
Precision: 0.9347
Recall: 0.9333
F1-Score: 0.9332
SVM (Support Vector Machine):

Accuracy: 93.33%
Precision: 0.9347
Recall: 0.9333
F1-Score: 0.9332
Random Forest achieved the highest accuracy at 95.56%, indicating that it correctly predicted the iris flower species in the test data with the highest rate among the three models. This model also has the highest precision, recall, and F1-Score, making it the best overall performer in this evaluation.

Decision Tree and SVM had slightly lower accuracy, precision, recall, and F1-Scores, but their performance is still quite competitive.

In summary, the Random Forest model is the top-performing model, while both the Decision Tree and SVM models provide reasonable results. The choice of the best model may depend on specific use case requirements and the trade-offs between precision, recall, and other factors.







