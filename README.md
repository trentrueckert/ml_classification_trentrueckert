# ml_classification_trentrueckert

## Links
Notebook: https://github.com/trentrueckert/ml_classification_trentrueckert/blob/main/classification_trentrueckert.ipynb
Peer review: 

## Preliminary Project Setup

### Step 1 - Initial Setup
1. Click "New Repository"
* Generate name with no spaces
* Add a "README.md"

2. Clone Repository to machine via VS Code
* Create folder in "C:\Projects"

3. Install requirements.txt
4. Setup .gitignore file

### Step 2 - Create Project Virtual Environment

```
py -m venv .venv
.venv\Scripts\Activate
py -m pip install --upgrade pip 
py -m pip install -r requirements.txt
```

### Step 3 - Git add, clone, and commit

```
git add .
git clone "urlexample"
git commit -m "Commit Example"
git push -u origin main
```

## Overview
In this notebook, I will analyze the UIC Banknote Authentication Dataset to predict authenticity by preparing/exploring the data, cleaning the data/handling missing values, performing feature engineering, and training machine learning models based on different selected features. More specifically, I will be using various Decision Tree and Random Forest models to provide insights on all of the features' collective impact on predicting authenticity.

## Section 1. Import and Inspect the Data
* 1.1 Load the dataset and display the first 10 rows
* 1.2 Check for missing values and display summary statistics
* Reflection 1

## Section 2. Data Exploration and Preparation
* 2.1 Explore Data Patterns and Distributions
* 2.2 Handle Missing Values and Clean Data
* 2.3 Feature Selection and Engineering
* Reflection 2

## Section 3. Feature Selection and Justification
* 3.1 Choose Features and Target
* 3.2 Define X and y
* Reflection 3
  
## Section 4. Train a Model (Classification: Choose 1: Decision Tree, Random Forest, Logistic Regression)
* 4.1 Split the data into training and test sets using train_test_split
* 4.2 Train model using Scikit-Learn model.fit() method
* 4.3 Evalulate performance
* Reflection 4

## Section 5. Improve the Model or Try Alternates (Implement a Second Option)
* 5.1 Train an alternative classifier (e.g., Decision Tree, Random Forest, Logistic Regression)
* 5.2 Compare performance of all models across the same performance metrics
* Reflection 5

## Section 6. Final Thoughts & Insights
* 6.1 Summarize Findings
* 6.2 Discuss Challenges Faced
* 6.3 If you had more time, what would you try next?
* Reflection 6