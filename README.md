Project Objective: The telecom company was facing a high customer churn rate and needed a clear understanding of why customers are leaving, which segments are most affected etc. 
The goal was to build a data-driven dashboard to track churn behavior and provide actionable insights.

KPI’s & Metrics: 
-	Total Churned, Churn Rate, New Joiners and Joiner Rate
-	Total Revenue, Revenue Loss and Loss Rate
-	Churn by Gender, Churn by Tenure Groups, Churn by City, Internet Type and Payment Method

Data Source and Transformation: Data was pulled from database like MySQL workbench (customer_id, customer_age, gender, tenure, city, churn_category etc). Used Python Pandas for data understanding, cleaning and missing/null values.

Dax & Features: 
-	Used Dax measure to calculate Churn Rate, Joiner Rate and Revenue Loss % and also used slicer for filtering.

Visualization:
-	Bar Charts for churn by city, contract, internet type.
-	Line + Column Chart churn rate by tenure.
-	Cards for various Services.
-	KPI’s for high level insights.

Outcomes: 
-	Month-to-month contract customers churn the most (1655) 
-	Short tenure (1–12 months) has highest churn (47.44%) 
-	Competitor is main reason (~45%) 
-	Fiber optic users churn more than others 
-	San Diego & big cities have highest churn volume

Business Impact: 
1. Key Problems 
    - High churn in early tenure customers 
 - Weak retention for monthly contracts 
 - Strong competitor impact 
 - Revenue loss concentrated in specific segments
2. Business Recommendations:
    - Introduce loyalty plans for new customers 
    - Promote long-term contracts (1–2 years) 
    - Improve pricing & competitor offers 
    - Focus retention campaigns on: Fiber users, High churn cities
3. Outcome:
    - Provided a clear, data-backed strategy 
    - Helped stakeholders reduce churn & protect revenue
