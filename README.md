# Diabetes Prediction Analysis

This repository contains materials for the project **"Diabetes Prediction Analysis"**, which investigates the impact of key demographic and medical factors on the likelihood of developing diabetes. By leveraging statistical techniques and machine learning, the project provides insights to enhance diabetes prediction, management, and public health strategies.

## Project Overview

- **Objective**: Assess the predictive power of factors like age, BMI, HbA1c levels, and blood glucose concentrations on diabetes risk.
- **Data Source**: [Diabetes Prediction Dataset](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset).
- **Approach**:
  - Explored variable distributions and relationships through visualizations.
  - Conducted logistic regression to calculate odds ratios for predictors.
  - Utilized non-parametric tests (Kruskal-Wallis and Dunn's post-hoc) due to the dataset's non-normal distribution.
- **Results**: HbA1c levels and BMI emerged as the strongest predictors, with significant contributions from all factors.

## Files in the Repository

- `diabetes-prediction-analysis.Rmd`: R Markdown file with code for data preprocessing, statistical analysis, and visualization.
- `diabetes-prediction-analysis-report.pdf`: Detailed report describing the methodology, statistical tests, and findings.
- `diabetes-prediction-analysis-presentation.pdf`: Slide deck summarizing the project, including methodology, results, and conclusions.

## Methodology

1. **Data Preprocessing**:
   - Verified no null values in the dataset.
   - Addressed outliers using the IQR method for BMI, HbA1c, and blood glucose levels.
   - Ensured consistency in data types and variable transformations.

2. **Descriptive Statistics**:
   - Provided summary metrics for all variables (e.g., mean, median, standard deviation).
   - Analyzed participant demographics and health-related variables.

3. **Statistical Analysis**:
   - **Logistic Regression**:
     - Estimated odds ratios for predictors like age (5.2% increase per year), BMI (14.9% per unit), HbA1c levels (1196% per unit), and blood glucose levels (3% per unit).
     - Multivariate analysis confirmed the importance of all predictors.
   - **Non-Parametric Testing**:
     - Kruskal-Wallis test confirmed significant differences across predictors.
     - Dunn's post-hoc tests validated pairwise differences between groups.

4. **Visualization**:
   - Created histograms, bar charts, and boxplots to visualize variable distributions and relationships.
   - Generated Q-Q plots and other diagnostic visuals to explore data normality.

## Key Findings

- **Age**: Older individuals have a significantly higher likelihood of developing diabetes.
- **BMI**: Elevated BMI strongly correlates with diabetes prevalence, emphasizing the need for weight management.
- **HbA1c Levels**: A one-unit increase in HbA1c levels raises diabetes risk by 1196%, making it the strongest predictor.
- **Blood Glucose Levels**: Higher blood glucose levels are also significantly associated with diabetes.

## Limitations

- The large dataset size (>100,000 records) prevented the use of some parametric tests (e.g., Shapiro-Wilk).
- Non-parametric tests like Kruskal-Wallis rank data, which may lose information about the magnitude of differences.

## Applications

- **Healthcare Providers**: Insights can guide personalized treatment plans for at-risk individuals.
- **Public Health Strategies**: Findings can inform initiatives targeting modifiable risk factors like BMI and glucose levels.

## Contributors

- **Adarsh Viswanath**
- **Amol Prakash**
- **Keerthika Sunchu**
- **Meghana Darla**
- **Samantha Sanjeev**

## Contact

For questions or suggestions, please contact:  
Keerthika Sunchu - [ksunchu@iu.edu](mailto:ksunchu@iu.edu)
