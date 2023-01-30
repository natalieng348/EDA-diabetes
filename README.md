# EDA Project: Diagnosing Diabetes

![image](https://user-images.githubusercontent.com/96028654/215403383-e49fc304-721e-4ceb-a42d-7b085cec9bb2.png)

## Overview

In this project, we will explore the data to see how certain diagnostic factors affect the diabetes outcome of women patients using EDA.

## Goals

This notebook presents an examination of a diabetes dataset obtained from the National Institute of Diabetes and Digestive and Kidney Diseases, which can be found on [Kaggle](https://www.kaggle.com/uciml/pima-indians-diabetes-database).

The objectives of this project are to:

* Familiarize with the data
* Prepare the data for analysis by cleaning it
* Formulate relevant questions for further analysis
* Analyze the variables within the data to uncover patterns and insights related to these questions.


## Dataset

The dataset for this project was downloaded from Kaggle, which contains the following columns:

- `Pregnancies`: Number of times pregnant
- `Glucose`: Plasma glucose concentration per 2 hours in an oral glucose tolerance test
- `BloodPressure`: Diastolic blood pressure (mm Hg)
- `SkinThickness`: Triceps skinfold thickness (mm)
- `Insulin`: 2-Hour serum insulin (mu U/ml)
- `BMI`: Body mass index (weight in kg/(height in m)2)
- `DiabetesPedigreeFunction`: Diabetes pedigree function (a function which scores likelihood of diabetes based on family history)
- `Age`: Age (years)
- `Outcome`: Class variable (0 if non-diabetic, 1 if diabetic)

## Table of Contents

- 0. Goals
- 1. Data
   
   - 1.1 Overview
   
   - 1.2 Data Description
   
   - 1.3 Data Summary

- 2. Data Cleaning

   - 2.1 Missing Values

       - 2.1.1 Impute Missing Values
   
   - 2.2 Outliers
   
       - 2.2.1 Insulin
      
       - 2.2.2 SkinThickness
      
       - 2.2.3 Pregnancies

- 3. Exploratory Data Analysis
