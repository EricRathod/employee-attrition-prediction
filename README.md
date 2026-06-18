# Employee Attrition Prediction

This project predicts employee attrition using machine learning.  
The goal is to identify employees who are likely to leave the company and understand the key factors affecting employee turnover.

## Dataset

IBM HR Analytics Employee Attrition Dataset

- Rows: 1,470
- Columns: 35
- Target column: Attrition
- Attrition rate: 16.12%

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- Random Forest Classifier
- Google Colab

## Project Workflow

1. Loaded and explored the dataset
2. Checked missing values
3. Visualized employee attrition distribution
4. Encoded categorical columns
5. Trained a Random Forest model
6. Evaluated model performance
7. Analyzed feature importance
8. Created visualizations
9. Generated business recommendations

## Model Result

The Random Forest model achieved **88.10% accuracy**.

Note: Recall for employees who left was low because the dataset is imbalanced. Future improvements can include SMOTE, class weights, or XGBoost.

## Key Insights

- Overtime is one of the strongest indicators of employee attrition.
- Monthly income and age influence employee retention.
- Certain departments experience higher attrition rates.
- Predictive analytics can help identify at-risk employees early.

## Business Recommendations

- Monitor employees working overtime regularly.
- Improve employee retention programs.
- Review compensation and monthly income structures.
- Provide career growth opportunities for long-term employees.
- Use predictive analytics to support workforce planning.

## Author

Eric Rathod
