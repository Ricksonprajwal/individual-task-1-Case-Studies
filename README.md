# individual-task-1-Case-Studies
Machine learning analysis for Individual Task 1


# Individual Task 1 – Case Studies

This repository contains the datasets, machine learning code, job advertisement, and supporting materials used for Individual Task 1.

## Selected Data Science Role

The selected position is the **Data Scientist** role at the **Australian Council for Educational Research (ACER)** in Camberwell, Melbourne.

The job advertisement is included in this repository as:

`ACER_Data_Scientist_Job_Advertisement.pdf`

## Datasets

### OpenML 43415

**File:** `dataset`

The OpenML 43415 dataset contains student-related demographic, educational, and behavioural information. It was used as a classification problem to predict the outcome class.

**Dataset URL:**  
https://www.openml.org/search?type=data&sort=runs&id=43415&status=active

### UCI Student Performance – Mathematics

**File:** `student-mat.csv`

The UCI Student Performance Mathematics dataset contains demographic, family, social, school, and academic information about students. The final grade (`G3`) was used as the prediction target for the regression analysis.

**Dataset URL:**  
https://archive.ics.uci.edu/dataset/320/student

## Machine Learning Analysis

Two machine learning algorithms were applied:

- Random Forest
- K-Nearest Neighbours (KNN)

The analysis includes:

- Data loading and exploration
- Data preprocessing
- Training and testing data splits
- Random Forest classification
- KNN classification
- Random Forest regression
- KNN regression
- Model evaluation and comparison
- Feature importance analysis
- An additional Random Forest experiment using previous grades (`G1` and `G2`)

## Evaluation Metrics

For the classification task, the following metrics were used:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

For the regression task, the following metrics were used:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)

## Repository Files

- `data_analysis.ipynb` – Jupyter Notebook containing the data analysis and machine learning experiments.
- `dataset` – OpenML 43415 dataset used for the classification analysis.
- `student-mat.csv` – UCI Student Performance Mathematics dataset used for the regression analysis.
- `ACER_Data_Scientist_Job_Advertisement.pdf` – Copy of the selected ACER Data Scientist job advertisement.
- `README.md` – Description of the repository, datasets, models, and analysis.
- `.gitignore` – Specifies files and folders that should not be tracked by Git.

## Running the Analysis

Open `data_analysis.ipynb` using Jupyter Notebook, JupyterLab, or Google Colab and run the cells sequentially.

The dataset files should remain available to the notebook using the filenames specified above.
