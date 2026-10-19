# Student Performance Prediction

University coursework exploring student outcomes using data derived
from the Open University Learning Analytics Dataset (OULAD).

The project addresses two tasks:
- Classification of students into Withdrawn, Fail, Pass and Distinction.
- Regression to predict the final coursework score.

## Approach

The notebook includes exploratory data analysis, missing-value
imputation, outlier handling, feature encoding and standardization.

Models:
- Decision Tree classifier: baseline and hyperparameter experiments.
- Linear Regression, Ridge and Lasso.

Detailed explanations, visualizations and interpretation of the results
are included in the notebook in Romanian.

## Results

Results from the provided labeled test set:

| Model | Metric | Value |
| --- | --- | --- |
| Decision Tree | Accuracy | 74.45% |
| Decision Tree | Macro-F1 | 0.686 |
| Linear Regression | MAE | 5.070 |
| Linear Regression | RMSE | 7.157 |
| Linear Regression | R² | 0.808 |

## How to run

1. Download or clone this repository.
2. Open `student_performance.ipynb` in Jupyter Notebook, JupyterLab
   or VS Code with Jupyter support.
3. Install the dependencies using the setup instructions in the notebook.
4. Place `oulad_train.csv` and `oulad_test.csv` in the same directory
   as the notebook.
5. Restart the kernel and run all cells from top to bottom.

For Google Colab, upload the notebook and both CSV files before running
the cells.

## Dataset

The project uses course-provided, preprocessed tables derived from OULAD,
with 18,802 training rows and 4,700 test rows.

These tables contain engineered features and differ from the raw OULAD
dataset.
