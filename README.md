# Task 2: Feature Engineering, Model Optimization & Performance Comparison

AI/ML Internship Task at Maincrafts Technology.

## Objective
Improved on the Task 1 baseline by applying feature scaling, training multiple
regression models, and comparing their performance to select the best one —
mirroring real-world ML engineering workflows.

## Tools Used
Python, pandas, NumPy, scikit-learn, matplotlib, Jupyter Notebook

## Workflow
1. Loaded the California Housing dataset
2. Applied feature scaling using StandardScaler
3. Split data into train/test sets
4. Trained three models: Linear Regression, Ridge Regression, Decision Tree Regressor
5. Evaluated all models using RMSE and R² Score
6. Compared results and selected the best-performing model
7. Visualized predictions vs actual values

## Results

| Model              | RMSE   | R² Score |
|--------------------|--------|----------|
| Linear Regression  | 0.7456 | 0.5758   |
| Ridge Regression    | 0.7456 | 0.5758   |
| Decision Tree       | 0.7242 | 0.5997   |

**Best Model:** Decision Tree Regressor (max_depth=5)

## Files
- `AI_ML_Task2_Model_Comparison.ipynb` — full notebook with code, comparison table, and plots
- `task2_report.pdf` — summary report with methodology and conclusions
- `best_house_price_model.pkl` — saved best-performing model (optional)
