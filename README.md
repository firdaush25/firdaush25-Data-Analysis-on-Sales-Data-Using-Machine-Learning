📊 Data Analysis on Sales Dataset Using Machine Learning

🧾 Project by: *Firdaush Alam*  
📅 Date: *23-07-2025*  
🧠 Tools: *Pandas, Matplotlib, Seaborn, Plotly*

🔍 Project Overview:

This project performs an end-to-end **exploratory data analysis (EDA)** and **visual storytelling** using a real-world sales dataset. The goal is to generate actionable insights by cleaning the data, visualizing key patterns, and preparing for machine learning applications such as forecasting and segmentation.

🧰 Tech Stack:

| Library     | Purpose                            |
|-------------|------------------------------------|
| Pandas      | Data wrangling & manipulation      |
| Matplotlib  | Static plotting                    |
| Seaborn     | Statistical visualizations         |
| Plotly      | Interactive dashboard components   |
| Jupyter NB  | Modular coding & documentation     |

📁 Dataset Summary:

The dataset contains **1000 rows and 14 columns**, featuring:
- `Product_ID`, `Sale_Date`, `Sales_Rep`, `Region`  
- `Sales_Amount`, `Quantity_Sold`, `Unit_Cost`, `Unit_Price`  
- `Customer_Type`, `Product_Category`, `Discount`, `Payment_Method`, `Sales_Channel`, `Region_and_Sales_Rep`  

No missing values were found during analysis.

📊 Key Components:

1. ✅ Data Cleaning
- Checked missing values (row-wise & column-wise)
- Verified data types, duplicates, and value ranges
- Converted `Sale_Date` to datetime format

2. 📈 Visualizations
- **Line Plot**: Daily sales trends  
- **Scatter Plot**: Unit price vs quantity sold  
- **Bar Graph**: Total sales by region  
- **Pie Chart**: Customer type distribution  
- **Area Plot**: Cumulative quantity sold  
- **Histogram**: Discount frequency  
- **Boxplots**: Sales metrics by customer type & region  
- **Heatmaps**: Correlation matrix & categorical cross-tabulations

3. 🧠 Data Analysis Types
- **Univariate**: Distribution, outliers, mean & median  
- **Bivariate**: Quantity vs Price, Discount vs Cost  
- **Multivariate**: Correlation matrix of key metrics  

4. 📦 Feature Engineering
- `Region_and_Sales_Rep` was used to create hybrid insights  
- Sales metrics were melted into long-format for categorical comparison


💡 Insights
- **Furniture** was the most frequently sold product category  
- **North & West** regions outperformed in sales revenue  
- **Returning customers** contributed equally to sales volume  
- Discounts generally ranged from **0%–30%**, with a median of **15%**



🚀 How to Run

https://github.com/firdaush25/firdaush25-Data-Analysis-on-Sales-Data-Using-Machine-Learning.git
cd sales-data-analysis
pip install pandas matplotlib seaborn plotly jupyter
jupyter notebook

🛠️ Future Additions
- Sales forecasting using regression models  
- Customer segmentation via clustering  
- KPI dashboards using Plotly Dash or Streamlit  
