# ❤️ Heart Disease Prediction Analysis

A comprehensive exploratory data analysis (EDA) project using the 2020 BRFSS (Behavioral Risk Factor Surveillance System) dataset to analyze factors associated with heart disease.

[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://python.org)
[![Pandas](https://img.shields.io/badge/Pandas-1.3+-green.svg)](https://pandas.pydata.org)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.11+-orange.svg)](https://seaborn.pydata.org)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.3+-red.svg)](https://matplotlib.org)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## 📖 Overview

This project performs exploratory data analysis on heart disease data from the CDC's Behavioral Risk Factor Surveillance System (BRFSS) 2020 dataset. The analysis aims to understand the distribution of various health and lifestyle factors and their potential relationships with heart disease occurrence.

## 📊 Dataset Information

- **Source**: [CDC BRFSS 2020 Dataset](https://www.cdc.gov/brfss/annual_data/2020/pdf/codebook20_llcp-v2-508.pdf)
- **Size**: 319,795 records × 18 features
- **Target Variable**: Heart Disease (Binary: Yes/No)
- **Class Distribution**: 
  - No Heart Disease: 292,422 (91.4%)
  - Heart Disease: 27,373 (8.6%)

### 🔍 Features Included

| Feature | Type | Description | Unique Values |
|---------|------|-------------|---------------|
| **HeartDisease** | Categorical | Target variable | Yes, No |
| **BMI** | Numerical | Body Mass Index | Continuous (16.6 - 62.42) |
| **Smoking** | Categorical | Smoking status | Yes, No |
| **AlcoholDrinking** | Categorical | Heavy alcohol consumption | Yes, No |
| **Stroke** | Categorical | History of stroke | Yes, No |
| **PhysicalHealth** | Numerical | Poor physical health days (0-30) | 0-30 |
| **MentalHealth** | Numerical | Poor mental health days (0-30) | 0-30 |
| **DiffWalking** | Categorical | Difficulty walking/climbing stairs | Yes, No |
| **Sex** | Categorical | Gender | Male, Female |
| **AgeCategory** | Categorical | Age groups | 13 categories (18-24 to 80+) |
| **Race** | Categorical | Race/ethnicity | 6 categories |
| **Diabetic** | Categorical | Diabetes status | 4 categories |
| **PhysicalActivity** | Categorical | Physical activity in past 30 days | Yes, No |
| **GenHealth** | Categorical | General health rating | 5 categories |
| **SleepTime** | Numerical | Average sleep hours | 1-24 hours |
| **Asthma** | Categorical | Asthma diagnosis | Yes, No |
| **KidneyDisease** | Categorical | Kidney disease diagnosis | Yes, No |
| **SkinCancer** | Categorical | Skin cancer diagnosis | Yes, No |

## 🛠️ Technology Stack

- **Python 3.7+**
- **Data Manipulation**: Pandas
- **Visualization**: Matplotlib, Seaborn
- **Environment**: Google Colab
- **Data Storage**: Google Drive integration

## 📈 Analysis Components

### 1. **Data Loading & Exploration**
- Dataset overview and basic statistics
- Missing value analysis (✅ No missing values found)
- Target variable distribution analysis

### 2. **Feature Analysis**
- Categorical variable distribution
- Numerical variable summary statistics
- Unique value identification for each feature

### 3. **Exploratory Data Analysis**
- **Scatter Matrix**: Pairwise relationships between all variables
- **Count Plots**: Distribution visualization for categorical features
- **Feature Distribution**: Comprehensive overview of all categorical variables

### 4. **Key Findings**
- **Class Imbalance**: Significant imbalance in heart disease cases (8.6% positive)
- **Data Quality**: Clean dataset with no missing values
- **Feature Diversity**: Mix of health indicators, lifestyle factors, and demographics
- **Age Distribution**: Covers all adult age groups from 18-24 to 80+

## 📊 Visualizations Generated

1. **Scatter Matrix Plot** (15×15): Comprehensive pairwise variable relationships
2. **Categorical Feature Distribution**: 14 count plots showing distribution of:
   - Heart Disease prevalence
   - Smoking and alcohol consumption patterns
   - Health conditions (stroke, diabetes, asthma, etc.)
   - Demographics (age, sex, race)
   - Lifestyle factors (physical activity, general health)

## 🎯 Potential Use Cases

This analysis serves as a foundation for:
- **Predictive Modeling**: Building machine learning models for heart disease prediction
- **Risk Factor Analysis**: Identifying key contributors to heart disease
- **Public Health Research**: Understanding population health patterns
- **Clinical Decision Support**: Developing screening tools
- **Health Policy**: Informing prevention strategies

## ⚠️ Data Considerations

### Limitations
- **Class Imbalance**: 91.4% negative cases may require sampling techniques
- **Observational Data**: Cannot establish causation, only associations
- **Self-Reported**: Some variables rely on participant self-reporting
- **Temporal**: Cross-sectional data from 2020 only

### Data Quality
- ✅ No missing values
- ✅ Consistent categorical encodings
- ✅ Reasonable value ranges for numerical features
- ✅ Large sample size (319K+ records)

## 🔮 Future Enhancements

- [ ] **Advanced EDA**: Correlation analysis, statistical testing
- [ ] **Feature Engineering**: Create new risk indicators
- [ ] **Machine Learning**: Implement classification models
- [ ] **Interactive Dashboards**: Build Plotly/Streamlit visualizations
- [ ] **Statistical Analysis**: Hypothesis testing for risk factors
- [ ] **Time Series**: Incorporate multi-year BRFSS data

---

⭐ **Star this repository if you found it helpful for your health data analysis projects!**
