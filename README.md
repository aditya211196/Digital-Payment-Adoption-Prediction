# Digital-Payment-Adoption-Prediction


 **Predicting Digital Payment Adoption to Drive Financial Inclusion**
This project analyzes patterns in digital payment adoption across 139 countries, aiming to uncover barriers to financial inclusion and identify strategies for expanding access to digital financial services. Using publicly available micro-level survey data and macroeconomic indicators, we built and evaluated multiple machine learning models to predict the likelihood of individuals adopting digital payments based on demographic and economic factors.

**Project Objective**
To use data-driven techniques and predictive modeling to:

Understand socio-economic factors influencing digital payment adoption

Identify underserved population segments

Support the design of inclusive financial solutions for policymakers and fintech institutions

**Tools & Technologies**
Language: Python

Libraries: pandas, NumPy, scikit-learn, XGBoost, seaborn, matplotlib

Environment: Jupyter Notebook

Data Sources: World Bank Microdata & Country-level Indicators

 **Methodology**
1. Data Collection & Preparation
Combined micro-level survey data with macroeconomic indicators

Handled missing values using imputation (Random Forest Regressor for age)

Standardized features and bucketed age for interpretability

Encoded categorical variables (gender, mobile ownership, internet access)

2. Exploratory Data Analysis (EDA)
Visualized adoption rates by income, gender, age, education, and region

Found education and internet access to be the strongest positive correlates

Highlighted persistent gender and regional disparities

3. Predictive Modeling
Models Used: Logistic Regression, Decision Tree, Random Forest, XGBoost

Evaluation Metrics: Accuracy, Precision, Recall, F1-Score

Decision Tree selected for final use due to:

High interpretability for stakeholders

Best recall for identifying non-adopters, aiding targeted intervention

 **Recognition**
 Second Runner-Up at BitATHON 2025, a national-level data analytics competition organized by SAS.

 **Key Insights**
Education level and internet access are the most influential factors in digital payment adoption.

Even in high-income groups, adoption gaps remain—indicating trust and usability issues.

Age is not a linear factor—older age groups (65–84) showed high adoption in some regions.

Gender disparities persist, especially in lower-income quintiles.

 **Impact**
The insights from this project can help:

Fintechs target product design for high-potential but underpenetrated segments.

Governments & NGOs build region-specific financial literacy programs.

Researchers explore further applications in economic inclusion and policy-making.









