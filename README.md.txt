# 🛒 Supermarket Sales Data Analysis

## Project Overview
This project analyzes sales transactions from a multi-branch supermarket to uncover performance patterns, customer preferences, and operational insights.  
The dataset contains information such as branch, city, customer type, gender, product line, payment method, total amount, tax, and rating.

## Objectives
- Analyze sales performance across cities and branches  
- Identify the most profitable product lines  
- Examine gender-based spending patterns  
- Study payment preferences of customers  
- Discover sales peaks by day and time

## Dataset
- **File:** `supermarket_sales.csv`  
- **Source:** Public retail sales dataset (Kaggle / internal file)  
- **Main Columns:**  
  `Invoice ID`, `Branch`, `City`, `Customer type`, `Gender`,  
  `Product line`, `Unit price`, `Quantity`, `Tax`, `Total`,  
  `Date`, `Time`, `Payment`, `Gross income`, `Rating`

## Tools & Libraries
- Python 3.x  
- Jupyter Notebook  
- Pandas, NumPy – data manipulation  
- Matplotlib, Seaborn – visualization  

## Steps Performed
1. **Data Loading & Inspection** – checked shape, info, and descriptive statistics  
2. **Data Cleaning** – handled missing values, corrected data types, removed duplicates  
3. **Feature Engineering** – extracted month/day, computed gross margin & total revenue  
4. **Exploratory Data Analysis (EDA)** – explored branch, gender, and product trends  
5. **Visualization** – bar, pie, box, line plots for clearer business insights  
6. **Insights & Storytelling** – summarized results with visual evidence  

## Key Insights
- **Branch B** achieved the highest sales overall.  
- **Health & Beauty** and **Food & Beverages** were the top-earning product lines.  
- **Female customers** tend to spend slightly more on average.  
- **E-wallet** and **Credit Card** are the most preferred payment modes.  
- **Weekend afternoons** showed the highest transaction frequency.

## Results
The analysis provides a clear overview of sales performance and customer behavior, supporting better decision-making in marketing and inventory planning.

##  Requirements
```bash
pip install -r requirements.txt
