# 📊 Job Market Intelligence Dashboard

![Python](https://img.shields.io/badge/Python-3.12+-blue.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-red.svg)
![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Visualization-purple.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)

An end-to-end Data Science project that analyzes technology job postings using Natural Language Processing (NLP), salary analytics, clustering, and machine learning.

The project extracts insights from real-world job postings to identify in-demand skills, hiring trends, salary patterns, and job market segments.

---

## 🎯 Project Objectives

* Analyze current technology job market trends
* Identify the most in-demand technical skills
* Explore salary distributions and compensation factors
* Discover hidden job categories using clustering
* Predict salaries using machine learning
* Build interactive dashboards for business insights

---

## 📂 Project Structure

```text
job-market-intelligence-dashboard/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   ├── 03_skill_extraction.ipynb
│   ├── 04_salary_analysis.ipynb
│   ├── 05_job_clustering.ipynb
│   ├── 06_salary_prediction.ipynb
│   └── 07_dashboard_visualization.ipynb
│
├── outputs/
│   ├── figures/
│   ├── models/
│   └── reports/
│
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 📊 Dataset

Dataset used:

**Data Science Job Postings with Salaries (2025)**

### Dataset Features

* Job Title
* Company
* Location
* Industry
* Seniority Level
* Salary
* Skills
* Revenue
* Company Size
* Ownership Type

### Dataset Size

* 944 Job Postings
* 13 Features

---

## 🛠 Technologies Used

### Data Processing

* Python
* Pandas
* NumPy

### Visualization

* Matplotlib
* Plotly

### Machine Learning

* Scikit-Learn
* K-Means Clustering
* Random Forest Regression
* TF-IDF Vectorization

### Development Environment

* VS Code
* Jupyter Notebook
* Git
* GitHub

---

## 📈 Project Workflow

### 1. Data Cleaning

* Removed duplicates
* Handled missing values
* Converted salary ranges into numeric values
* Standardized date formats

### 2. Exploratory Data Analysis

* Top hiring roles
* Hiring locations
* Seniority-level distribution
* Salary distribution analysis

### 3. Skill Extraction

* Parsed skill lists
* Computed skill frequencies
* Identified top-demand technologies

### 4. Salary Analytics

* Average salary by skill
* Average salary by seniority
* Compensation trend analysis

### 5. Job Clustering

Used:

* TF-IDF Vectorization
* K-Means Clustering

Generated meaningful job clusters such as:

* Data Science
* Data Engineering
* Machine Learning
* Analytics
* Cloud & MLOps

### 6. Salary Prediction

Model:

* Random Forest Regressor

Features:

* Job Title
* Industry
* Location
* Seniority Level

Evaluation Metrics:

* MAE
* R² Score

### 7. Interactive Dashboard

Built interactive visualizations using Plotly:

* Salary Distribution
* Skill Popularity
* Hiring Locations
* Seniority Analysis

---

## 📷 Generated Visualizations

The project automatically saves figures to:

```text
outputs/figures/
```

Examples:

```text
top_job_titles.png
salary_distribution.png
top_skills.png
top_paying_skills.png
salary_by_seniority.png
seniority_distribution.png
job_clusters.png
job_clusters_pca.png
feature_importance.png
actual_vs_predicted.png
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/Subiswas36218/job-market-intelligence-dashboard.git

cd job-market-intelligence-dashboard
```

Create a virtual environment:

```bash
python -m venv venv
```

Activate:

### macOS/Linux

```bash
source venv/bin/activate
```

### Windows

```bash
venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter:

```bash
jupyter notebook
```

---

## 📋 Results

Key findings include:

* Python remains the most requested skill.
* SQL and cloud platforms are highly demanded.
* Senior-level positions command significantly higher salaries.
* Machine Learning and Data Engineering roles offer the highest compensation.
* Job postings naturally group into meaningful technical domains.

---

## 🔮 Future Improvements

* Streamlit Web Dashboard
* BERT-Based Skill Embeddings
* Real-Time Job Data Collection
* SQL Database Integration
* Cloud Deployment
* Automated ETL Pipeline
* Salary Forecasting by Country

---

## 👨‍💻 Author

**Subhankar Biswas**

M.Sc. Data Engineering
Constructor University, Bremen, Germany

GitHub: https://github.com/Subiswas36218

LinkedIn: https://www.linkedin.com/in/subhankar-biswas-086830169/

---

## 📄 License

This project is licensed under the MIT License.

See the LICENSE file for details.
