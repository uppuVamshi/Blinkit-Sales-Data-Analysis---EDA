🛒 **Blinkit Sales Data Analysis**

📌 **Project Overview**
This project performs Exploratory Data Analysis (EDA) on Blinkit Sales Data to uncover meaningful insights about product performance, outlet types, customer ratings, and sales trends.
Blinkit is an online grocery delivery platform that connects customers with nearby stores to provide groceries and essentials quickly and efficiently.

The dataset contains 8523 rows and 12 columns, including information about:
- Item Type
- Fat Content
- Outlet Type & Size
- Location Tier
- Item Visibility
- Sales
- Customer Ratings
After cleaning and removing outliers, the final dataset contains 6472 rows × 12 columns.

🎯 **Objectives**
- Understand the structure of the dataset
- Perform data cleaning and preprocessing
- Detect and remove outliers using IQR method
- Conduct Univariate, Bivariate, and Multivariate analysis
- Extract business insights from sales data

🛠️ **Technologies Used**
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

📊 **Data Cleaning Process**
-  Handled missing values (Item Weight column)
- Checked and removed duplicate values
- Fixed inconsistent categorical values (LF → Low Fat, reg → Regular)
- Detected outliers using IQR method
- Removed outliers from:
- Item Visibility
- Rating
- Final Cleaned Dataset
- No missing values
- No duplicate values
- Consistent categorical data
- Ready for analysis

🔎 **Key Analysis Performed**
1️⃣ **Univariate Analysis**
- Distribution of Sales
- Most sold Item Types
- Distribution of Outlet Types
- Rating distribution

2️⃣ **Bivariate Analysis**
- Outlet Type vs Sales
- Item Type vs Rating
- Item Weight vs Sales
- Fat Content vs Total Sales

3️⃣**Multivariate Analysis**
- Item Type performance across Outlet Types
- Correlation heatmap of numerical variables
- Sales vs Item Weight across Outlet Types (with Rating impact)

📈 **Key Insights**
- Fruits & Vegetables and Snack Foods are the most sold items
- Supermarket Type1 outlets contribute the highest share of sales
- Regular-fat items generate slightly higher total sales than Low-fat items
- Item Weight has almost no correlation with Sales
- Ratings do not strongly influence Sales performance
- Sales performance is relatively similar across different outlet types

📌 **Correlation Summary**
- Weak correlation between Item Weight and Sales
- Very low correlation between Visibility and Rating
- Sales moderately consistent across outlet categories

📂 **Dataset Features**
| Feature                   | Description                   |
| ------------------------- | ----------------------------- |
| Item Fat Content          | Low Fat / Regular             |
| Item Identifier           | Unique product ID             |
| Item Type                 | Category of product           |
| Outlet Establishment Year | Year outlet started           |
| Outlet Identifier         | Unique outlet ID              |
| Outlet Location Type      | Tier 1 / Tier 2 / Tier 3      |
| Outlet Size               | Small / Medium / High         |
| Outlet Type               | Grocery Store / Supermarket   |
| Item Visibility           | Display visibility percentage |
| Item Weight               | Weight of product             |
| Sales                     | Sales value                   |
| Rating                    | Customer rating               |


📌 **Business Conclusions**
- Fast-moving consumer goods drive most revenue
- Larger supermarkets slightly outperform smaller outlets
- Product weight does not impact sales significantly
- Customer preference leans slightly towards Regular products
- Outlet location has minimal impact on sales performance
