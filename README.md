# Adult-Census-Income-Classification
Project Overview

This project analyzes socio-economic factors affecting income levels using the Adult Census Income dataset. The primary objective was to develop predictive models that classify individuals into two income categories: earning ≤ $50,000 annually or > $50,000 annually, based on demographic and employment data.



Dataset Information

Source: Kaggle (Adult Census Income from UCI Machine Learning Repository)

Entries: 32,561

Attributes: 15 (Demographics, socio-economic factors, and income)

Key attributes: Age, Education, Occupation, Marital Status, Hours per Week

Key Objectives

Identify factors contributing to income disparities.

Develop robust predictive models.

Offer data-driven recommendations to guide policy and economic strategies.

Methodology

Data Preprocessing: Handled missing values and class imbalance using RandomOverSampler.

Feature Selection: Identified important predictors using ExtraTreesClassifier.

Machine Learning Algorithms Used:

Logistic Regression

Decision Trees

Random Forest (Best performing model)

Key Insights

Most Influential Factors:

Education level

Hours worked per week

Marital status

Occupation

Higher education and longer working hours significantly correlate with higher income.

Results

Best Model: Random Forest

Accuracy: 92.23%

F1-score: 92.61%

Visualization Highlights

Income distribution

Age distribution

Education and years of education distribution

Marital and relationship status

Gender and race representation

Project Implications

This analysis provides actionable insights to:

Enhance workforce development and financial education.

Inform inclusive economic policies.

Reduce income inequality and support economic mobility.

Tools and Libraries

Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

Machine Learning techniques (Logistic Regression, Decision Trees, Random Forest)
