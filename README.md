# Student Performance Prediction — ML Regression Model

## Overview
A machine learning project that predicts student math exam scores 
using demographic and academic features from a dataset of 1,000 
real student records.

## Results
| Model | R² Score | RMSE |
|---|---|---|
| Linear Regression | 0.8838 | 5.32 |
| Ridge Regression | 0.8838 | 5.32 |
| Random Forest | 0.8567 | 5.91 |

**Best Model: Ridge Regression — R² 0.88, RMSE 5.32**

## Dataset
Kaggle Student Performance Dataset — 1,000 records, 7 features
- Gender, race/ethnicity, parental education level
- Lunch type, test preparation course
- Reading score, writing score
- Target: Math score

## Key Finding
Reading score and writing score are the strongest predictors 
of math performance. Test preparation course completion showed 
measurable positive impact on predicted scores.

## Tech Stack
- Python 3
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Project Structure
student-performance-prediction/
│
├── StudentsPerformance.csv       # Dataset
├── student_performance.ipynb     # Main notebook
├── score_distribution.png        # EDA chart
├── correlation_heatmap.png       # Feature correlations
├── model_comparison.png          # R² and RMSE comparison
├── feature_importance.png        # Random Forest importance
├── actual_vs_predicted.png       # Prediction accuracy plot
└── README.md

## How to Run
1. Clone the repo
2. Open `student_performance.ipynb` in Jupyter or Google Colab
3. Upload `StudentsPerformance.csv` if using Colab
4. Run all cells in order
