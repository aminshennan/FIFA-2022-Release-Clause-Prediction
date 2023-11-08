# FIFA 2022 Release Clause Prediction

## Project Overview
This project aims to fill in the missing release clause values for FIFA 2022 players using a predictive model. A multilinear regression approach was adopted to estimate these values based on a dataset featuring various player attributes.

## Dataset
The dataset consists of 19,239 entries and 110 columns, detailing players' names, clubs, leagues, positions, and performance statistics. This data was sourced from the FIFA 2022 complete player dataset available on Kaggle.

## Methodology
The project follows a structured data science pipeline, including:

- Data Cleaning: Handled missing values and removed duplicate observations.
- Data Transformation: Normalized and aggregated data for modeling.
- Exploratory Data Analysis: Used statistical methods to understand data distribution and attribute relationships.
- Data Mining: Identified attributes with the highest correlation to the release clause.
- Model Training: Employed multilinear regression to create the predictive model.
- Results Evaluation: Validated the model's predictions against actual data.

## Results
The linear regression model achieved a high degree of accuracy with an R-squared value of 1.0, indicating a strong correlation between the predicted and actual release clause values.

## Conclusion and Future Work
The linear regression model successfully predicted player release clauses. Future iterations could employ more advanced machine learning techniques and incorporate additional data to enhance prediction accuracy.

## How to Use
1. Clone the repository.
2. Run the Jupyter notebook `Project.ipynb` to view the analysis and modeling process.

## References
- FIFA 2022 Complete Player Dataset: [Kaggle Dataset](https://www.kaggle.com/datasets/stefanoleone992/fifa-22-complete-player-dataset?select=players_22.csv)
