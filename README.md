# AI_ML_Task5

## Ensemble Learning, Model Optimization & ML Pipeline

This is my **Artificial Intelligence and Machine Learning - Task 5** project.

In this project, I worked with the Breast Cancer dataset and implemented different machine learning models to understand how their performance changes when we use ensemble techniques and hyperparameter tuning.

## What I Did

In this project, I performed the following steps:

- Loaded the Breast Cancer dataset using Scikit-learn
- Split the dataset into training and testing data
- Applied feature scaling
- Built a Logistic Regression model as a baseline
- Built a Random Forest Classifier
- Built a Gradient Boosting Classifier
- Compared the performance of different models
- Used GridSearchCV for Random Forest hyperparameter tuning
- Evaluated the final model using different classification metrics

## Dataset

I used the Breast Cancer dataset available in Scikit-learn.

The dataset contains:

- 569 samples
- 30 features
- Classification target

I used an 80:20 ratio for training and testing the data.

## Models Used

### Logistic Regression

I used Logistic Regression as the baseline model so that the performance of the ensemble models could be compared with a simple classification model.

### Random Forest

Random Forest was used to understand ensemble learning with multiple decision trees.

### Gradient Boosting

Gradient Boosting was implemented to see how a boosting-based ensemble model performs on the same dataset.

### Optimized Random Forest

I used GridSearchCV to find better Random Forest parameters using cross-validation.

## Hyperparameter Tuning

For Random Forest, I experimented with:

```text
n_estimators
max_depth
min_samples_split

GridSearchCV was used with 5-fold cross-validation to find the better combination of these parameters.

Model Evaluation

I compared the models using:

Accuracy
Precision
Recall
F1-score

I also created an accuracy comparison graph to make the model performance easier to understand.

Project Workflow
Load Dataset
      ↓
Train-Test Split
      ↓
Feature Scaling
      ↓
Logistic Regression
      ↓
Random Forest
      ↓
Gradient Boosting
      ↓
GridSearchCV
      ↓
Model Comparison
      ↓
Final Evaluation

# Tools Used
Python
VS Code
Jupyter Notebook
Pandas
NumPy
Matplotlib
Scikit-learn
Files
AI_ML_Task5/
│
├── AI_ML_Task5.ipynb
├── README.md
└── Task_5_Report.pdf

What I Learned

While working on this task, I got practical understanding of ensemble learning and how multiple models can be used for improving machine learning performance.

I also learned how GridSearchCV can be used for hyperparameter tuning and how different models can be compared using evaluation metrics.

Author

Chetan Sharma

B.Tech - Artificial Intelligence & Data Science
