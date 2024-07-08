# Airbnb-Data-Prediction

## Airbnb's program to predict the country of reservation for new subscribers

### Overview
**📕Data: 
https://www.kaggle.com/c/airbnb-recruiting-new-user-bookings**

**🔑Purpose:
Predicting Reservation Destinations. Building a Machine Learning Model**

**👩🏻‍💻 Datasets Used: train_users_2.csv, test_users.csv**

### Data Preprocessing
**Describe the preprocessing steps taken for the numerical(age, sighnup_flow) and categorical data(gender, language). (Fills a null value and removes unfilled rows)
If the age is less than 10 years old or more than 90 years old, it was considered an abnormal value and dropped**
![image](https://github.com/iey704/Airbnb-Data-Prediction/assets/105503671/963635c4-7e4c-4401-b87b-ffbb0b72e71c)
![image](https://github.com/iey704/Airbnb-Data-Prediction/assets/105503671/00ade4a5-e0d7-42c2-9181-ef36ceff4375)
![image](https://github.com/iey704/Airbnb-Data-Prediction/assets/105503671/5c30e797-66b9-49f9-89aa-341aac7b17cd)
**Final Preprocessing Method:**
![image](https://github.com/iey704/Airbnb-Data-Prediction/assets/105503671/9a7e4923-c887-48c7-867d-94eaf6d037e0)

[Scaling](url)
**the numerical data was preprocessed by scaling (MinMax, Robust, Standard)**
![image](https://github.com/iey704/Airbnb-Data-Prediction/assets/105503671/ffff8839-4856-4325-86a5-2d24e6b1453e)

[Encoding](url)
**the categorical data was preprocessed by encoding (OneHot, Ordinal, Label).**
![image](https://github.com/iey704/Airbnb-Data-Prediction/assets/105503671/f0afd0a8-b19c-4974-b907-e36f7e971d15)
![image](https://github.com/iey704/Airbnb-Data-Prediction/assets/105503671/ec5a1cda-401d-438d-8774-7c0af428f74f)
![image](https://github.com/iey704/Airbnb-Data-Prediction/assets/105503671/50a1ead7-2533-4e10-ab2b-72f369bec4b8) ![image](https://github.com/iey704/Airbnb-Data-Prediction/assets/105503671/48f362aa-7fb6-4942-b5e0-20ba7c139442)

### Data Visualization
**Visualization based on data frames processed for outliers**
![image](https://github.com/iey704/Airbnb-Data-Prediction/assets/105503671/b95d6f86-d43c-4fc3-ba33-b356425df677)
![image](https://github.com/iey704/Airbnb-Data-Prediction/assets/105503671/d4cb9bfd-f157-4798-b631-e30dc2cb3dd0)
![image](https://github.com/iey704/Airbnb-Data-Prediction/assets/105503671/b801147b-2f33-400e-b85b-03cc6d2e5a64)

### Modeling
**Describe the models used (Logistic Regression and Decision Tree)**
![image](https://github.com/iey704/Airbnb-Data-Prediction/assets/105503671/7ff7cb9f-98b9-4f6f-a52c-44aa9bcf5e78)
![image](https://github.com/iey704/Airbnb-Data-Prediction/assets/105503671/7907ea5b-3453-4eb7-b23e-eb28292e7d5f)

### Model Visualization
![image](https://github.com/iey704/Airbnb-Data-Prediction/assets/105503671/4568bd27-ace7-4694-af3d-c2206d42b6e3)

### Evaluation
**Use k fold cross validation to find the optimal k value**
![image](https://github.com/iey704/Airbnb-Data-Prediction/assets/105503671/bcc3cb70-52d7-44c8-8e53-babb877c22be)
![image](https://github.com/iey704/Airbnb-Data-Prediction/assets/105503671/5e326909-5620-4c7e-a7d7-b1f16838280b)

[Use confusion matrices to visualize the results of classification tasks and evaluate the performance of models](url)
**Logistic Regression**
![image](https://github.com/iey704/Airbnb-Data-Prediction/assets/105503671/6924c3a0-1cb9-4f96-a75d-8ebd0e93e416)
**decision tree**
![image](https://github.com/iey704/Airbnb-Data-Prediction/assets/105503671/17ab023d-398b-4c22-af73-e22d58de8f51)

### Best 5 combination
**Extract the top 5 combinations of all combinations considering 3 encoders (One-hot, Ordinary, Label) + 3 Scaling (MinMax, Standard, Robust) + hyperparameters**
![image](https://github.com/iey704/Airbnb-Data-Prediction/assets/105503671/6512f26d-7e0d-4467-98e2-34d97389da84)

### Analysis
**Analyze critical features in predicting destinations through modeling**
![image](https://github.com/iey704/Airbnb-Data-Prediction/assets/105503671/8aa1daf2-5b13-45f6-b89d-32dc9d4f4a49)
![image](https://github.com/iey704/Airbnb-Data-Prediction/assets/105503671/a4cd6443-50de-4b5f-b7f1-a28b17e577b7)

### Usage
**It can be used to interpret other data because it has carried out an end-to-end process that includes all the steps, including data collection, preprocessing, modeling, evaluation, and data analysis results analysis.**
