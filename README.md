# Loan Approval Classification

A notebook experiment that predicts a loan approval label from applicant and loan attributes in the included dataset. The workflow preprocesses mixed numerical and categorical data, addresses class imbalance with SMOTE, compares Logistic Regression and Decision Tree classifiers, and reports classification metrics and confusion matrices.

## Project files

```text
.
├── LV_2_Task_4.ipynb
├── loan_approval_dataset.csv
└── README.md
```

## Notebook workflow

1. Load the loan dataset and inspect the target and features.
2. Clean column values and encode the loan-status target.
3. Split data into training and test sets.
4. Use scikit-learn preprocessing pipelines with imputation, encoding, and scaling.
5. Apply SMOTE to the training data and train Logistic Regression and Decision Tree classifiers.
6. Compare model metrics, confusion matrices, and feature-importance output where supported by the estimator.

The current notebook loads the CSV from `/content/loan_approval_dataset.csv`, which is a Google Colab-style path. For local use, change that cell to `pd.read_csv("loan_approval_dataset.csv")` and launch the notebook from the repository root.

## Requirements

Python and Jupyter are required. The notebook uses pandas, NumPy, scikit-learn, imbalanced-learn, and packaging.

```bash
pip install pandas numpy scikit-learn imbalanced-learn packaging jupyter
jupyter notebook
```

Open `LV_2_Task_4.ipynb` and run the cells in order.

## Responsible use

Loan approval is a consequential decision. This educational model can encode dataset bias and must not be used to make real lending decisions. Review data provenance, fairness, calibration, and applicable legal requirements before any real-world use.
