# Prodigy-Infotech-DataScience-Task3

## Project: Customer Purchase Prediction using Decision Tree Classifier

### Overview
This repository contains the implementation of Task 03, which involves building a **Decision Tree Classifier** to predict whether a customer will purchase a product or service based on their demographic and behavioral data. 

For this task, I utilized the **Bank Marketing Dataset** from the UCI Machine Learning Repository, which contains information about direct marketing campaigns (phone calls) of a Portuguese banking institution.

### Core Objectives
1. **Data Preprocessing:**
    * Handling categorical variables using Label Encoding or One-Hot Encoding.
    * Splitting the dataset into Training and Testing sets.
2. **Model Development:**
    * Implementing the `DecisionTreeClassifier` from the Scikit-Learn library.
3. **Performance Evaluation:**
    * Assessing the model using Accuracy, Precision, Recall, and F1-Score.
    * Generating a Confusion Matrix to visualize prediction errors.
4. **Visualization:**
    * Visualizing the trained Decision Tree to understand the decision-making rules.

### Dataset
* **Source:** [UCI Machine Learning Repository - Bank Marketing](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
* **Target Variable:** `y` (Has the client subscribed to a term deposit? 'yes' or 'no')

### Key Features Analyzed
* **Demographics:** Age, job, marital status, education.
* **Financial Status:** Default history, average yearly balance, housing/personal loans.
* **Campaign Data:** Contact type, month, duration of the last contact, and previous campaign outcomes.

### Tools & Technologies
* **Python 3.x**
* **Pandas & NumPy:** For data manipulation.
* **Scikit-Learn:** For model building and evaluation.
* **Matplotlib & Graphviz:** For visualizing the decision tree structure.

### Results
* The model achieved an accuracy of approximately **XX%** (Update with your result).
* The most significant predictors of customer purchase were **[Duration/Age/Balance]** (Update based on your feature importance analysis).

### How to Run
1. Clone the repo: `git clone https://github.com/YourUsername/PRODIGY_DS_03.git`
2. Install dependencies: `pip install pandas scikit-learn matplotlib`
3. Open and run the notebook: `jupyter notebook Task_03_DecisionTree.ipynb`

---
**Author:** Ntwanano Makhubele  
*Student of Maths & Physics | Aspiring Data Scientist*
