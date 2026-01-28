# Washing-Machine-Price-and-Feature-Analysis
🧺 Washing Machine Price & Feature Analysis (EDA Project)
📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of washing machine products collected from the Flipkart website using web scraping.
The aim is to analyze how different product features influence pricing, brand performance, and customer preferences in the washing machine market.

Using Python and popular data analysis libraries, the project uncovers meaningful insights related to price trends, feature impact, and brand dominance.

🎯 Objectives

Collect real-world washing machine data using web scraping

Clean and preprocess raw data for accurate analysis

Perform Exploratory Data Analysis (EDA)

Analyze price trends across:

Brands

Capacity (kg)

Load type

Automation type

Study the relationship between features (RPM, capacity, star rating) and price

Identify popular brands based on customer ratings and product count

Visualize insights using charts and graphs for better interpretation

🌐 Data Collection (Web Scraping)

Source: Flipkart – Washing Machine Listings

Tools used:

Browser Developer Tools (Inspect Element)

Requests and BeautifulSoup (Python)

Extracted structured product data such as:

Brand

Price

Capacity

Load Type

Automation Type

Star Rating

RPM

Warranty

Customer Rating

📂 Dataset Overview

Total records: ~950 rows

Total columns: 9

Data stored and analyzed in CSV format

Column Types

Categorical Columns

Brand

Automation_Type

Load_Type

Numerical Columns

Price

Capacity_kg

Star_Rating

RPM

Warranty_Years

Customer_Rating

🧹 Data Cleaning & Preprocessing

Removed duplicate records

Handled missing values:

Numerical → replaced with median

Categorical → replaced with mode

Cleaned and standardized data:

Removed symbols like ₹, commas, “kg”

Converted columns to numeric format

Extracted numeric values from text fields (e.g., “2 Years” → 2)

Removed outliers in:

Price

RPM

Capacity

Standardized text fields for consistency

Reset index after cleaning

📊 Exploratory Data Analysis (EDA)
Univariate Analysis

Distribution analysis using:

Histograms

Boxplots

Descriptive statistics:

Mean, Median, Min, Max, Standard Deviation

Frequency analysis of:

Brands

Load Type

Automation Type

Bivariate Analysis

Scatter plots:

Price vs Capacity

Price vs RPM

Bar plots:

Average price by Brand

Average price by Load Type and Automation Type

Boxplots:

Price variation across machine types

Correlation heatmap to analyze relationships between numerical features

🛠️ Tools & Technologies

Python

BeautifulSoup & Requests (Web Scraping)

Pandas (Data Manipulation)

Matplotlib & Seaborn (Visualization)

Jupyter Notebook

🔑 Key Insights

Prices range from ₹6,000 to ₹47,000

Fully Automatic and Front Load machines are more expensive

Top Load and Semi Automatic machines are more frequent

Brands like LG, Samsung, and IFB dominate the market

Strong correlation observed between:

Capacity, RPM, and Price

Higher features generally lead to higher pricing

✅ Conclusion

This project successfully demonstrates how web scraping combined with EDA can reveal valuable market insights.
The analysis highlights how washing machine prices are influenced by features, brand reputation, and efficiency, providing useful information for customers, analysts, and businesses.
