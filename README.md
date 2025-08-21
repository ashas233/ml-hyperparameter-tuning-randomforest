ML Hyperparameter Tuning - Random Forest

This repository contains a Jupyter Notebook for experimenting with **hyperparameter tuning** in machine learning models.  
The focus is on using **Random Forest** with `GridSearchCV` to find the best-performing parameters.


 Project Overview
- **Task 1 & 2**: Train baseline ML models and evaluate their performance.
- **Task 3**: Perform **simple hyperparameter tuning** using `GridSearchCV`:
  - Search over a grid of parameters:
    - `n_estimators`: [50, 100, 200]
    - `max_depth`: [3, 5, 10, None]
    - `min_samples_split`: [2, 5, 10]
  - Use 3-fold cross-validation.
  - Compare results before and after tuning.
- **Final Step**: Evaluate the best model on the test set (20% hold-out data).



Tech Stack
- Python 3.x  
- Jupyter Notebook  
- scikit-learn  
- pandas, numpy, matplotlib  
