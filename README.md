# Module 3 Milestone 1 – Machine Learning Project

## 📌 Project Overview

This project is part of our Master's in Data Science coursework and represents the first milestone in a multi-part machine learning pipeline. The overall objective is to build a predictive model using real-world housing data to estimate property values or identify trends. This milestone focused on data cleaning, preprocessing, and feature selection in preparation for modeling.

## 🧠 Goal

Our goal for Milestone 1 was to:

- Understand the dataset structure and identify potential issues
- Perform thorough exploratory data analysis (EDA)
- Clean and prepare the data for modeling
- Select and engineer features relevant to our prediction task
- Document decisions that will guide future model development

## 🗂️ Dataset

We used a real estate dataset provided for the course, which included information such as:

- Property characteristics (size, location, year built, etc.)
- Tax information
- Geographic identifiers
- Categorical and numeric variables with varying levels of missingness

## 🔧 What We Did

### ✅ 1. Data Cleaning
- Dropped non-informative or overly sparse features like `fireplaceflag`, `taxdelinquencyflag`, and `censustractandblock`
- Handled missing values through targeted imputation strategies
- Standardized and cleaned categorical fields where appropriate

### ✅ 2. Feature Selection
- Removed columns with too many unique values or low variance
- Retained features deemed useful for modeling, such as square footage, location ZIP codes, and construction year
- Identified potential features for future encoding (e.g., `airconditioningtypeid`, `heatingorsystemtypeid`)

### ✅ 3. Data Preparation
- Converted relevant data types
- Created a clean dataset ready for modeling
- Documented rationale for dropping or keeping each column

## 📁 File Structure

- `Milestone1_Report.ipynb` – Jupyter notebook containing all data preparation and cleaning code
- `cleaned_data.csv` – Final cleaned dataset ready for modeling (if exported)
- `README.md` – This file
- `Module3_Milestone1_Reflection_TetianaKravchuk.docx` – Individual reflection on teamwork
- `README_Milestone1_Team.md` – Shared explanation of team progress (if applicable)

## 🙋‍♀️ Teamwork Reflection

Each team member contributed to data exploration and decision-making. We discussed which features to retain or remove and shared insights to improve the data quality. A detailed individual reflection is included in the Word document submission.

## 🚀 Next Steps (Milestone 2)

In the next milestone, we plan to:

- Perform feature encoding and scaling
- Train baseline regression models
- Evaluate model performance using cross-validation
- Begin hyperparameter tuning
