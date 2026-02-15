#  Task 16: Hyperparameter Tuning using GridSearchCV

## Objective

The goal of this task is to understand and implement hyperparameter
tuning using GridSearchCV in Scikit-learn. This helps in improving the
performance of machine learning models by finding the best combination
of parameters.

##  Tools & Technologies Used

-   Python
-   Scikit-learn
-   Pandas
-   NumPy
-   Google Colab


##  Dataset Used

Breast Cancer Dataset (loaded directly from sklearn library)

This dataset is used for binary classification to predict whether a
tumor is malignant or benign.


##  Steps Performed

1.  Imported required libraries
2.  Loaded the Breast Cancer dataset
3.  Performed train-test split
4.  Built a default SVM model
5.  Evaluated default model accuracy
6.  Defined hyperparameter grid (C, gamma, kernel)
7.  Applied GridSearchCV with 5-fold cross-validation
8.  Extracted best parameters
9.  Evaluated tuned model
10. Compared default vs tuned model performance


##  Hyperparameters Tuned

-   C (Regularization Parameter)
-   Gamma (Kernel coefficient)
-   Kernel (RBF)

GridSearchCV tested multiple combinations and selected the best model
based on cross-validation accuracy.


##  Results

The tuned SVM model performed better than the default model.

✔ Default Model Accuracy: Improved after tuning\
✔ Best Parameters: Selected using cross-validation\
✔ Tuned Model Accuracy: Higher compared to default


##  Conclusion

Hyperparameter tuning plays a crucial role in improving machine learning
model performance. GridSearchCV provides a structured and reliable way
to test multiple parameter combinations and select the best model using
cross-validation.

This task enhanced my understanding of model optimization techniques and
evaluation strategies.

## Output
<img width="712" height="343" alt="Image" src="https://github.com/user-attachments/assets/d03aa146-a2dd-41dc-b5ec-b8d6a6e5e354" />
<img width="683" height="331" alt="Image" src="https://github.com/user-attachments/assets/388e7b23-1522-4a19-b799-291b6a662c6e" />
<img width="802" height="656" alt="Image" src="https://github.com/user-attachments/assets/591d491e-5944-4540-b031-34a4cb5706c3" />