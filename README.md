# Data Jobs And Salaries

## Overview

This project analyzes how salaries in the data industry are influenced by various factors such as company size, location, job category, and experience level. The goal is to understand key determinants of salary levels and identify trends to inform job seekers and industry professionals.

## Dataset

The dataset used for this analysis is sourced from Kaggle and can be found at [Jobs and Salaries in Data Field 2024](https://www.kaggle.com/datasets/murilozangari/jobs-and-salaries-in-data-field-2024/data). The original data comes from [AI-Jobs.net](https://ai-jobs.net/salaries/2024/).

## Tools and Technologies

The analysis was conducted using Python, with libraries such as Pandas for data manipulation, NumPy for numerical computations, Matplotlib for data visualization, and Seaborn for statistical graphics.

## Project Structure

The project consists of the following notebooks:

- **[Exploratory Data Analysis (EDA) Notebook](https://github.com/Vanderval31bs/DataJobsAndSalaries/blob/main/EDA.ipynb)**: This notebook performs data exploration, visualization, and preliminary analysis to understand the dataset and identify trends.
- **[Model Training Notebook](https://github.com/Vanderval31bs/DataJobsAndSalaries/blob/main/Model_Training)**: This notebook focuses on training and evaluating different machine learning models to predict job salaries. It includes model performance comparisons and results.

## Conclusions

- **Salary Influencers**: Job salary is related to experience level, job title/category, employment type, work setting, company size, location, and employee residence.
- **High Salary Factors**:
  - Executive experience level
  - Full-time contracts
  - In-person work settings
  - Medium to large-sized companies
- **Top-Paying Job Category**: "Machine Learning and AI" pays the most.

## Model Training Results

The final model chosen was a **Random Forest Regressor** with the following parameters:
- `n_estimators=100`
- `max_depth=10`

On the test data, the model achieved:
- **R²-score**: 0.299, indicating it explained approximately 30% of the variance in the target variable.
- **Mean Absolute Error (MAE)**: 40650.49.
- **Root Mean Squared Error (RMSE)**: 52877.33.

These results suggest that while the model captures some underlying patterns, there is still considerable room for improvement in its performance.

## Contact

For any questions or feedback, please contact [Vanderval](mailto:vander31bs@gmail.com).
