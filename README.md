# Titanic Data Analysis

## Overview

A comprehensive exploratory data analysis of the Titanic dataset, investigating passenger survival patterns and the impact of demographic factors on survival rates.

## Dataset

- **Source:** [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)
- **Train set:** 891 passengers with 12 features
- **Test set:** 418 passengers for prediction
- **Files:** data/train.csv, data/test.csv

## Key Findings

### Gender Impact

- **Female survival rate:** 74.2%
- **Male survival rate:** 18.9%
- **Insight:** "Women and children first" policy was clearly evident in the data

### Age and Gender Interaction

The analysis reveals that gender was the strongest predictor of survival across all age groups:

| Age Group | Male Survival | Female Survival | Difference |
|-----------|--------------|-----------------|-----------|
| 0-10 | 57.6% | 61.3% | 3.7% |
| 11-20 | 14.5% | 73.9% | 59.4% |
| 21-30 | 15.4% | 75.3% | 59.9% |
| 31-40 | 23.0% | 83.6% | 60.6% |
| 41-50 | 21.8% | 67.7% | 45.9% |
| 51-60 | 14.3% | 92.9% | 78.6% |
| 60+ | 10.5% | 100.0% | 89.5% |

**Key Insight:** Women in every age group had significantly higher survival rates. The gender gap was largest for elderly passengers (89.5% difference).

## Analysis Methodology

The analysis uses Python with pandas, NumPy, and Matplotlib for:

1. Data loading and exploration
2. Demographic analysis by gender and age
3. Multi-dimensional survival rate calculations
4. Professional visualizations

## Files in This Repository

- `notebooks/titanic_analysis.ipynb` - Complete analysis notebook with code and visualizations
- `data/train.csv` - Training dataset
- `data/test.csv` - Test dataset
- `README.md` - This file

## Visualizations

The analysis includes a line chart comparing male and female survival rates across age groups, clearly showing the gender disparity in survival outcomes.

## Lessons Learned

1. Gender was the strongest predictor of survival on the Titanic
2. The "women and children first" evacuation protocol was evident in the data
3. Multi-dimensional analysis reveals patterns that single-factor analysis might miss
4. Data visualization effectively communicates complex findings

## Tools and Libraries

- Python 3.12
- pandas - Data manipulation and analysis
- NumPy - Numerical computing
- Matplotlib - Data visualization
- Jupyter - Interactive notebook environment

## Author

Anupriya Singh

## License

This project uses publicly available data from Kaggle.
