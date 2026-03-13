📊 Exploratory Data Analysis (EDA) on Retail Sales Dataset
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on a simulated retail sales dataset using Python and Pandas.

The objective of this analysis is to understand the dataset structure, identify missing values, analyze distributions, and explore relationships between variables using statistical summaries and visualizations.

EDA is a critical step in any data science or analytics workflow because it helps uncover patterns, detect anomalies, and prepare the dataset for further analysis or modeling.

🎯 Project Objectives

The main goals of this project are:

Inspect the dataset structure

Identify and quantify missing values

Generate descriptive statistics

Visualize data distributions

Detect potential outliers

Analyze relationships between numerical variables

🗂 Dataset Description

The dataset simulates daily retail order records across different cities and product categories.

Columns in the Dataset
Column	Description
order_id	Unique order identifier
city	City where the order was placed
category	Product category
order_value	Total value of the order
delivery_days	Number of days taken for delivery
rating	Customer rating (1–5)
Dataset Size

Rows: 200

Columns: 6

🧰 Tools & Libraries Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

🔍 Exploratory Data Analysis Steps
1️⃣ Data Inspection

Checked dataset dimensions

Examined data types of columns

Previewed initial rows

2️⃣ Missing Value Analysis

Counted missing values in each column

Calculated percentage of missing values

3️⃣ Descriptive Statistics

Generated summary statistics using df.describe()

Identified possible outliers in order_value

4️⃣ Data Visualization

Visualizations created:

Histogram for order_value distribution

Box plot for delivery_days to detect outliers

5️⃣ Correlation Analysis

Computed correlation matrix

Visualized relationships using a heatmap

📈 Key Insights

The order_value column contains extreme outliers compared to typical order amounts.

Delivery times generally fall between 1–14 days, indicating consistent logistics performance.

Most numerical variables show low correlation, suggesting relatively independent behavior.

📊 Example Visualizations

The notebook includes the following visualizations:

Distribution of order values

Delivery time outlier detection

Correlation heatmap

These visualizations help reveal patterns and potential anomalies in the dataset.

📁 Repository Structure

eda-assignment-harshavardhan
│
├── harshavardhan_eda_assignment.ipynb

└── README.md

▶️ How to Run the Project

Clone the repository

git clone https://github.com/J-harshavardhan/eda-assignment-harshavardhan.git

Navigate to the folder

cd eda-assignment-harshavardhan

Open the notebook

jupyter notebook

Run all cells to reproduce the analysis.

🚀 Future Improvements

Possible extensions to this project:

Handle missing values using imputation techniques

Perform advanced outlier detection

Create category-wise sales analysis

Build predictive models for order value

👨‍💻 Author

Harshavardhan J

GitHub:
https://github.com/J-harshavardhan
