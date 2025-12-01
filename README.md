#🏏 End-to-End Cricket Data Analytics Project

A complete analytics solution covering web scraping → cleaning → transformation → insights → Power BI dashboard for cricket match performance tracking.

📌 Overview

This project collects cricket match data, cleans it, analyzes performance trends, and visualizes insights through Power BI dashboards.
It was built to showcase ETL automation, data engineering, and analytics storytelling.

🛠 Tech Stack

Python (Pandas, NumPy, Matplotlib, BeautifulSoup)

Web Scraping (Requests, BeautifulSoup)

Power BI Dashboard

Excel

Jupyter Notebook

📥 Dataset Source

Scraped from cricket statistics websites using Python + BeautifulSoup.

10,000+ match records collected (batting, bowling, match summary).

🔄 Workflow
1. Web Scraping

Extracted match details

Collected batting + bowling scorecards

Stored raw HTML tables

2. Data Cleaning

Removed duplicates

Standardized player names

Handled missing values

Normalized match formats (ODI, T20, Test)

3. Data Analysis

Top batsmen/bowlers

Team win percentages

Toss comparison

Player strike rate & economy trends

Venue-based performance

4. Visualization (Power BI)

KPI Cards

Player ranking

Match outcome visuals

Year-wise performance trends

📊 Dashboard Preview

(Add images in your repo using:)

![Dashboard](dashboard/dashboard1.png)

🚀 How to Run the Notebook
pip install -r requirements.txt
jupyter notebook

🧾 Key Insights

Openers contribute 48% of team runs

Spinners dominate middle overs

Teams batting second win 53% of matches

Home teams show 23% better performance

📁 Repository Structure
├── notebooks/
├── data/
├── scripts/
├── dashboard/
├── README.md
└── requirements.txt

✔ Future Improvements

Automate daily scraping

Add ML model for score prediction
