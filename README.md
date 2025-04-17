# 💼 AD688 Final Project – Employability & Gender Disparities  
**Team 8 | Boston University | Spring 2025**

[🌐 View Project Website](https://chialingsung.github.io/ad688-employability-sp25A1-group8/)  
[📂 GitHub Repository](https://github.com/ChialingSung/ad688-employability-sp25A1-group8)

---

## 📌 Project Overview

This project explores gender disparities in the U.S. job market using real-world job posting data. Through data cleaning, exploratory data analysis, machine learning models, and skill gap assessment, we examine how gender, industry, location, and political affiliation interact in shaping employment outcomes.


---

## 🔍 Key Modules & Files

| 📁 Module                     | 📄 File                          | 📝 Description & Improvements |
|------------------------------|----------------------------------|-------------------------------|
| **Introduction**             | `introduction.qmd`              | Introduces the motivation, context, and significance of studying gender disparities in the labor market. Highlights the role of industry structure and policy environments. |
| **Data Cleaning & Exploration** | `data_analysis.ipynb`         | Cleaned missing values, removed irrelevant or duplicate columns, standardized job categories using NAICS and SOC codes. Includes summaries of job descriptions and salary columns. |
| **Exploratory Data Analysis**  | `eda.ipynb`                   | Enhanced visualizations (bar charts, boxplots, pie/donut charts) to analyze job posting volumes, salary distributions, and remote work types across industries. Added business implications for career planning and workforce strategy. |
| **Skill Gap Analysis**        | `skill_gap_analysis.ipynb`     | Compared team members' self-assessed technical skills against market demands. Used heatmaps to identify gaps and proposed personalized upskilling strategies with recommended resources. |
| **Machine Learning Methods**  | `ml_methods.ipynb`             | Applied KMeans clustering to group occupations by gender dominance. Used classification models (e.g., decision tree, random forest) to predict gender representation based on job attributes and geography. |
| **NLP Methods** *(optional)*  | `nlp_methods.ipynb` *(if included)* | Conducted topic modeling on job descriptions, extracted skill keywords, and examined text-based differences between male- and female-dominated roles. |

---

## 📁 Project Directory Overview

| Folder / File           | Description |
|-------------------------|-------------|
| `data/`                 | Stores input datasets (e.g., `job_postings.csv`, `employment_gender.xlsx`) – *excluded from GitHub via `.gitignore`* |
| `reference/`            | Contains project illustrations (`home_1.png`, `intro_1.png`), citation file `references.bib`, and CSL styling |
| `_output/`              | Stores exported images and visualizations from EDA and ML methods |
| `_site/`                | Auto-generated website output directory for GitHub Pages |
| `.gitignore`            | Git tracking rules to exclude large or private files (e.g., datasets, environment folders) |
| `_quarto.yml`           | Quarto configuration file for theming, navigation, and build control |
| `README.md`             | Project overview and navigation guide (this file) |

---


## 👥 Team Members

| Name            | Role                |
|-----------------|---------------------|
| Jianhao Hong    | NLP Method |
| Xinran Li       | Skill Gap         |
| Chialing Sung   | eda |
| Zimo Zeng       | ML Method |

---

## 🚀 How to View or Clone This Project

- 🔗 [Open the Live Website](https://chialingsung.github.io/ad688-employability-sp25A1-group8/)
- 📥 Clone to VS Code: vscode://vscode.git/clone?url=https://github.com/ChialingSung/ad688-employability-sp25A1-group8.git

---

## 📚 References

- U.S. Bureau of Labor Statistics (2023)  
> Full citations available in `reference/references.bib`


---

> _This project is part of the AD688 course at Boston University, Spring 2025._
