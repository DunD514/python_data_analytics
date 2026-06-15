<div align="center">

# 📊 Data Scientist Job Market Analysis

### Exploring Global Data Science Careers Through Python, Data Visualization, and Real-World Job Market Data

<p>
<img src="https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python">
<img src="https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas">
<img src="https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge">
<img src="https://img.shields.io/badge/Seaborn-Statistical%20Graphics-green?style=for-the-badge">
</p>

</div>

---

## 📑 Table of Contents

* [Overview](#-overview)
* [Business Questions](#-business-questions)
* [Tools Used](#-tools-used)
* [Project Notebooks](#-project-notebooks)
* [Skill Demand Analysis](#-skill-demand-analysis)
* [Skill Trend Analysis](#-skill-trend-analysis)
* [Salary Analysis](#-salary-analysis)
* [Highest Paying vs Most Demanded Skills](#-highest-paying-vs-most-demanded-skills)
* [Optimal Skills Analysis](#-optimal-skills-analysis)
* [Key Takeaways](#-key-takeaways)
* [What I Learned](#-what-i-learned)
* [Future Improvements](#-future-improvements)
* [Acknowledgements](#-acknowledgements)

---

# 📖 Overview

Choosing which technologies to learn is one of the biggest challenges for aspiring Data Scientists.

Thousands of job postings mention hundreds of tools, frameworks, programming languages, and cloud technologies. Some skills appear in nearly every role but offer average salaries, while others command premium compensation despite appearing in fewer job postings.

The goal of this project was to answer a practical question:

> **Which skills should an aspiring Data Scientist focus on to maximize both employability and earning potential?**

Using Python and real-world job posting data, I analyzed:

* Skill demand across major data careers
* Monthly trends in Data Science technologies
* Salary distributions across data roles
* The relationship between demand and compensation
* High-value skills worth investing time in

<br>

<p align="center">
  <img src="project/images/optimal_skills.png" width="95%">
</p>

<p align="center">
  <em>Figure 1. Relationship between skill demand and median salary for Data Science skills.</em>
</p>

---

# 🎯 Business Questions

This project answers the following questions:

### 1. Which skills are most demanded across Data Analyst, Data Scientist, and Data Engineer roles?

### 2. How do Data Science skill requirements change throughout the year?

### 3. Which data careers offer the highest compensation?

### 4. Are the highest-paying skills also the most demanded?

### 5. Which technologies provide the best balance between salary and demand?

---

# 🛠️ Tools Used

### Programming

* Python

### Data Analysis

* Pandas

### Data Visualization

* Matplotlib
* Seaborn

### Development Environment

* Jupyter Notebook
* Visual Studio Code

### Version Control

* Git
* GitHub

---

# 📚 Project Notebooks

| Notebook                | Description               |
| ----------------------- | ------------------------- |
| `EDA.ipynb`             | Exploratory Data Analysis |
| `skills_demanded.ipynb` | Skill Demand Analysis     |
| `skills_trend.ipynb`    | Skill Trend Analysis      |
| `salary_analysis.ipynb` | Salary Analysis           |
| `optimal_skills.ipynb`  | Optimal Skills Analysis   |

---

# 📈 Skill Demand Analysis

Understanding which skills employers request most frequently provides a roadmap for aspiring data professionals.

<p align="center">
  <img src="project/images/skills_likelihood.png" width="95%">
</p>

<p align="center">
  <em>Figure 2. Likelihood of skills appearing in job postings for Data Analysts, Data Scientists, and Data Engineers.</em>
</p>

## Key Insights

### Data Analysts

Most requested skills:

* SQL (47.1%)
* Excel (34.1%)
* Python (29.2%)
* Tableau (23.7%)
* Power BI (20.1%)

### Data Scientists

Most requested skills:

* Python (66%)
* SQL (45.8%)
* R (34.6%)
* SAS (17.1%)
* Tableau (17.1%)

### Data Engineers

Most requested skills:

* SQL (60.7%)
* Python (58%)
* AWS (33.3%)
* Azure (32.6%)
* Spark (28.8%)

## What This Means

The chart reveals a clear pattern:

* SQL is the universal language of data.
* Python dominates technical data roles.
* Data Engineering increasingly requires cloud expertise.
* Data Analysts continue to rely heavily on reporting and visualization tools.

### Real-World Application

For someone entering the industry today:

1. Learn SQL first.
2. Learn Python second.
3. Specialize afterward.

This approach maximizes flexibility and creates opportunities across multiple career paths.

---

# 📅 Skill Trend Analysis

Technology trends change rapidly, but foundational skills often remain valuable for years.

<p align="center">
  <img src="project/images/skill_trend.png" width="95%">
</p>

<p align="center">
  <em>Figure 3. Monthly demand trends for the most requested Data Science skills.</em>
</p>

## Key Insights

### Python Remains Dominant

Python consistently appears in over 60% of Data Science job postings throughout the year.

Its dominance comes from its versatility across:

* Machine Learning
* Artificial Intelligence
* Data Analysis
* Automation

### SQL Shows Remarkable Stability

SQL remains one of the most consistently requested skills throughout the year, highlighting the importance of database management and structured data.

### R Maintains Relevance

Despite Python's dominance, R continues to appear in approximately one-third of Data Science postings, particularly within research and statistical environments.

### Real-World Application

The data suggests that mastering core technologies such as Python and SQL provides a significantly better return on investment than constantly chasing emerging tools and frameworks.

---

# 💰 Salary Analysis

Demand is only one side of the equation. Understanding compensation helps identify which career paths offer the strongest financial opportunities.

<p align="center">
  <img src="project/images/salary_distribution.png" width="95%">
</p>

<p align="center">
  <em>Figure 4. Salary distribution across major data careers.</em>
</p>

## Key Insights

### Senior Data Scientists Earn the Highest Salaries

Senior Data Scientists show the highest median salaries and the greatest earning potential.

### Data Engineers Are Extremely Competitive

Data Engineers earn salaries comparable to Data Scientists, emphasizing the growing value of cloud and infrastructure expertise.

### Data Analysts Have Lower Salary Ceilings

Although Data Analysts remain essential to organizations, compensation tends to be lower than more technical and specialized roles.

### Real-World Application

Professionals looking to maximize long-term salary growth should consider developing expertise in:

* Machine Learning
* Data Engineering
* Cloud Technologies
* Advanced Analytics

---

# 🚀 Highest Paying vs Most Demanded Skills

One of the most interesting findings from the project was that the most demanded skills are not necessarily the highest paying.

<p align="center">
  <img src="project/images/top_skills_analysis.png" width="95%">
</p>

<p align="center">
  <em>Figure 5. Comparison of the highest-paying and most demanded Data Science skills.</em>
</p>

## Most Demanded Skills

* Python
* SQL
* R
* Tableau
* SAS

## Highest Paying Skills

* Asana
* Airtable
* Watson
* Ruby on Rails
* Hugging Face

## What This Means

There is often a trade-off between:

* Job availability
* Salary premium

Mainstream technologies create more opportunities.

Specialized technologies create fewer opportunities but often offer significantly higher compensation.

### Career Strategy

#### Maximize Employability

Focus on:

* Python
* SQL
* Tableau
* R

#### Maximize Compensation

Specialize in:

* Hugging Face
* Watson
* Ruby on Rails

The strongest professionals combine both approaches.

---

# 🎯 Optimal Skills Analysis

The final analysis combines demand and salary data to identify the technologies offering the best overall return on investment.

<p align="center">
  <img src="project/images/optimal_skills.png" width="95%">
</p>

<p align="center">
  <em>Figure 6. Skills that balance both demand and compensation.</em>
</p>

## Key Insights

### Python Is the Clear Winner

Python combines:

* High demand
* Strong salaries
* Broad applicability

No other technology offers a better overall balance.

### SQL Remains Essential

SQL appears in more than half of job postings while maintaining strong compensation.

### Machine Learning Skills Command Premium Salaries

Technologies such as:

* TensorFlow
* PyTorch

appear less frequently but offer some of the highest salaries.

### Cloud Skills Continue to Grow

AWS and Azure provide strong salary potential while remaining highly relevant across industries.

## Recommended Learning Roadmap

### Phase 1: Foundation

* SQL
* Python

### Phase 2: Analytics

* Tableau
* Power BI
* R

### Phase 3: Specialization

* TensorFlow
* PyTorch
* AWS
* Azure
* Spark

This progression provides the strongest balance between employability and long-term earning potential.

---

# 🔑 Key Takeaways

After analyzing thousands of job postings, five clear patterns emerged:

### 1. SQL Is Non-Negotiable

SQL appears across every major data profession and remains one of the safest skills to invest in.

### 2. Python Dominates Data Science

Python consistently appears as the most requested skill and offers one of the strongest salary-to-demand ratios.

### 3. Data Engineering Is Underrated

Data Engineers earn salaries comparable to Data Scientists while benefiting from growing demand for cloud expertise.

### 4. Niche Skills Command Premium Salaries

Technologies such as Hugging Face, Watson, and Airtable appear less frequently but offer significantly higher compensation.

### 5. Fundamentals Outperform Trends

The data suggests that mastering Python and SQL provides a stronger long-term return than constantly chasing new frameworks.

---

# 📖 What I Learned

This project strengthened my skills in:

### Data Analysis

* Exploratory Data Analysis (EDA)
* Data Cleaning
* Data Transformation
* Statistical Analysis

### Python

* Pandas
* GroupBy Operations
* Pivot Tables
* Data Aggregation
* Explode Functions

### Data Visualization

* Bar Charts
* Line Charts
* Box Plots
* Scatter Plots
* Multi-Panel Dashboards

### Data Storytelling

The biggest lesson from this project was learning how to transform data into actionable insights.

Creating visualizations is only part of the process.

The real value comes from explaining what the data means and using it to support better decisions.

---

# 🚧 Future Improvements

Potential future enhancements include:

* Interactive dashboards using Plotly
* Salary prediction models
* Geographic salary analysis
* Remote vs On-site role comparisons
* Industry-specific skill analysis
* Forecasting future skill demand using Machine Learning

---

# 🙏 Acknowledgements

This project was inspired by and built using datasets provided through Luke Barousse's Python Data Analytics course.

The analysis, visualizations, insights, and recommendations presented here were independently developed as part of my data analytics learning journey.

---

<div align="center">

### 👨‍💻 Duncan D'Souza

Aspiring Data Analyst • Data Science Enthusiast • Python Developer

</div>
