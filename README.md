# Titanic Survival Prediction

This project is a machine learning pipeline for predicting Titanic survival outcomes using the Titanic dataset from Kaggle. The notebook is structured into several steps, including data preprocessing, model training, and evaluation.

## Table of Contents
1. [Libraries Used](#libraries-used)
2. [Dataset](#dataset)
3. [Steps in the Notebook](#steps-in-the-notebook)
4. [How to Run](#how-to-run)
5. [Model and Accuracy](#model-and-accuracy)

---

## Libraries Used
The following Python libraries are used in this notebook:
- `numpy` for numerical computations
- `pandas` for data manipulation and analysis
- `scikit-learn` for machine learning and preprocessing
- `os` for file handling

---

## Dataset
The dataset used in this project is the Titanic dataset provided by Kaggle. It consists of two files:
- `train.csv`: Training data with survival outcomes
- `test.csv`: Test data for predictions

---

## Steps in the Notebook

1. **Library Import**  
   Import necessary libraries and set up the environment.

2. **Read Dataset**  
   Load the training and test datasets using `pandas`.

3. **Preprocessing**  
   - Drop unnecessary columns (`Name`, `Ticket`, `Cabin`).
   - Handle missing values in `Age` and `Embarked`.
   - Encode categorical variables (`Sex` and `Embarked`).
   - Perform one-hot encoding for `Embarked`.

4. **Train/Test Split**  
   - Split the data into training and testing sets.
   - Scale the features using `StandardScaler`.

5. **Model Training and Accuracy**  
   - Train a `RandomForestClassifier` with 200 estimators.
   - Evaluate the model's accuracy on the test set.

---

## How to Run
1. Clone the repository or download the notebook.
2. Ensure the required libraries are installed:
   ```bash
   pip install numpy pandas scikit-learn

