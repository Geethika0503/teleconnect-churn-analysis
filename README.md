# Teleconnect: Customer Churn Analysis & Retention Intelligence

TeleConnect Customer Churn Analysis is a Python-based data analysis project that studies customer churn and identifies the main factors that may cause customers to leave a telecom service.

The project focuses on cleaning customer data, understanding churn patterns, and identifying customers who may be at higher risk of leaving.

## Features

* Load and explore customer data
* Clean missing and incorrect values
* Remove duplicate records
* Handle invalid customer ages
* Analyze customer churn
* Identify high-risk customer groups
* Calculate churn rates
* Generate useful business insights
* Provide recommendations to reduce customer churn

## Technologies Used

* Python
* Pandas
* NumPy
* Jupyter Notebook
* Git & GitHub

## Project Structure

```text
teleconnect-capstone-starter/
│
├── customers_2025.csv
├── customers_clean.csv
├── teleconnect_churn_student.ipynb
├── README.md
└── .gitignore
```

## Dataset

The project uses customer data containing information such as:

* Customer details
* Age
* Tenure
* Contract type
* Support calls
* Monthly charges
* Customer churn status

The dataset is used to understand customer behavior and find patterns related to churn.

## Data Cleaning

Before performing the analysis, the dataset is cleaned by handling:

* Missing values
* Duplicate records
* Invalid ages
* Incorrect or inconsistent data

For example, invalid ages such as values below 21 or above 110 are removed from the analysis.

A cleaned dataset is then created for further analysis.

## Churn Analysis

The project analyzes different factors that may be related to customer churn, including:

* Contract type
* Customer tenure
* Number of support calls
* Customer charges
* Customer demographics

One important high-risk group identified in the analysis is customers who have:

* Month-to-month contracts
* Tenure of 6 months or less
* Two or more support calls

This group shows a significantly higher churn rate compared with the overall customer base.

## How to Run the Project

### 1. Clone the repository

```bash
git clone <your-repository-url>
```

### 2. Open the project folder

```bash
cd teleconnect-capstone-starter
```

### 3. Install the required packages

```bash
pip install pandas numpy jupyter
```

### 4. Run the notebook

```bash
jupyter notebook
```

Open:

```text
teleconnect_churn_student.ipynb
```

Run the notebook cells from top to bottom.

## Business Insights

The analysis helps TeleConnect understand:

* Which types of customers are more likely to leave
* Which customer groups have higher churn rates
* How contract type affects churn
* Whether low-tenure customers are at higher risk
* How customer support interactions may relate to churn

These insights can help the company improve customer retention and focus its efforts on high-risk customers.

## Recommendations

Based on the analysis, TeleConnect could:

* Give extra attention to new customers
* Improve support for customers with repeated complaints
* Offer suitable plans to month-to-month customers
* Provide special offers to high-risk customers
* Monitor customers with multiple support calls

## Learning Outcomes

Through this project, I learned:

* Data cleaning using Python
* Working with CSV datasets
* Handling missing and duplicate data
* Identifying invalid values
* Exploratory data analysis
* Calculating churn rates
* Finding high-risk customer groups
* Converting data into business insights
* Using Git and GitHub for project management

## Future Improvements

Some possible improvements are:

* Build a machine learning model to predict future churn
* Create a customer churn dashboard
* Add customer segmentation
* Use more recent customer data
* Develop an automated churn-risk scoring system
* Create retention recommendations for individual customers
