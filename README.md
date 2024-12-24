# 🔍 Customer Segmentation Analysis

This project focuses on segmenting customers based on their demographic and transactional data. The goal is to identify distinct customer groups to help businesses optimize marketing strategies, personalize customer experiences, and increase overall profitability.

This project applies clustering techniques to group customers based on spending habits, demographics, and lifestyle indicators.

## **Key Insights**
### **1. Data Preparation**
- Created a `TotalAmountSpent` feature by summing expenditures across categories such as:
  - Fruits
  - Meat
  - Sweet products
  - Gold products
  - Wines
- Calculated customer `Age` from the `Year_Birth` column.
- Cleaned and standardized categorical variables (e.g., `Education`, `Marital_Status`).

### **2. Exploratory Data Analysis (EDA)**
- **Age Distribution**:
  - Most customers fall within a specific age range, with clear patterns in spending by age group.
- **Education Levels**:
  - Consolidated education levels into broader categories (e.g., Undergraduate, Graduate, Postgraduate).
  - Visualized proportions of customers in each category.
- **Spending Trends**:
  - Analyzed relationships between demographic factors (e.g., marital status, age) and spending patterns.

### **3. Clustering and Segmentation**
- Applied clustering techniques such as **K-Means** to identify distinct customer groups:
  - Segments based on spending habits and demographic features.
  - Optimal number of clusters determined using the **elbow method** and **silhouette scores**.
- Each cluster represents a specific customer persona (e.g., high spenders, budget-conscious, family-oriented).


## **Data and Tools**
### **Dataset**
- **Source**: Marketing campaign data (CSV format) containing:
  - Demographic data: Age, Education, Marital Status.
  - Transactional data: Spending across various categories.

### **Tools Used**
- **Python Libraries**:
  - `pandas` and `numpy`: Data manipulation and feature engineering.
  - `matplotlib` and `seaborn`: Data visualization.
  - `sklearn`: Clustering and evaluation metrics.
- **Google Colab**:
  - Interactive development environment for running the notebook.


## **Results**
### **Customer Segments Identified**
1. **High-Value Customers**:
   - High total spending across multiple categories.
   - Likely targets for premium product offerings.
2. **Budget-Conscious Customers**:
   - Lower spending, focus on specific categories.
   - Opportunities for discounts and promotions.
3. **Family-Oriented Customers**:
   - Spending patterns suggest purchases for family needs (e.g., meat, sweets).
   - Potential for targeted family-oriented marketing.


## **Recommendations**
1. **Marketing Strategies**:
   - Design personalized campaigns targeting each segment.
   - Focus on high-value customers for premium product offerings.
2. **Customer Retention**:
   - Offer loyalty programs to budget-conscious and family-oriented customers.
3. **Data-Driven Decision Making**:
   - Use cluster insights to allocate marketing budgets effectively.



