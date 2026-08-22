# Level 3 Second Term Project: GitHub Projects Data Analytics Pipeline

**Student Name:** Mazen Mohamed Mohamed El-Shazly  
**Student ID:** DECI4-S-416558  
**Course:** Data Science Level 3 - Term 2  

---

## 📌 Project Overview
This project completes an end-to-end data analytics workflow on Machine Learning repositories from GitHub:
1. **Data Collection & Preparation:** Collected repository data from the GitHub API using Python and Pandas, cleaned missing/duplicate records, and saved the dataset to CSV.
2. **Database Storage & SQL Analysis:** Loaded the prepared dataset into SQLite, executed analytical SQL queries (filtering, searching, logical operators, ranking, and grouping), and generated Matplotlib visualizations.
3. **Version Control & Ethics:** Managed the project lifecycle using Git and GitHub, providing evidence screenshots and reflections on responsible public data usage.

---

## 📁 Repository Structure
* `LV3_SecondTermProject_Mazen_DECI4-S-416558.ipynb`: Main Google Colab project notebook with full code, outputs, and visualizations.
* `github_projects.csv`: Cleaned dataset containing the top 100 machine learning repositories.
* `github_projects.db`: SQLite database storing the `Repositories` table.
* `requirements.txt`: Python package dependencies.
* `screenshots/`: Git command execution and repository evidence screenshots.

---

## 🔗 Data Source
GitHub Search API:
`https://api.github.com/search/repositories?q=machine+learning&sort=stars&order=desc&per_page=100`
