# Body Fitness Prediction

Applied Machine Learning mini-project: classifies body fitness performance level (A/B/C/D class) from biometric and physical-test measurements, using the [bodyPerformance](https://www.kaggle.com/datasets/kukuroo3/body-performance-data) dataset.

## Data

Each row is one person's measurements: age, gender, height, weight, body fat %, blood pressure (diastolic/systolic), grip force, sit-and-reach flexibility, sit-up count, and standing broad jump distance, labeled with an overall fitness class.

## Approach

- Exploratory data analysis and visualization (`AML_mini project.ipynb`)
- Preprocessing: encoding, scaling (`OrdinalEncoder`, `MinMaxScaler`/`StandardScaler`)
- Classification models built with scikit-learn (`AML_MP_13_B.ipynb`)

## Contents

- `AML_mini project.ipynb` — data exploration and preprocessing
- `AML_MP_13_B.ipynb` — model training and evaluation
- `bodyPerformance.csv` — dataset
