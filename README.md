# Phobia-Classification-ai
AI-powered phobia classification using NLP and behavioral pattern analysis.

## Overview
This project builds a machine learning model to classify types of phobia based on behavioral and demographic features.  
It uses NLP and structured data to uncover patterns in fear severity, treatment seeking, and regional distribution.

## Dataset Features
- **Phobia_Type**: Target label (e.g., Arachnophobia, Claustrophobia)
- **Age**: Age of the individual
- **Gender**: Male / Female
- **Region**: Geographic region
- **Severity_Level**: Mild / Moderate / Severe
- **Encounter_Frequency**: How often the phobia is triggered
- **Treatment_Seeking**: Binary indicator (0 or 1)

## Workflow Summary
1. **Data Cleaning**: Handling missing values and duplicates
2. **Encoding**: Label encoding and one-hot encoding for categorical features
3. **Visualization**: Distribution plots, boxplots, and gender breakdowns
4. **Feature Scaling**: MinMax normalization for numerical features
5. **Modeling**:
   - Logistic Regression
   - Random Forest Classifier
6. **Evaluation**:
   - Confusion Matrix
   - Classification Report
   - True Positives and Support per class

## Notebooks
- `notebooks/phobia Types.ipynb`: Full Colab notebook with EDA, preprocessing, modeling, and evaluation
- `notebooks/phobia Types.py`

## Visuals
- `visuals/`: Contains charts for phobia distribution, gender breakdown, and model performance

## Author
**Ibtisam Alghwainem**  
