# superstore-profit-risk-analysis
End-to-end retail analytics project analyzing sales, profitability, discount impact, and customer risk using Python, SQL, and Tableau.

The analysis focuses on understanding:
- Sales and profit performance
- Time trends and seasonality
- Product and category profitability
- Regional performance differences
- Customer behavior and segmentation
- The relationship between discounts and profit
- Customer profitability risk
After completing exploratory data analysis (EDA), a Logistic Regression model was built to predict customer profitability risk.

## Tools
- Python
- Pandas
- NumPy
- SQL
- Tableau
- Matplotlib
- Seaborn
- Scikit-learn


### 2. Exploratory Data Analysis (EDA)

The analysis was organized into five major business dimensions.

---

#### Overall Sales Analysis

This section focused on the overall business performance and profitability structure, including:

- Total sales
- Total profit
- Profit margin
- Average order value
- Overall loss rate

The goal was to understand the company’s overall operational performance before drilling into specific business problems.

---

#### Time Trend Analysis

Time-based analysis was conducted using the order date field to identify business trends and operational fluctuations over time.

Key analyses included:

- Overall sales trends
- Profit trends
- Seasonal fluctuations
- Volatility and anomaly detection
- Discount trends over time

This analysis helped identify periods of unstable profitability and potential impacts of discount strategies on long-term margins.

---

#### Product & Category Analysis

The product analysis was structured around four analytical questions: Where, Which, Why, and What.

##### Where
Identify where profitability issues occur:

- Sales and profit margin comparison by category
- Profit and discount comparison across product groups

##### Which
Identify which products contribute most to profit or loss:

- Top-performing products
- Loss-driving products
- Sub-category profitability ranking

##### Why
Explore why certain products or categories become unprofitable:

- Relationship between discount and profit
- Relationship between sales growth and margin decline
- Discount-driven profitability pressure

##### What
Generate business improvement directions:

- Product structure optimization
- Reducing excessive discount dependence
- Improving low-margin product strategies

---

#### Regional Analysis

Geographic analysis was performed at multiple levels:

- Region analysis
- State analysis
- City analysis

Cross-dimensional analysis between products and regions was also conducted to identify regional profitability patterns.

Key analyses included:

- Product performance across regions
- Top 10 most profitable region-product combinations
- Top 10 loss-driving state & region-product combinations
- Regional discount and profit comparison

The purpose was to identify high-risk regions and understand how geographic factors influence profitability.

---

#### Customer Analysis

Customer-level analysis focused on identifying high-value and high-risk customer groups.

Key analyses included:

- Customer segmentation
- RFM analysis
- Customer Lifetime Value (CLV)
- High-value customer identification
- Customer profitability analysis
- Discount sensitivity analysis

The analysis explored how customer purchasing behavior and discount exposure relate to long-term profitability.

---

### 3. Machine Learning Analysis

A Logistic Regression model was built to predict customer profitability risk based on customer purchasing behavior and discount patterns.

Features included:

- AOV (Average Order Value)
- Discount
- Frequency
- Recency
- Monetary value

The model was used to identify high-risk customers and evaluate how discount strategies and customer purchasing behavior influence profitability outcomes.

A Random Forest model was also tested for comparison. Although Random Forest achieved reasonable overall accuracy, Logistic Regression produced better recall and more stable performance in identifying high-risk customers, making it more suitable for this business problem.

---

### 4. SQL Analysis

SQL was used to perform:

- Aggregation analysis
- Ranking analysis
- Customer segmentation
- Profitability comparison
- KPI calculations

---

## Tableau Dashboards

- Sales vs Profit Dashboard
- Discount-Driven Profitability Dashboard
- Customer Risk Dashboard
- Regional Analysis Dashboard
