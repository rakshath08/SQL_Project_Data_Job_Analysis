
# 💼 Data Analyst Job Market Exploration — 2023 Edition

## 📊 Introduction  
Dive into the data job market! Focusing on **data analyst roles**, this project explores:  
- 💰 Top-paying jobs  
- 🔥 In-demand skills  
- 📈 Where high demand meets high salary in data analytics  

## 🧠 Background  
This project was inspired by a desire to better understand the **data analyst job market**. By identifying the **top-paying** and **most in-demand skills**, it helps streamline career planning for aspiring analysts and working professionals.

---

## 🎯 Key Questions

1. What are the **top-paying** data analyst jobs?
2. What **skills** are required for these top-paying jobs?
3. What **skills are most in demand** for data analysts?
4. Which skills are associated with **higher salaries**?
5. What are the **most optimal skills to learn**?

---

## 🛠️ Tools Used

| Tool          | Purpose                                           |
|---------------|---------------------------------------------------|
| **SQL**       | To write complex queries for data extraction      |
| **PostgreSQL**| Database system to handle job data                |
| **VS Code**   | IDE for writing and executing SQL queries         |
| **Git & GitHub** | Version control and project collaboration    |

---

## 🔎 The Analysis

### 1️⃣ Top-Paying Data Analyst Jobs

```sql
-- SQL query to get top 10 highest-paying remote jobs
SELECT ... 
```

📌 **Insights:**
- Salary ranges from **$184K to $650K** for top roles.
- Employers include **SmartAsset, Meta, AT&T**, etc.
- Titles vary: from **Data Analyst** to **Director of Analytics**.

---

### 2️⃣ Skills Required for Top-Paying Jobs

```sql
-- SQL query joining job postings with skills
WITH top_paying_jobs AS (...) 
SELECT ...
```

📌 **Top Skills:**
- **SQL** (used in 8 of top 10 jobs)  
- **Python**, **Tableau**, **R**, **Snowflake**, **Excel** also appear

---

### 3️⃣ Most In-Demand Skills

```sql
-- SQL query to count skill demand
SELECT skills, COUNT(...) ...
```

📌 **Top 5 Most Demanded Skills:**

| Skill     | Demand Count |
|-----------|---------------|
| SQL       | 7,291         |
| Excel     | 4,611         |
| Python    | 4,330         |
| Tableau   | 3,745         |
| Power BI  | 2,609         |

---

### 4️⃣ Skills with Highest Salaries

```sql
-- SQL query to find average salary by skill
SELECT skills, AVG(salary_year_avg) ...
```

📌 **Top Paying Skills:**

| Skill         | Avg Salary ($) |
|---------------|----------------|
| PySpark       | 208,172        |
| Couchbase     | 160,515        |
| DataRobot     | 155,486        |
| GitLab        | 154,500        |
| Jupyter       | 152,777        |

---

### 5️⃣ Most Optimal Skills to Learn (High Demand + High Salary)

```sql
-- SQL combining demand + salary, filtered by minimum demand
SELECT skills, COUNT(...), AVG(...) ...
```

📌 **Most Strategic Skills:**

| Skill     | Demand | Avg Salary ($) |
|-----------|--------|----------------|
| Go        | 27     | 115,320        |
| Snowflake | 37     | 112,948        |
| Azure     | 34     | 111,225        |
| AWS       | 32     | 108,317        |
| Java      | 17     | 106,906        |

---

## 🧠 What I Learned

- **Advanced SQL:** CTEs, joins, aggregations, filtering, and subqueries
- **Data Analysis Thinking:** Translating business questions into SQL logic
- **Insight Communication:** Turning raw data into actionable insights

---

## 🧾 Conclusions

### 📌 Key Takeaways:

1. **Remote analyst roles** can offer salaries up to **$650K**.
2. **SQL** is king—both **high-paying** and **in-demand**.
3. **Python**, **Tableau**, and **Excel** are must-have foundational tools.
4. Specialized tools (e.g., **PySpark**, **Snowflake**) can significantly boost earning potential.
5. Learn strategically: aim for tools that are **in demand AND high paying**.

---

## 🔚 Final Thoughts

This project not only boosted my SQL capabilities but gave me **real-world insight** into where the data job market is heading. If you're planning your **data analytics journey**, this guide can help you prioritize **the right tools** to learn and the **best opportunities** to chase.

---

## 📂 Folder Structure

```bash
.
├── README.md
├── assets
│   └── 1_top_paying_roles.png
├── project_sql
│   ├── top_paying_jobs.csv
│   ├── skills_top_jobs.csv
│   ├── demand_skills.csv
│   ├── salary_skills.csv
│   └── optimal_skills.csv
```
