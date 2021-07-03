# telco-churn-analytics

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)


## Installation <a name="installation"></a>

The code is running with no issue using Python versions 3.8.x.

Below are the necessary libraries and versions used for this project.
- xgboost==1.4.2
- shap==0.39.0
- seaborn==0.11.1


## Project Motivation<a name="motivation"></a>

I was interested in developing methodology of churn analytics providing not only predictive model also related actionable insights according to customer's service status by applying SHAP (SHapley Additive exPlanations).
Through this project, we mainly wanted to get answers to the following questions.

1. What factors about an individual customer largely contributed to potential churn probability?
2. Can we quantify the contribution of each factor to the potential churn chance for each customer?
3. Can we get any insights to act (e.g., providing personalized promotion) to boost loyalty  according to customer's service usage status (contract type, tenure month, internet service)?
