# Customer Purchase Behavior Analysis

## 📌 Overview
This project analyzes customer purchase data to identify key trends, helping businesses optimize their marketing and sales strategies.

## Explanation of the Code and Analysis:

**Import Libraries:**

- numpy for numerical operations.
- pandas for data manipulation.
- matplotlib.pyplot for plotting.
- seaborn for enhanced visualizations.

**Load Data:**

- Reads the CSV file into a pandas DataFrame.
- Displays the first few rows, data types, and summary statistics to get an initial understanding of the data.

**Data Cleaning:**

- Null Value Handling: Fills missing values in Product_Category_2 and Product_Category_3 with 0, as these missing values likely indicate the absence of those categories.
- Duplicate Row Handling: Checks for and removes duplicate rows.

**Data Preprocessing:**

- Categorical to Numerical Conversion:
- Maps 'Gender' to 0 and 1.
- Maps the age ranges to median numerical values.
- Maps the city category to numerical values.
- Maps the stay in current city to numerical values.

  
**Analysis:**

- Top Customers: Groups the data by User_ID, calculates the total purchase amount for each user, and displays the top 10 customers.
- Age Group Analysis: Creates a countplot to show the distribution of purchases across different age groups.
- Correlation Analysis: Calculates the correlation between the frequency of purchases and the total purchase amount for each user.
- Gender Analysis: Creates a bar plot to visualize the purchase amounts by gender.
- City Category Analysis: Creates a bar plot to visualize the purchase amounts by City Category and stay in current city years.
- Occupation Analysis: Creates a bar plot to visualize the purchase amounts by occupation.
- Product Category Analysis: Creates a countplot to show the distribution of purchases across different product categories.
- Top and Least Purchased Products: Counts the occurrences of each Product_ID and displays the top 3 and least 3 purchased products.

## 🔍 Key Insights
- **26-35 Age Group** has the highest purchase activity.
- **Male Customers** spend more, despite equal purchase frequency.
- **Recent Movers to City** are the top spenders.
- **City Category B** contributes the most purchases.
- **Top Spending Occupations:** 4, 0, and 7.
- **Most Purchased Product Category:** 1.
- **Least Purchased Categories:** 7, 9, 12, 18.
- **Top 3 Selling Products:** P00025442, P00110742, P00255842.
- **Least Selling Products:** P00353042, P00309042, P00091742.

---

## Libraries Used in the Notebook
- **pandas** → Data manipulation
- **numpy** → Numerical operations
- **matplotlib & seaborn** → Data visualization
