# Dhruv Bhatt

BSc (Honors) Computer Science @ University of Alberta · GPA 3.7 · Expected May 2027

I build things end-to-end — cloud infrastructure, data pipelines, backend APIs, and the ML models
and tooling around them. My work spans cloud/DevOps (serverless architectures, IaC), data engineering
(ETL, SQL, reporting automation), applied ML (predictive modelling, computer vision, LLM integration),
and systems programming (networking, concurrent servers). I care about shipping things that are
correct, documented, and maintainable — not just things that run.

---

## What I've Built
 
- **DataLens** — Serverless data lakehouse on AWS. Ingests live earthquake data from USGS every
  6 hours (EventBridge + Lambda), cleans it and lands it as partitioned Parquet in S3, catalogs it
  with Glue, and serves it two ways: a React/Recharts dashboard over fixed Athena queries, or a
  plain-English question box where an LLM (Gemini) writes and safety-checks its own SQL before
  running it. Fully defined in Terraform, CI via GitHub Actions, CloudWatch alarms + dashboard.
  Live and running on a schedule, not a one-off script.
- **SQL Server ETL Pipeline** — Python ETL + T-SQL stored procedures + Power BI dashboard + automated
  PowerPoint reporting. Full stack from raw CSV to executive summary, with audit logging throughout.
- **QueueWise** — Full-stack waitlist & appointment management platform. FastAPI + React/Vite/Tailwind,
  real-time queue dashboard over WebSockets, multi-tenant orgs, JWT auth, RBAC, auto-generated OpenAPI
  docs.
- **F1 Race Pace Predictor** — Modular data pipeline over FastF1 telemetry. Regression + classification
  with GroupKFold CV (MAE ~0.32s, F1 ~0.76). Streamlit dashboard for interactive exploration.

---

## Currently Working On

- Cloud infrastructure & IaC (AWS, Terraform) — DataLens was the first end-to-end build here
- Sharpening algorithms & data structures fundamentals (NeetCode roadmap)
- Computer Networks & Distributed Systems
- Machine Learning

---

## Stack

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=white)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Streamlit](https://img.shields.io/badge/Streamlit-%23FE4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/dhruv-b-1aa777274)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:dhruvchi@ualberta.ca)
