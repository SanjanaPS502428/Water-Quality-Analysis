# Water Quality Analysis and Pollution-Risk Prediction Using Python

## Project Overview

This project analyzes water quality measurements from Kerala to identify patterns associated with potentially problematic water-quality conditions.

It combines exploratory data analysis, water-quality indicator assessment, visualization, and basic machine learning classification to investigate fecal coliform exceedance.

The project demonstrates a complete data analysis workflow, from data inspection and preprocessing to model training, evaluation, and interpretation.

## Objectives

- Analyze water quality measurements across monitoring stations.
- Explore spatial and temporal patterns in water-quality indicators.
- Examine relationships between BOD, fecal coliform, and total coliform.
- Identify observations exceeding a fecal coliform benchmark.
- Train and compare machine learning classification models.
- Visualize findings and communicate limitations.

## Dataset

- **Source:** Kerala water quality monitoring dataset
- **Coverage:** Monitoring observations from 2021
- **Data:** Water-quality measurements, monitoring station information, and geographical coordinates.

## Technologies and Tools

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Git
- GitHub

## Project Workflow

1. Data Inspection
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
4. Water Quality Analysis
5. Machine Learning Modeling and Evaluation

## Machine Learning Models

- K-Nearest Neighbors (KNN)
- Logistic Regression

The models classify observations according to whether fecal coliform exceeds the selected benchmark.

## Model Evaluation

Both models were evaluated using a stratified train-test split and compared using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

The analysis highlights the importance of evaluating minority-class performance rather than relying solely on accuracy.

## Important Limitation

The classification target represents fecal coliform benchmark exceedance, not actual drinking-water potability.

The results should not be interpreted as drinking-water safety certification or comprehensive water-quality classification.

## Repository Structure

```text
Water-Quality-Analysis/
├── notebooks/
│   ├── 01_data_inspection.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   ├── 03_data_preprocessing.ipynb
│   ├── 04_water_quality_analysis.ipynb
│   └── 05_modeling_preparation.ipynb
├── datasets/
├── README.md
└── .gitignore
```

## Future Improvements

- Explore additional classification approaches.
- Improve minority-class detection.
- Incorporate more complete water-quality measurements.
- Develop an interactive dashboard for monitoring insights.
