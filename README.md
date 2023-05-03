# Data Science Salary Estimator

This repository contains code and data for a data science salary estimator project. The project aims to predict the salary of data scientists based on various factors such as work experience, employment type, job title, and company size. 

The project consists of the following components:

## - `data` 
This directory contains the dataset used for training and testing the models. The dataset is sourced from various job boards and includes features such as work experience, job title, salary, and company size.

The dataset for this project includes the following variables:

- `work_year`: The year in which the salary was paid.
- `experience_level`: The experience level of the employee during the work year.
- `employment_type`: The type of employment for the role, such as full-time, part-time, or contract.
- `job_title`: The job title for the role worked in during the year.
- `salary`: The total gross salary amount paid for the year.
- `salary_currency`: The currency of the salary paid as an ISO 4217 currency code.
- `salary_in_usd`: The salary amount converted to US dollars.
- `employee_residence`: The primary country of residence for the employee during the work year, as an ISO 3166 country code.
- `remote_ratio`: The overall amount of work done remotely during the work year.
- `company_location`: The country of the employer's main office or contracting branch.
- `company_size`: The median number of people who worked for the company during the work year.

## - `notebooks` 
This directory contains Jupyter notebooks used for data exploration, preprocessing, feature engineering, model building, and evaluation. Each notebook covers a specific stage in the data science workflow and includes detailed explanations of the code and results.

## - `models`
This directory contains trained machine learning models for predicting salaries based on different algorithms such as linear regression, decision trees, and random forests. The models are saved in serialized format and can be loaded for deployment in a production environment.

## - `scripts` 
This directory contains Python scripts for automating data collection, cleaning, and preprocessing tasks. The scripts can be used to update the dataset with new job postings and to automate the model training process. 

The project is implemented in Python using various libraries such as NumPy, Pandas, Scikit-learn, and Matplotlib. The code is well-documented and follows best practices for data science project organization and reproducibility.

Feel free to explore the code and data in this repository to learn more about the project. Thank you for visiting!
