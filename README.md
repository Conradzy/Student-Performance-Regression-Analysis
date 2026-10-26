# Student Performance Regression Analysis

Predicts student exam scores and compares linear, regularized, tree-based, kernel, and nearest-neighbor regression algorithms. It also interprets the multiple linear regression equation and coefficient-based feature importance.

## Workflow

1. Load `Student_Performance.csv`.
2. Select performance-related features and the `ExamScore` target.
3. Create training and test sets.
4. Train seven regression models.
5. Compare MAE, MSE, RMSE, and R² and inspect linear-model coefficients.

## Data Requirements

- `Student_Performance.csv` — student factors and exam scores.

Datasets and generated artifacts are not included unless they are embedded directly in the notebook.

## Requirements

- pandas
- NumPy
- scikit-learn
- Matplotlib
- Seaborn

Install missing packages in your Jupyter or Google Colab environment before running the notebook.

## Running the Notebook

1. Open [`studentperformancenapinas.ipynb`](studentperformancenapinas.ipynb) in Jupyter Notebook or Google Colab.
2. Place any required data files in the path expected by the notebook.
3. Update local or Google Drive paths where needed.
4. Run the cells from top to bottom.

## Outputs

- Regression metrics table
- Per-metric comparison charts
- Linear-regression equation
- Coefficient importance chart
- Example exam-score prediction

## Repository Contents

```text
.
|-- README.md
`-- studentperformancenapinas.ipynb
```

## Notes

- This repository preserves the analysis as a notebook-first educational project.
- Results may vary with dataset versions, random splits, package versions, and available hardware.
- Review file paths and runtime-specific commands before executing outside Google Colab.
