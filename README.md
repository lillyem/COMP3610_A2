# COMP3610 Assignment 2

This project builds machine learning models to predict taxi tip amounts and classify high-tip trips using the NYC Taxi dataset. The notebook includes data preprocessing, feature engineering, model training, hyperparameter tuning, neural network modeling, and model evaluation.
---
## Setup Instructions

### 1) Create and activate a virtual environment (Windows, PowerShell)
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

### 2) Install dependencies
```powershell
pip install -r requirements.txt
```

### 3) Data files
The data files are **not included in this repository**.  
Large dataset files and intermediate artifacts are excluded from the repository using .gitignore.
They were downloaded and cleaned manually in Assignment 1.

- Create a `data/` folder in the project root if it does not exist.
- Copy your cleaned parquet file from Assignment 1 into `data/`.

### 4) Update cleaned parquet filename
For this assignment, update the cleaned parquet filename used by the code to match your file.

- If the code expects a fixed name, either:
  - rename your file to that expected name, **or**
  - update the file path variable in the script/notebook to your actual parquet filename.

Example:
- Your file: `data/a1_cleaned_dataset.parquet`
- Update code references from `data/cleaned.parquet` to `data/a1_cleaned_dataset.parquet`.

### 5) Run
Run the main script or notebook after confirming the parquet filename/path is correct.

1. Ensure the dataset path is correct.

2. Open the notebook in Jupyter.

3. Run the cells from top to bottom.