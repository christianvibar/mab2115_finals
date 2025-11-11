# mab2115_finals
Final project for MAB2115 (Computing for Analytics)

**For files**

Use global_findex_for_analysis.csv for analysis. To access the file, use `pd.read_csv('../data/processed/global_findex_for_analysis.csv')`

-----
# 🌍 Global Findex Exploratory Data Analysis  
### *Understanding Borrowing, Saving, and Digital Financial Behavior in the ASEAN-6 and a deep dive into financial behavior in the Philippines*


---

## 📘 Overview  
This repository contains an **exploratory data analysis (EDA)** of the **Global Findex Database**, a flagship World Bank survey measuring how adults around the world save, borrow, make payments, and manage risk.  

The project focuses on uncovering patterns and insights on **financial inclusion** through three behavioral dimensions:

1. 💰 **Borrowing** – How do people access credit, and what are the formal vs. informal borrowing trends?  
2. 🪙 **Saving** – How do individuals save, and for what purposes (e.g. old age)?  
3. 💳 **Spending** – How are digital financial services (DFS) like mobile money and online payments transforming financial participation?  


---

## 🗂️ Dataset  
**Source:** [World Bank Global Findex Database (2014-2024)](https://microdata.worldbank.org/index.php/catalog/global-findex)  

**Key Features:**
- 🌏 Over **120,000 respondents** across 120+ economies  
- 💬 Indicators covering **account ownership, savings, borrowing, and digital finance use**  
- 🎯 Designed to support research in **financial inclusion and development economics**

| Category | Key Variables | Description |
|-----------|----------------|-------------|
| **Borrowing** | `fin22a`, `fin24a`, `fin28b`, `fin28c` | Source and purpose of loans (formal, informal, family/friends) |
| **Saving** | `fin17a`, `fin17f`, `fin18a` | Savings behavior and purpose (old age, emergencies, etc.) |
| **Digital Channels** | `fin2`, `fin5a`, `fin5b` | Use of digital payments, online purchases, and mobile money |

---

## 🧰 Tools and Libraries  
Developed with **Python 3.11** using the following libraries:

| Category | Libraries |
|-----------|------------|
| **Data Wrangling** | `pandas`, `numpy` |
| **Visualization** | `matplotlib`, `seaborn` |
| **Documentation & Reporting** | `jupyter`, `markdown` |

---

## 🔍 Key Analyses  

- **Saving for Old Age by Age Group**  
  → How do savings motivations change across age demographics?  

- **Borrowing Formality by Education Level**  
  → Are more educated individuals more likely to borrow from formal institutions?  

- **Use of Digital Payments by Income Quintile**  
  → Are higher-income individuals more likely to use digital financial channels?  

Each notebook includes:
- Data cleaning and preparation  
- Visual exploration (bar plots, histograms, heatmaps)  
- Insights and interpretations linked to financial inclusion  

---

## 👩‍💻 Authors

**Eleanor Geniston**
**Jennifer Lacaza**
**Angelene Lacar**
**Jonas Macasero**
**Christian Vibar**

Master in Applied Business Analytics (MABA)
University of Asia and the Pacific 
