# 🧠 AI Job Market Analysis using Python

### Data Cleaning + Visualization Project

## 📋 Project Overview

This project analyzes AI-related job postings to uncover trends in hiring, skills demand, and salary patterns.
It demonstrates the end-to-end process of data cleaning, transformation, and visualization using Python’s data science ecosystem.

### 🎯 Objectives
---
- Clean and preprocess raw AI job market data.
- Identify top hiring companies and most demanded technical skills.
- Analyze salary distributions and correlations across experience levels.
- Visualize temporal trends in AI job postings and skill demand.

### 📊 Dataset
---
**Source:** AI Job Market Dataset — Kaggle.
The dataset includes job postings with attributes such as:
Job title, company name, location,
Employment type and experience level,
Required skills and posted date,
Salary range in USD.

### 🧹 Data Cleaning Process (basic_cleanup.ipynb)
---
The data preparation notebook performs key preprocessing tasks:
- Handles missing and inconsistent entries.
- Splits and cleans skill lists (skills_required).
- Converts date columns and standardizes formats.
- Extracts salary components (min_salary, max_salary, avg_salary).
- Removes duplicate and irrelevant records.

After cleaning, the dataset is structured and ready for visual exploration.

### 📈 Exploratory Analysis & Visualizations (visualisation.ipynb)
---
The analysis notebook presents a range of statistical summaries and visual insights:
- Top Hiring Companies — identifies companies with the highest AI job postings.
- Monthly Hiring Trend (2024) — visualizes AI job posting activity over time.
- Top In-Demand Skills — reveals the most frequently requested AI skills.
- Salary Distribution by Experience Level — compares pay scales across roles.
- Correlation Heatmap — highlights numeric relationships between dataset features.
- Skill Demand vs. Salary — analyzes which skills are both popular and high-paying.
- Word Cloud — visual summary of the most common skills in job descriptions.

### 📸 Visual Highlights
---
![Dash Board](/images/output.png)
### 💡 Dashboard overview
- **Monthly Trends:** Shows hiring fluctuations throughout the year.  
- **Top Skills:** Highlights which AI skills are in highest demand.  
- **Salary Distribution:** Reveals pay variation across AI roles.  
- **Hiring Companies:** Identifies leading employers in the AI job market.
![Dash Board](/images/top%203)
### 💡 overview
- The top 3 most frequent skills for **Data Analyst** roles are displayed as trends over time.  
- Helps identify **seasonal demand** or **emerging technologies** in analytics.  
- These insights can guide upskilling and job market strategies.


### 💡 Key Insights
---
- The demand for AI-related roles continues to rise, with notable seasonal peaks.
- Python, SQL, and Machine Learning consistently rank among the most requested skills.
- Senior-level positions command significantly higher salaries, reflecting experience premiums.
- Some in-demand skills (e.g., Data Analysis, NLP) offer strong salary advantages.
- Certain companies dominate hiring activity for AI roles in 2024.

### 🛠️ Tools & Libraries
---
- Languages: Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Plotly, WordCloud
- Environment: Jupyter Notebook (VS Code)

### ⚙️ How to Run Locally
---
Clone this repository - 
git clone https://github.com/your-username/AI-Job-Market-Analysis.git.

cd AI-Job-Market-Analysis

### Create and activate a virtual environment

- python -m venv venv
- source venv/bin/activate   # for macOS/Linux
- venv\Scripts\activate      # for Windows


### Install dependencies

pip install -r requirements.txt


### Launch Jupyter Notebook

jupyter notebook


### Open and run the notebooks

- basic_cleanup.ipynb → Data cleaning and preprocessing
- visualisation.ipynb → Data visualization and insights

## Connect with Me  

- 📧 Email: *lokeshofficial66@gmail.com*  
- 💼 LinkedIn: *https://www.linkedin.com/in/lokesh-m-861658360*  
 
