# Diabetes Classification

A cleaned and reproducible machine-learning notebook based on the supplied Diabetes Classification exercise. It covers descriptive analysis, EDA, categorical encoding, feature selection, KNN and SVM classification, confusion matrices, ROC/AUC evaluation, model comparison, and a one-hot vs label-encoding experiment.

## Repository structure
```text
.
├── data/
│   └── Diabetes Classification.csv   # add locally; not included in the supplied files
├── notebooks/
│   ├── Diabetes_Classification_Analysis.ipynb
│   └── Diabetes_Classification_Original.ipynb
├── reports/
├── src/
├── requirements.txt
└── README.md
```

## Run locally

1. Create an environment and install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Put `Diabetes Classification.csv` in `data/`.
3. Open `notebooks/Diabetes_Classification_Analysis.ipynb`.
4. Run all cells from top to bottom.

## What was fixed

- Corrected the SyntaxError in the SVM ROC-curve f-string.
- Corrected the selected-feature train/test split.
- Corrected the SVM selected-feature classification report.
- Removed the machine-specific absolute data path.
- Added train-only preprocessing/feature selection and scaling.
- Completed all four assignment tasks.

## Important

This project is for educational machine-learning purposes only. It is not a validated clinical diagnostic tool.
