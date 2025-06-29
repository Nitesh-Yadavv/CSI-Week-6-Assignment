## Contents

- `titanic_classification.ipynb` – Main Jupyter notebook with step-by-step implementation
- `README.md` – Project overview and instructions

---

## Project Overview

We use supervised learning models to predict the **survival of passengers on the Titanic**, based on features like age, class, gender, fare, and more.

### Key Highlights:
- Cleaned and imputed missing data
- Label and one-hot encoded categorical features
- Scaled numerical features
- Trained and evaluated multiple models:
  - Logistic Regression
  - Random Forest
  - Support Vector Machine (SVM)
  - k-Nearest Neighbors (KNN)
- Used both `GridSearchCV` and `RandomizedSearchCV` for hyperparameter tuning
- Compared models using **Accuracy, Precision, Recall, and F1-Score**

---

## Final Result

> **Selected Model**: `Random Forest Classifier`  
> Achieved perfect evaluation scores with both Grid and Randomized search  
> **F1-Score: 1.00**, indicating ideal performance on test data

---

## How to Run

1. Clone the repository or download the `.ipynb` file
2. Open it with Jupyter Notebook or Jupyter Lab
3. Run all cells from top to bottom

```bash
# Required Libraries:
pandas
numpy
scikit-learn
seaborn
matplotlib
