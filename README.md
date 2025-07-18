# Data-Wrangling---Used-Cars-Pricing
A comprehensive data preprocessing pipeline that transforms raw automotive industry data into a clean, analysis-ready dataset. This project demonstrates essential data science skills through systematic handling of real-world data quality issues commonly encountered in business analytics.

## Dataset Overview

**Source**: UCI Machine Learning Repository - Automobile Dataset  
**Domain**: Automotive Industry Analytics  
**Size**: 205 records with 26 attributes  
**Complexity**: Mixed data types, missing values, inconsistent formats

The dataset contains comprehensive automobile specifications including technical features (engine size, horsepower, fuel efficiency), categorical attributes (make, body style, fuel type), and pricing information. This represents typical business data challenges found in manufacturing, retail, and market analysis contexts.

## Data Preprocessing Pipeline

**Data Quality Assessment & Cleaning**
- Identified and standardized missing value representations (`?` → `NaN`)
- Applied domain-appropriate imputation strategies (mean for continuous, mode for categorical)
- Implemented data validation and quality control measures
- Handled incomplete records with business logic (removed entries without target variable)

**Data Type Optimization**
- Corrected inconsistent data types for computational efficiency
- Converted string representations to appropriate numerical formats
- Ensured data integrity across mixed-type datasets

**Feature Engineering & Standardization**
- Transformed units for international compatibility (MPG → L/100km conversion)
- Created standardized metrics for cross-regional analysis
- Applied domain knowledge to enhance data usability

**Data Normalization & Scaling**
- Implemented min-max normalization for dimensional attributes
- Prepared features for machine learning algorithms
- Maintained data relationships while enabling fair comparisons

**Categorical Data Processing**
- Applied binning techniques to create meaningful segments (horsepower categories)
- Generated one-hot encoded variables for categorical features
- Optimized data structure for predictive modeling and statistical analysis

**Advanced Feature Creation**
- Developed categorical groupings from continuous variables
- Created binary indicator variables for regression analysis
- Enhanced dataset dimensionality for comprehensive modeling

## Technical Implementation

This project applies industry-standard data science methodologies to address common data quality challenges:

- **Systematic Data Assessment**: Comprehensive evaluation of data integrity and quality issues
- **Strategic Imputation**: Domain-informed approaches to handling missing values and outliers  
- **Feature Engineering**: Creation of analytical variables optimized for downstream modeling
- **Pipeline Architecture**: Reproducible workflow design suitable for production environments
- **Quality Validation**: Implementation of data integrity checks and validation protocols

## Outcomes

**clean_df.csv**: Analysis-ready dataset with standardized features, proper data types, and complete records suitable for machine learning and statistical analysis.

*This preprocessing foundation supports advanced analytics including predictive modeling, market segmentation, and pricing optimization across automotive industry applications.*
