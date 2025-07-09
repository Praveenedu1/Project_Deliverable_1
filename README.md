# Customer Behavior Analysis - Project Deliverable 1

## Advanced Big Data and Data Mining - Bi-term 2

## Project Overview

This project focuses on comprehensive customer behavior analysis using advanced data mining techniques. The dataset contains 1000 customer records with 28 diverse attributes covering demographic information, purchase behavior, preferences, and satisfaction metrics.

## Dataset Summary

**Dataset Characteristics:**
- **Records:** 1000 customer entries
- **Features:** 28 attributes
- **Data Types:** Mixed (numerical, categorical, boolean)
- **Domain:** E-commerce customer behavior analysis

**Key Attributes:**
- **Demographic:** Age, Gender, Income Level, Education, Occupation, Location
- **Purchase Behavior:** Purchase Amount, Frequency, Category, Channel, Payment Method
- **Customer Metrics:** Brand Loyalty, Product Rating, Customer Satisfaction, Return Rate
- **Digital Engagement:** Social Media Influence, Ad Engagement, Device Usage
- **Preferences:** Discount Sensitivity, Shipping Preference, Purchase Intent

## Key Insights from Analysis

### 1. Data Quality Assessment
- **Missing Values:** 2 features with missing data (Social Media Influence: 24.7%, Engagement with Ads: 25.6%)
- **Duplicates:** No duplicate records found
- **Data Types:** Properly formatted with mixed data types suitable for comprehensive analysis

### 2. Customer Demographics
- **Age Distribution:** Normal distribution across age groups (18-80 years)
- **Gender Balance:** Relatively balanced representation
- **Income Levels:** Even distribution across Low, Medium, and High categories
- **Education:** Diverse educational backgrounds from High School to PhD

### 3. Purchase Behavior Patterns
- **Purchase Frequency:** Wide variation (1-20 purchases) indicating diverse customer engagement levels
- **Brand Loyalty:** Scores range from 1-10, showing varied customer loyalty
- **Customer Satisfaction:** Generally positive ratings with room for improvement
- **Purchase Channels:** Multi-channel approach (Online, In-Store, Mobile App)

### 4. Digital Engagement
- **Device Usage:** Customers use multiple devices (Desktop, Mobile, Tablet)
- **Payment Methods:** Diverse payment preferences (Credit Card, Debit Card, PayPal, Cash)
- **Social Media Influence:** Mixed levels of social media impact on purchase decisions

### 5. Key Correlations Identified
- Potential relationship between brand loyalty and customer satisfaction
- Research time may influence product ratings
- Income level appears to affect purchase frequency
- Discount sensitivity varies across customer segments

## Data Cleaning Steps Performed

### 1. Missing Value Treatment
- **Strategy:** Mode imputation for categorical variables
- **Social Media Influence:** Filled with most frequent value
- **Engagement with Ads:** Filled with most frequent value
- **Rationale:** Preserves data distribution while maintaining dataset completeness

### 2. Data Type Corrections
- **Purchase Amount:** Converted categorical ranges to numerical scale for analysis
- **Boolean Variables:** Properly formatted for analysis
- **Categorical Encoding:** Prepared for future modeling steps

### 3. Outlier Detection
- **Method:** Interquartile Range (IQR) technique
- **Features Analyzed:** Age, Purchase Frequency, Brand Loyalty, Research Time
- **Decision:** Outliers retained for comprehensive analysis but flagged for future consideration

### 4. Data Validation
- **Duplicate Check:** No duplicates found
- **Consistency Check:** All data formats validated
- **Range Validation:** All numerical values within expected ranges

## Challenges Encountered and Solutions

### 1. Missing Data Challenge
**Challenge:** Significant missing values in Social Media Influence (24.7%) and Ad Engagement (25.6%)
**Solution:** Applied mode imputation to maintain data integrity while preserving distribution patterns

### 2. Mixed Data Types
**Challenge:** Categorical purchase amounts hindering numerical analysis
**Solution:** Created numerical mapping while preserving original categorical data

### 3. Feature Complexity
**Challenge:** 28 diverse features requiring different handling approaches
**Solution:** Systematic categorization and tailored preprocessing for each data type

### 4. Outlier Management
**Challenge:** Determining appropriate outlier treatment strategy
**Solution:** Identified outliers using IQR method but retained for comprehensive analysis

## Technical Implementation

### Tools and Libraries Used
- **Python 3.x**
- **Pandas:** Data manipulation and analysis
- **NumPy:** Numerical computations
- **Matplotlib & Seaborn:** Data visualization
- **Scipy:** Statistical analysis

### Visualization Highlights
- Age distribution histograms
- Purchase amount analysis by gender
- Customer satisfaction distribution
- Purchase channel distribution pie charts
- Correlation heatmaps for numerical features
- Outlier detection box plots

## Future Modeling Directions

### 1. Feature Engineering
- Create derived features from existing data
- Implement proper categorical encoding
- Scale numerical features for modeling

### 2. Potential Modeling Approaches
- **Regression:** Predict purchase amount or customer satisfaction
- **Classification:** Classify customers into loyalty segments
- **Clustering:** Group customers based on behavior patterns
- **Association Rules:** Find relationships between purchase patterns

### 3. Advanced Analytics
- Customer segmentation analysis
- Predictive modeling for customer behavior
- Recommendation system development
- Churn prediction modeling


## Key Deliverables

- Dataset selection and justification
- Data loading and structure inspection
- Comprehensive data cleaning
- Exploratory data analysis with visualizations
- Missing value treatment
- Outlier detection and analysis
- Key insights and findings
- Future modeling recommendations

## Conclusion

This analysis successfully prepared a comprehensive customer behavior dataset for advanced data mining techniques. The cleaned and explored dataset provides a solid foundation for future deliverables, including feature engineering, predictive modeling, clustering, and association rule mining.

The insights gained from this exploratory analysis will guide strategic decisions in subsequent modeling phases, ensuring that the most relevant patterns and relationships are leveraged for actionable business intelligence.
