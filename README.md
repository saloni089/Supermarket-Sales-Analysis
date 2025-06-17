Supermarket Sales Analysis
A comprehensive data analysis project to explore sales trends, customer behavior, and product performance using real-world transactional data from a supermarket.

Dataset Overview
Source: Public dataset typically found on Kaggle or retail simulation repositories.

Rows: 1000
Columns: 21


Tools & Libraries Used
Python 3.11+

Jupyter Notebook
Pandas, NumPy – Data cleaning and manipulation
Matplotlib, Seaborn – Visualization
Scikit-learn (if modeling included)

Data Cleaning Steps
Removed duplicates
Handled missing values (if any)
Converted Date and Time columns to appropriate datetime types
Renamed inconsistent columns
Extracted Year, Month, Day from the Date column
Computed new fields: revenue and profit margin

Exploratory Data Analysis (EDA)
Visualized sales by Branch, City, and Product Line
Analyzed Customer Type and Gender distributions
Explored correlation between Gross Income, Rating, and Quantity
Trend analysis using Time Series plots
Revenue comparisons by Payment Method

Key Insights
Branch A in Yangon had the highest sales.
Female customers contributed to more transactions.
Ewallet was the most preferred payment method.
Health and beauty & Food and beverages were top-selling categories.
Average customer ratings were high, typically 7–9.
Profit margins varied by product and customer type.

How to Run the Project
1. Clone the Repository
git clone https://github.com/yourusername/supermarket-sales-analysis.git
cd supermarket-sales-analysis

2. Install Required Libraries
pip install pandas numpy matplotlib seaborn scikit-learn

3. Run the Jupyter Notebook
jupyter notebook
Open supermarket_analysis.ipynb and run each cell.
