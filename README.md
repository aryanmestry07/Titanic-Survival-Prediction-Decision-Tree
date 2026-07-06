# Titanic Survival Prediction using Decision Tree Classifier

## Project Overview

This project implements a **Decision Tree Classifier** to predict whether a passenger survived the Titanic disaster. The project covers the complete machine learning workflow, including data preprocessing, feature engineering, model training, pre-pruning, post-pruning, model evaluation, and visualization using Scikit-learn.

---

## Dataset

- **Dataset:** Titanic Dataset
- **Problem Type:** Binary Classification
- **Target Variable:** Survived
  - 0 = Did Not Survive
  - 1 = Survived

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

1. Import Libraries
2. Load Dataset
3. Exploratory Data Analysis (EDA)
4. Handle Missing Values
5. Encode Categorical Features
6. Feature Selection
7. Train-Test Split
8. Train Decision Tree Classifier
9. Model Evaluation
10. Pre-Pruning
    - max_depth
    - min_samples_leaf
11. Decision Tree Visualization
12. Feature Importance
13. Post-Pruning (Cost Complexity Pruning)
14. Final Model Evaluation

---

## Data Preprocessing

- Filled missing values in **Age** using the median.
- Removed the **Cabin** column due to excessive missing values.
- Removed rows with missing **Embarked** values.
- Applied Label Encoding to the **Sex** column.
- Applied One-Hot Encoding to the **Embarked** column.

---

## Model Evaluation Metrics

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Decision Tree Optimization

### Pre-Pruning

The following hyperparameters were used to reduce overfitting:

- max_depth
- min_samples_leaf

### Post-Pruning

Cost Complexity Pruning (`ccp_alpha`) was applied to simplify the Decision Tree and improve generalization.

---

## Visualizations

The notebook includes:

- Dataset Overview
- Missing Values
- Pre-Pruning Accuracy Curve
- Decision Tree Visualization
- Feature Importance Plot
- Confusion Matrix

---

## Learning Outcomes

Through this project, I learned:

- Data preprocessing techniques
- Feature encoding
- Building Decision Tree Classification models
- Hyperparameter tuning
- Pre-Pruning and Post-Pruning
- Model evaluation using multiple classification metrics
- Feature importance analysis
- Decision Tree visualization

---

## Repository Structure

```
Titanic-Survival-Prediction-Decision-Tree/
│
├── Decision_Tree_Classification.ipynb
├── Titanic-Dataset.csv
├── README.md
└── screenshots/
```

---

## Future Improvements

- Random Forest Classifier
- Gradient Boosting
- XGBoost
- Cross Validation
- GridSearchCV
- Hyperparameter Optimization

---

## Author

**Aryan Mestry**

- GitHub: https://github.com/aryanmestry07
- LinkedIn: https://www.linkedin.com/in/aryanmestry

---

⭐ If you found this project useful, feel free to star the repository.
