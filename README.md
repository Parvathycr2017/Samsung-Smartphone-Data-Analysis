📱 Samsung Smartphone Data Analysis
📌 Project Overview

This project focuses on analyzing Samsung smartphone performance using sales, market share, and 5G adoption metrics. The goal is to gain insights into revenue trends, regional performance, and the impact of 5G infrastructure on customer preference.

The analysis is performed using Python in a Jupyter Notebook, following a structured data analysis workflow.

📂 Dataset

Source: Kaggle (Samsung Xpand Dataset)

The dataset includes information such as:

Revenue ($)

Units Sold

Market Share (%)

Regional 5G Coverage (%)

5G Subscribers (millions)

Average 5G Speed (mbps)

Preference for 5G (%)

Region

⚠️ The dataset is not included in this repository.
Please download it separately from Kaggle.

🗂️ Project Structure
Samsung-Smartphone-Data-Analysis/
│
├─ data/
│   └─ Expanded_Dataset.csv   (download separately)
│
├─ Notebook.ipynb
└─ README.md

🛠️ Tools & Technologies Used

Python

Jupyter Notebook

Pandas

Matplotlib

Seaborn

🔍 Analysis Workflow

Data Overview

Dataset shape, columns, and data types

Preview using head() and tail()

Data Cleaning

Handling missing values

Removing duplicate records

Correcting data types

Exploratory Data Analysis (EDA)

Revenue distribution

Units sold by region

Market share vs revenue

5G coverage and customer preference

Pie chart analysis for regional contribution

Trend Analysis

Revenue trend over time

5G subscribers growth trend

Correlation Analysis

Correlation heatmap for numerical variables

Insights & Conclusions

Key findings from EDA and trend analysis

Business-driven insights

📈 Key Insights

Revenue and sales performance vary significantly across regions.

Higher market share is associated with increased revenue.

5G subscriber growth shows a steady upward trend.

Customer preference for 5G increases with better coverage and higher speeds.

Expansion of 5G infrastructure plays a crucial role in future sales growth.

## 📊 Key Visualizations

### 1. 5G Subscribers Trend
![5G Subscribers Trend](images/5g_subscribers_trend.png)

### 2. Average 5G Speed
![Average 5G Speed](images/avg_5g_speed.png)

### 3. Revenue Contribution by Region
![Revenue Contribution](images/revenue_contribution_region.png)

### 4. Revenue Distribution
![Revenue Distribution](images/revenue_distribution.png)

### 5. Units Sold by Region
![Units Sold by Region](images/units_sold_regional.png)


💡 Business Recommendations

Focus on high-performing regions to maximize revenue.

Expand 5G coverage and improve network speed.

Promote 5G-enabled devices in regions with growing subscriber trends.

Develop targeted strategies for underperforming regions.

▶️ How to Run the Project

Download the dataset from Kaggle.

Place the CSV file inside a folder named data.

Ensure the file name matches: Expanded_Dataset.csv.

Open Notebook.ipynb in Jupyter Notebook.

Run all cells sequentially.

👤 Author

Your Name
Data Analysis Beginner | Python & Pandas Enthusiast

⭐ Acknowledgements

Kaggle for providing the dataset

Open-source Python community

🎯 Final Note

This project demonstrates a complete data analysis workflow and can be extended further with predictive modeling or dashboard creation.
