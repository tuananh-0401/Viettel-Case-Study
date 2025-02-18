# Viettel-Case-Study

This repository contains two projects focused on analyzing customer data and providing business insights for Viettel. The projects apply machine learning techniques, including clustering and classification, to derive customer segmentation and predict suitable mobile packages.

## Project Overview

### **Project 1: Customer Segmentation using K-Means Clustering and RFM Analysis**

In this project, we combined **K-Means clustering** with **RFM (Recency, Frequency, Monetary) analysis** to segment customers into distinct groups based on their purchasing behavior. The goal was to identify customer segments and provide insights that can guide targeted marketing campaigns.

#### Tools & Technologies Used:
- **Python** (for data processing and modeling)
- **Pandas** (for data manipulation)
- **Scikit-learn** (for K-Means clustering)
- **Matplotlib / Seaborn** (for data visualization)

#### Key Steps:
1. **Data Cleaning**: Removed missing values and outliers to prepare the data for analysis.
2. **RFM Analysis**: Calculated Recency, Frequency, and Monetary values to assess customer behaviors.
3. **Clustering**: Applied K-Means clustering to segment customers based on their RFM scores.
4. **Insights & Recommendations**: Identified customer segments and proposed marketing strategies for each group to maximize engagement and revenue.

#### Results:
- Defined 4 customer segments with distinct behaviors, allowing for more personalized marketing efforts.
- Recommended targeted campaigns for each segment, such as discounts for frequent buyers or re-engagement strategies for customers with low recency.

---

### **Project 2: 4G Package Classification for Travelers**

This project focuses on predicting which 4G mobile packages are most suitable for travelers based on their trip details. A classification model was developed to predict the likelihood of a traveler needing specific packages, thus optimizing marketing efforts for mobile packages.

#### Tools & Technologies Used:
- **Python**
- **Scikit-learn** (for classification model)
- **Pandas** (for data manipulation)
- **Seaborn / Matplotlib** (for data visualization)

#### Key Steps:
1. **Data Exploration**: Analyzed travel-related data to identify features that influence the choice of 4G packages.
2. **Data Preprocessing**: Cleaned and transformed the data, dealing with missing values and encoding categorical variables.
3. **Model Development**: Built a classification model (Logistic Regression, Random Forest, etc.) to predict which packages are suitable based on the customer’s trip information.
4. **Marketing Strategy**: Based on the model's output, a marketing strategy was proposed to target travelers with the most relevant packages.

#### Results:
- Created a predictive model with an accuracy rate of X% (insert your accuracy).
- Recommended targeted marketing campaigns for travelers based on the predicted packages.
- Proposed specific promotional efforts, including discounts for frequent travelers and package trials for first-time users.

---

## Conclusion

Both projects provide actionable insights into Viettel’s customer base, enabling the company to optimize its marketing campaigns. The customer segmentation model helps tailor marketing efforts to specific groups, while the classification model allows for targeting travelers with the most suitable 4G packages.
