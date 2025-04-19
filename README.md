# 📊 Data Analytics Job Market in India – Exploratory Data Analysis

This project is an end-to-end Exploratory Data Analysis (EDA) of the **Data Analytics job market in India**, where I analyze job trends, salary ranges, and required skills. As an **aspiring data analyst**, I took on this project both to **strengthen my technical skills** and to **understand the market I’m preparing for**.

## 🎯 Project Goals

- Identify **high-demand skills** in the Indian data job market
- Analyze **salary patterns** across roles, locations, and skills
- Determine the **most valuable skill combinations**
- Showcase **real-world data analysis skills** using Python and Jupyter Notebooks
- 
## 🛠️ Tools & Libraries Used

For my deep dive into the data analyst job market, I harnessed the power of several key tools:

**Python:** The backbone of my analysis, allowing me to analyze the data and find critical insights.I also used the following Python libraries:

  -**Pandas Library:** This was used to analyze the data.
  
  -**Matplotlib Library:** I visualized the data.
  
  -**Seaborn Library:** Helped me create more advanced visuals.

**Jupyter Notebooks:** The tool I used to run my Python scripts which let me easily include my notes and analysis.

**GitHub: Essential** for version control and sharing my Python code and analysis, ensuring collaboration and project tracking.

## 📁 Project Structure

| Notebook | Description |

|----------|-------------|

| `EDA_Intro.ipynb` | Dataset overview and structure of job data |

| `Skill_Demand.ipynb` | Most in-demand tools and technologies |

| `3_Skill_Trend.ipynb` | How demand for certain skills has changed over time |

| `4_Salary_Analysis.ipynb` | Salary distributions by skill, city, and role |

| `5_Optimal_Skills.ipynb` | Insights into top-paying skill combinations | 

## 🔍 Key Insights 
Each Jupyter notebook for this project aimed at investigating specific aspects of the data job market.
### ⚙️ Top In-Demand Skills:

To find the most in-demand skills for the top 3 most popular data roles. I filtered out those positions by which ones were the most popular, and got the top 5 skills for these top 3 roles. 

![Results](images/Images/6_%25%20Skill%20Counts.png)

- **SQL** is the core skill for Data Analysts. **Excel** and BI tools like **Tableau** & **Power BI** are still heavily used.
- **SQL** and **Python** are essential for data engineers. Meanwhile, Cloud and big data tools like **Spark**, **AWS**, and **Azure** show a strong presence.
- Data Scientists are expected to code (**Python**, **R**), query databases(**SQL**), and also work on cloud (**AWS**) or visualization platforms (**Tableau**).

### 📈 Skill Trends:

To find how skills are trending in 2023 for Data Analysts, I filtered data analyst positions and grouped the skills by the month of the job postings. This got me the top 5 skills of data analysts by month, showing how popular skills were throughout 2023.

![Results](images/Images/8_%25%20Top%20Skills.png)

- SQL is a non-negotiable skill, appearing in over 60% of postings.
- Python (~44%) consistently ranks slightly higher than Excel (~39%) in job postings yearly, indicating that employers are increasingly preferring candidates who can automate and scale analyses.
- Power BI shows faster market growth (+160% YoY), while Tableau maintains steady demand (+75%).


### 💰 Salary Distribution by Role (USD):
To identify the highest-paying roles and skills, I only looked at jobs in India and their median salary. But first, I looked at the salary distributions of common data jobs like Data Scientist, Data Engineer, and Data Analyst, to get an idea of which jobs are paid the most.

![Results](images/Images/9_Salary%20Distribution.png)

- Data Analyst is a solid entry point, but transitioning can yield 60–80% higher pay.
- Machine Learning Engineers** command the highest median salary.
  
### 💼 Highest Paid Skills:

I narrowed analysis to data analyst roles. I used two bar charts to showcase the highest-paid skills and the most in-demand skills.
![Results](images/Images/10_Highest%20Paid%20Skills.png)

- PostgreSQL, PySpark, and GitLab are the top 3 highest-paying skills for Data Analysts.
- Most top-paying tools are back-end or data engineering-focused, highlighting the importance of cross-functional data skills.
- Power BI and Spark dominate both salary and demand — a great skill combo for BI + big data.
- Python and SQL remain the core foundational tools, with high job market saturation.
- Cloud platforms (Azure, AWS) offer moderate pay, likely more valuable when combined with other skills.

### 🔹 Most optimal Skills:

To identify the most optimal skills to learn ( the ones that are the highest paid and highest in demand) I calculated the percent of skill demand and the median salary of these skills. To easily identify which are the most optimal skills to learn.

![Results](images/Images/11_Optimal%20Skills.png)

**High Demand & Good Salary:**
- **Python** (around 42% of jobs, ~$96K median salary): A versatile programming language crucial for data manipulation, analysis, and machine learning.
- **Excel** (around 41% of jobs, ~$99K median salary): Still a fundamental tool for data handling, cleaning, and basic analysis.
- **Power BI** (around 25% of jobs, ~$118K median salary): A leading data visualization tool that's highly sought after.
- **Tableau** (around 22% of jobs, ~$108K median salary): Another popular data visualization platform.
- **SQL** (around 49% of jobs, ~$96K median salary): Absolutely essential for database querying and management, appearing in the highest percentage of jobs.

**High Salary & Lower Demand:**
- MongoDB (around 6% of jobs, ~$166K median salary): Expertise in NoSQL databases like MongoDB commands the highest median salary, suggesting specialized roles.
- Looker (around 12% of jobs, ~$112K median salary): A business intelligence and data visualization platform with a good salary.
- Spark (around 16% of jobs, ~$111K median salary): Valuable for big data processing.
- Flow (around 8% of jobs, ~$103K median salary): Another tool in the data engineering or workflow management space.

## 👩‍💻 What I have Learned:
Throughout this project, I deepened my understanding of the data analyst job market and enhanced my technical skills in Python, especially in data manipulation and visualization. Here are a few specific things I learned:
 - Advanced Python Usage
 - Data Cleaning
 - Strategic Skill Analysis

## 💡 Conclusion:
This project gave me a clear picture of what the data analyst job market looks like. I got to learn which skills are most important and what trends are shaping the field right now. The insights I found are very helpful, not just for me, but for anyone who wants to grow in data analytics. Since the job market keeps changing, it's important to keep learning and staying updated. This project is just the beginning, and it shows how important it is to keep exploring and improving in the data world.


  


