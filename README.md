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
![output_18_0](https://github.com/user-attachments/assets/ea6e8b9b-0737-4ad3-b740-4942ab6c82cc)


Age distribution
![output_20_0](https://github.com/user-attachments/assets/8ae089b6-5be9-439d-b46d-e7fe17c86d5f)


Education and years of education distribution
![output_22_0](https://github.com/user-attachments/assets/bc707f67-f253-46c1-a7b8-34600a5e3391)


Marital and relationship status
![output_25_0](https://github.com/user-attachments/assets/dda61e7c-4b4c-49f3-8d23-4565be78f552)
![output_27_0](https://github.com/user-attachments/assets/bdbdcbf5-be74-4f58-ab02-87a69b84c2fc)



Gender and race representation
![output_29_0](https://github.com/user-attachments/assets/bfd7baba-2999-4fac-893a-d6231ff8f155)
![output_31_0](https://github.com/user-attachments/assets/fa86e94f-b695-4aae-b633-dcae4d266ea9)



Project Implications

This analysis provides actionable insights to:

Enhance workforce development and financial education.

Inform inclusive economic policies.

Reduce income inequality and support economic mobility.

Tools and Libraries

Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

Machine Learning techniques (Logistic Regression, Decision Trees, Random Forest)
![output_182_0](https://github.com/user-attachments/assets/79bc9351-0249-44b9-b178-3ecc80223620)


