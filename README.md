# Predicting Medical Insurance Charges with AWS SageMaker

## Project Overview
This project applies supervised machine learning to predict medical insurance charges based on lifestyle and demographic data. The model was developed using Python and deployed using AWS SageMaker. The analysis explores how age, BMI, gender, and smoking status affect medical costs and proposes pricing strategies based on risk.

## Objectives
- Predict insurance charges using features such as age, smoker status, and BMI  
- Analyze patterns by gender, age group, and weight category  
- Simulate future cost increases using a 5% annual adjustment  
- Support risk-based pricing and policy recommendations for insurers

## Tools and Technologies
- Python (pandas, scikit-learn, matplotlib, XGBoost)  
- AWS SageMaker (Jupyter Notebooks, EC2 backend)  
- AWS S3 (for dataset and model storage)  
- Git (version control)


## Methodology
1. Exploratory Data Analysis (EDA)  
2. Feature engineering (one-hot encoding of categorical variables)  
3. Model training using XGBoostRegressor in AWS SageMaker  
4. Applied a 5% annual growth rate to simulate realistic future charges  
5. Visualized risk differences across key groups

## Results
- Smoking status was the most significant cost driver  
- Obese smokers had the highest projected charges  
- Non-smokers showed stable, lower costs across all age and BMI groups  
- Annual 5% adjustment aligned results with long-term healthcare cost trends and expected customer growth

## Recommendation
- Provide discounts for verified non-smoking periods (30, 60, 90 days)  
- Offer gift cards or wellness bonuses for sustained health improvements  
- Implement tiered premium benefits for participants in no-smoking programs 
- Restrict acceptance of new applicants who are confirmed active smokers due to high-risk exposure  
- Require a basic health screening or smoking status verification for all new enrollees  
