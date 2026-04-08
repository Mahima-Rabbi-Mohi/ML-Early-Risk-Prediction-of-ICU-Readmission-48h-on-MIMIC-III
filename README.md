# Machine Learning-Based Early Risk Prediction of 48-Hour ICU Readmissions Using the MIMIC-III Database

## Objective
This repository contains code and experiments for predicting ICU readmissions within 48 hours using the MIMIC-III clinical database.  
The project explores machine learning models for early risk identification, aiming to improve decision support in critical care.

## Contribution

- Extracted and cleaned structured patient/admission data
- Engineered readmission label within 48 hours
- Trained baseline and tree-based models
- Compared performance using AUROC, precision, recall, and F1
- Analyzed feature importance/error patterns

## Workflow
 MIMIC tables → cleaning → label creation → feature engineering → train/test split → models → evaluation

## Contents
- `MSc_MIMICIII_ICU_Readmission_48h_Colab.ipynb`: Base notebook with preprocessing, feature engineering, and model training.
- Data preprocessing scripts (linked/not included, MIMIC-III access required).
- Documentation and results.

## Dataset
- **MIMIC-III v1.4**: A freely accessible critical care database from MIT (requires credentialed access).  
- Due to data restrictions, raw data is not included.  
- Access MIMIC-III: https://physionet.org/content/mimiciii/1.4/

## Installation
Clone repo and install dependencies:
```bash
git clone https://github.com/Mahima-Rabbi-Mohi/Early-Risk-Prediction-of-ICU-Readmission-48h-on-MIMIC-III.git
pip install -r requirements.txt

