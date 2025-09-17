# Insurance-claim-data-

Problem Statement
A key challenge for the insurance industry is charging each customer an appropriate premium based on the risk they represent. Accurately predicting claim amounts has a significant impact on an insurer’s financial decisions and long-term sustainability. Health-related factors such as BMI, age, smoking habits, and medical conditions play a crucial role in determining insurance costs. Therefore, developing accurate and automated methods for claim prediction is essential.

Project Overview
This project focuses on predicting health insurance claim amounts using machine learning algorithms. The goal is to build a system that assists insurance companies in estimating claims more precisely. We implemented and compared multiple models, including Random Forest Regression, Support Vector Regression, XGBoost Regressor, and Linear Regression, using a health insurance dataset. Among these, XGBoost delivered the best performance.

By improving prediction accuracy, this project can help:

Insurance companies set fair and sustainable premiums

Patients choose plans that best match their needs

Policymakers analyze and understand pricing trends

The dataset contains various demographic, lifestyle, and health-related features that influence the claim amount of a policyholder:

age: Age of the policyholder (Numeric)

sex: Gender of the policyholder (Categorical)

weight: Weight of the policyholder (Numeric)

bmi: Body Mass Index, an objective index of body weight (kg/m²) using the ratio of height to weight (Numeric)

no_of_dependents: Number of dependent persons on the policyholder (Numeric)

smoker: Indicates whether the policyholder is a smoker (0 = non-smoker, 1 = smoker) (Categorical)

claim: The claim amount filed by the policyholder (Numeric — Target Variable)

bloodpressure: Blood pressure reading of the policyholder (Numeric)

diabetes: Indicates whether the policyholder suffers from diabetes (0 = non-diabetic, 1 = diabetic) (Categorical)

regular_ex: Indicates whether the policyholder exercises regularly (0 = no, 1 = yes) (Categorical)

job_title: Job profile of the policyholder (Categorical)

city: City of residence of the policyholder (Categorical)

hereditary_diseases: Indicates whether the policyholder has hereditary diseases (Categorical)
