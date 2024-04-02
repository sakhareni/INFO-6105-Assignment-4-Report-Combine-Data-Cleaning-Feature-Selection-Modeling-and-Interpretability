# **Comprehensive Report on Lead Conversion Probability Analysis**

## 1. Introduction
The objective of this report is to analyze the probability of lead conversion using various machine learning models and techniques. The primary question addressed is: "What is the probability that a lead will be converted?" This report encompasses three assignments, each focusing on different aspects of data analysis, model building, and evaluation.

### Question:
What is the probability a lead will be converted or not?

### Models:
1. Tree-based models
2. Linear Regression
3. Logistic Regression
4. AutoML Models (including Gradient Boosting, Stacked Ensemble, XGBoost, and GLM)

## 2. Methodology

### First Assignment:
- Conducted Exploratory Data Analysis (EDA) and Data Cleaning.
- Handled missing values using strategies other than mean imputation.
- Utilized RandomForestClassifier, permutation importance, and correlation analysis for feature selection.
- Identified key features: Lead Quality, Tags, Total Time Spent on Website.

### Second Assignment:
- Explored model assumptions and multicollinearity using various techniques like VIF.
- Utilized AutoML to identify the best-performing model (GBM) and feature importance.
- Implemented regularization (L2) to improve model accuracy marginally.
- Conducted SHAP analysis to understand feature importance across different models.

### Third Assignment:
- Further explored SHAP analysis across Linear, Tree-Based, and AutoML models.
- Interpreted regression coefficients in the linear model.
- Evaluated model nodes in the tree-based model.
- Selected the best model via AutoML analysis.

## 3. Results and Findings

### Model Performance:
- Achieved an accuracy of 92% in the confusion matrix, indicating robust model performance.
- Identified key features consistently across models: Lead Quality, Total Time Spent on Website, and Tags.
- Selected GBM as the best-performing model, followed by StackedEnsemble in the AutoML analysis.

### Insights:
- Positive associations were found for Lead Quality, Total Time Spent on Website, and Last Activity in the linear model.
- Tree-based model nodes emphasized Lead Quality, Tags, and Total Time Spent on Website.
- AutoML analysis highlighted the effectiveness of StackedEnsemble and GBM models.

## 4. Lessons Learned

### Key Takeaways:
1. Thorough data cleaning and EDA are critical for understanding data and selecting relevant features.
2. Utilizing different models and techniques (e.g., SHAP analysis, regularization) provides deeper insights into lead conversion prediction.
3. Model evaluation through confusion matrices, accuracy scores, and regularization techniques ensures model robustness.
4. Lead Quality, Total Time Spent on Website, and Tags emerged as significant predictors across multiple models.
5. Understanding model assumptions, multicollinearity, and hyperparameters optimization is crucial for model performance.

## 5. Conclusion
The comprehensive analysis conducted through three assignments provided valuable insights into predicting lead conversion probability. By leveraging various machine learning models, feature selection techniques, and model evaluation methods, we gained a deeper understanding of factors influencing lead conversion and optimized model performance. This report underscores the importance of data-driven decision-making in marketing and sales strategies.
