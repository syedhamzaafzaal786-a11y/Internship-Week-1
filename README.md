# Titanic Survival Analysis: An Exploratory Data Analysis

> A complete EDA of the Titanic dataset exploring who survived the disaster and why

![Titanic](https://img.shields.io/badge/dataset-Titanic-blue)
![Python](https://img.shields.io/badge/python-3.9+-green)
![License](https://img.shields.io/badge/license-MIT-orange)

## 📋 Overview

This project performs a comprehensive exploratory data analysis (EDA) on the classic Titanic dataset. The goal is to understand the factors that influenced survival during the Titanic disaster through data cleaning, visualization, and statistical analysis. This is the canonical first step for any data science portfolio.

**Key Question**: *Who survived the Titanic and why?*

## 🎯 What I Did

- **Data Loading**: Imported the Titanic dataset with proper error handling
- **Data Cleaning**: 
  - Imputed missing Age values using median by passenger class and sex
  - Extracted deck information from Cabin (77% missing → created 'has_cabin' flag)
  - Filled missing Embarked values with mode
  - Created new features: Family Size, Is Alone, Title
- **Exploratory Analysis**:
  - Survival distribution and rates
  - Gender-based survival analysis
  - Passenger class impact on survival
  - Age distribution and survival patterns
  - Family size effect on survival
  - Correlation analysis between features
  - Title analysis as social status proxy
  - Interaction effects (Class × Sex)
- **Visualization**: Created 10+ professional plots using Matplotlib and Seaborn
- **Findings**: Documented clear, actionable insights about survival patterns

## 📊 Key Findings

| Factor | Finding |
|--------|---------|
| **Gender** | Women survived at **74%** vs 19% for men (strongest predictor) |
| **Passenger Class** | 1st class: **63%**, 2nd: **47%**, 3rd: **24%** survival |
| **Age** | Children under 10 had **60%** survival rate |
| **Family Size** | Optimal: 1-3 family members (**55-60%** survival) |
| **Title** | 'Mrs' = **79%**, 'Miss' = **70%**, 'Mr' = **16%** survival |
| **Most Vulnerable** | 3rd class men: only **14%** survived |
| **Most Privileged** | 1st class women: **97%** survived |

> **Bottom Line**: Survival was heavily determined by **gender, class, and social status** - reflecting the stark inequalities of early 20th-century society.

## 🛠️ Technologies Used

- **Python 3.9+** - Core programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical operations
- **Matplotlib** - Basic plotting
- **Seaborn** - Statistical visualizations
- **Jupyter Notebook** - Interactive development environment

## 📁 Project Structure

