# Dataset

**Loan Predication**, uploaded by amit parjapat on [Kaggle](https://www.kaggle.com/datasets/ninzaami/loan-predication).

- Included file: `loan_data.csv`
- Original filename: `train_u6lujuX_CVtuZ9i (1).csv`
- Original size: 614 data rows and 13 columns
- Target: `Loan_Status` (`Y` approved, `N` not approved)
- Kaggle license label: CC0: Public Domain
- [Direct Kaggle download](https://www.kaggle.com/api/v1/datasets/download/ninzaami/loan-predication)

This is the same raw file used in my Week 2 assignment. The file's bytes are preserved. It has 149 missing cells across seven columns and no exact duplicate rows. The dataset description says 615 rows; the CSV has a header and 614 data rows. All results use the measured 614 data rows.

The notebook renames columns to camelCase in memory, removes the ID, and adds two simple income features. This gives seven numeric and six categorical input columns before one-hot encoding. All 22 processed inputs are numeric. Labels describe historical approval decisions, not loan repayment or default.
