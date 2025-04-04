# Diwali Sales Data Analysis Using Python
Exploratory Data Analysis of Diwali sales using Python to uncover customer trends and boost revenue.

## Project Objective
The objective of this project is to perform an Exploratory Data Analysis (EDA) on a Diwali sales dataset using Python and it's libraries. The goal is to uncover actionable insights about customer purchasing behavior, top-selling products, and key demographics to help a hypothetical company enhance customer experience and boost revenue during festive sales. This project demonstrates proficiency in data cleaning, analysis, and visualization using Python tools.

## Dataset Used
- <a href = "https://github.com/alina-khan-1/Data-Analysis-python/blob/main/Diwali%20Sales%20Data.csv">Diwali Sales Data</a>

## Questions Addressed
This project seeks to answer the following key questions:

- Who are the primary buyers? (Gender, Age Group, Marital Status, Occupation)
- Which states contribute the most to sales? (Orders and Amount)
- What are the top-selling product categories? (By order count and revenue)
- Which occupations have the highest purchasing power?
- How can these insights improve customer experience and revenue?

## Process
The analysis was conducted in Jupyter Notebook using Python libraries: Pandas, NumPy, Matplotlib, and Seaborn. Below is the step-by-step process:

**1. Environment Setup:**
- Installed Python and required libraries (pip install pandas numpy matplotlib seaborn).
- Launched Jupyter Notebook for interactive coding.

**2. Data Loading:**
- Loaded the CSV file into a Pandas DataFrame using pd.read_csv() with proper encoding (encoding='unicode_escape').

**3. Data Cleaning:**
- Removed unnecessary columns (Status, unnamed1) using df.drop().
- Dropped rows with null values in the Amount column (12 rows) using df.dropna().
- Converted Amount from float to integer using df['Amount'].astype(int) for cleaner analysis.

**4. Exploratory Data Analysis (EDA):**
- Used df.info() and df.describe() to understand data structure and statistics.
- Grouped data by key columns (e.g., Gender, Age Group, State) using df.groupby() and aggregated with sum() or count().
- Visualized insights with bar plots using Seaborn (sns.barplot()) and Matplotlib.

**5. Key Analyses:**
- Gender-wise sales (count and amount).
- Age group distribution and spending patterns.
- State-wise order count and revenue.
- Marital status impact on purchases.
- Occupation-based purchasing power.
- Product category performance (orders and revenue).

**6. Visualization:**
- Created bar charts to compare metrics (e.g., sns.barplot(x='Gender', y='Amount', data=df)).
- Adjusted plot sizes for readability (e.g., plt.figure(figsize=(15,5))).
  
**7. Summary:**
- Compiled insights into a concise conclusion for actionable recommendations.

## Project Insights

**1. Gender:**
- Most buyers are female (higher order count and total amount spent).
- Females exhibit greater purchasing power compared to males.
  
**2. Age Group:**
- The 26-35 age group dominates both order count and spending, with females leading within this segment.

**3. Marital Status:**
- Married women are the top spenders, contributing significantly to sales.
  
**4. State:**
- Top 3 states by order count: Uttar Pradesh, Maharashtra, Karnataka.
- Top 3 states by amount: Uttar Pradesh, Maharashtra, Haryana (Haryana overtakes Karnataka due to higher per-order spending).
  
**5. Occupation:**
- IT sector employees lead in both order count and spending, followed by Healthcare and Aviation.
  
**6. Product Category:**
- Top categories by order count: Clothing, Food, Electronics.
- Top categories by revenue: Food, Clothing, Electronics (Food surpasses Clothing in total amount).

## Final Conclusion
The Diwali sales analysis highlights that married women aged 26-35, particularly from Uttar Pradesh, Maharashtra, and Haryana, working in IT, Healthcare, and Aviation sectors, are the primary customers. They predominantly purchase Food, Clothing, and Electronics, with Food generating the highest revenue. To enhance customer experience and increase revenue, the company should:

- **Target Marketing:** Focus campaigns on married women in the 26-35 age group, emphasizing Food and Clothing deals.
- **Regional Strategy:** Prioritize Uttar Pradesh and Maharashtra with localized promotions.
- **Product Focus:** Stock high-demand items in Food and Electronics categories.
- **Occupation-Based Offers:** Offer discounts to IT and Healthcare professionals during festive seasons.
  
This project showcases my ability to clean, analyze, and visualize real-world data using Python, making it a valuable addition to my portfolio.
