# customer_behavior_analysis
Data analytics project showcasing customer behavior analysis using python , SQL and power BI. 

# Customer Shopping Behavior Analysis

Overview

This project analyzes customer shopping behavior using transactional data. The objective is to identify patterns in spending, product preferences, and customer engagement to support better business decisions. It covers the full analytics workflow, from data preparation to visualization and reporting.

---

Dataset

* Total Records: 3,900 transactions
* Features: 18 columns
* Includes:

  * Customer demographics (Age, Gender, Location, Subscription Status)
  * Purchase details (Item, Category, Amount, Season, Size, Color)
  * Behavioral data (Discounts, Purchase frequency, Ratings, Shipping type)

---

Tools & Technologies

* Python (Pandas, NumPy, Matplotlib/Seaborn) – Data processing and EDA
* SQL (PostgreSQL / MySQL / SQL Server) – Data querying and analysis
* Power BI – Dashboard creation and visualization
* Gamma – Presentation creation
* Jupyter Notebook / VS Code – Development environment

---

Project Steps

1. Data Loading & Exploration

* Loaded dataset using Pandas
* Examined structure using `.info()` and `.describe()`
* Identified missing values and inconsistencies

2. Data Cleaning

* Handled missing values (e.g., review ratings)
* Standardized column names (snake_case)
* Removed redundant columns
* Ensured data consistency

 3. Feature Engineering

* Created new features such as:

  * `age_group`
  * `purchase_frequency_days`
* Improved dataset usability for analysis

4. SQL Analysis

Executed queries to derive insights:

* Revenue by gender
* High-spending discount users
* Top-rated products
* Shipping type comparison
* Subscription vs non-subscription behavior
* Customer segmentation (New, Returning, Loyal)
* Revenue by age group

5. Dashboard Development

* Built an interactive Power BI dashboard
* Added filters (gender, category, shipping, subscription)
* Displayed key metrics such as revenue, average spend, and ratings

6. Reporting & Presentation

* Prepared a structured report summarizing findings
* Created a presentation using Gamma

---

Key Results

* Male customers contributed significantly higher revenue
* Clothing category generated the highest sales
* Discount usage did not necessarily reduce spending
* Loyal customers formed the largest segment
* Young adults contributed the highest revenue
* Subscription had limited impact on average spending

---

Dashboard

The Power BI dashboard includes:

* Revenue breakdown by category and age group
* Customer segmentation insights
* Subscription analysis
* Interactive filters for deeper exploration

---

 How to Run

 1. Python (EDA & Cleaning)

```bash
pip install pandas numpy matplotlib seaborn
```

* Open the notebook or script
* Run all cells in sequence

 2. Database (SQL)

* Import the cleaned dataset into PostgreSQL/MySQL/SQL Server
* Execute the provided SQL queries

3. Power BI

* Load the dataset into Power BI
* Open the `.pbix` file to view the dashboard

4. Presentation

 Open the Gamma presentation or exported slides

---

Conclusion

This project demonstrates how raw transactional data can be transformed into meaningful insights through a structured analytics workflow. The findings can support better decision-making, targeted marketing, and improved customer engagement.

---

Contact

For questions or collaboration, feel free to reach out.


