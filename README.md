Titanic Prediction Implementation Plan
Goal
Add explanatory "understanding messages" to the Titanic prediction notebook to guide the user through the analysis and modeling process.

Proposed Changes
Notebook 
titanic_prediction.ipynb
[MODIFY] 
titanic_prediction.ipynb
Add Markdown cells to explain:
1. Imports: Importing libraries.
2. Data Loading: Loading the Titanic dataset.
3. Data Exploration: Examining the dataframe structure.
4. Data Preprocessing:
Handling missing values (Cabin, Age, Embarked).
[FIX] Fix Sex mapping to handle 'Male'/'Female' (case sensitivity).
Encode Embarked.
5. Visualization: Analyzing survival rates.
6. Model Training: Train Logistic Regression, Decision Tree, and Random Forest.
7. Evaluation: Checking accuracy and confusion matrix.
Verification Plan
Manual Verification
Review the notebook to ensure the markdown cells correctly describe the subsequent code cells.
