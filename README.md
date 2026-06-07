# Customer Behaviour Analysis

An end-to-end data project where I explored customer shopping patterns using Python, PostgreSQL, and Power BI.

---

## What is this project about?

I worked on a retail customer dataset to understand how people shop — what they buy, how often, what they spend, and how factors like age, gender, and season affect their behaviour. The idea was to go beyond just cleaning data and actually connect it to a database and build a dashboard on top of it.

---

## Project Files

customer-behaviour-analysis/
│
├── customer_behaviour_analysis.ipynb   # Data cleaning and feature engineering
├── customer_behaviour.sql              # PostgreSQL database
└── customer_behaviour_dashboard.pbix   # Power BI dashboard

---

## Tools Used

| Tool | Why |
|---|---|
| Python (Pandas) | Cleaning and transforming the data |
| PostgreSQL | Storing the cleaned data in a database |
| SQLAlchemy | Connecting Python to PostgreSQL |
| Power BI | Building the dashboard |
| Jupyter Notebook | Writing and running the analysis |

---

## Dataset

Retail customer shopping data with around 900 records covering age, gender, items purchased, payment method, purchase amount, season, review ratings, and purchase frequency.

---

## What I did in the Notebook

- Loaded the raw CSV and did a full inspection
- Handled missing values in review ratings using category-wise median
- Cleaned up column names to make them consistent
- Created an age group column by dividing customers into Young Adult, Adult, Middle-aged, and Senior
- Mapped purchase frequency text like "Weekly" or "Monthly" into actual number of days
- Found that discount applied and promo code used were identical columns, so dropped one
- Finally pushed the clean data into PostgreSQL

---

## Dashboard

Built an interactive Power BI dashboard covering revenue by category and season, customer split by age and gender, subscription vs non-subscription behaviour, payment method preferences, and average ratings by category.

---
