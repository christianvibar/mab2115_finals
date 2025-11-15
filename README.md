# Final Project for MAB2115 (Computing for Analytics)

-----
# 🌍 Global Findex Exploratory Data Analysis  
### *An Investigation Into Financial Inclusion in the Phillipines: Patterns, Gaps, and Opportunities*
---

## 📘 Overview  
This repository contains an **exploratory data analysis (EDA)** of the **Global Findex Database**, a flagship World Bank survey measuring how adults around the world save, borrow, make payments, and manage risk.  

The project focuses on uncovering patterns and insights on **financial inclusion** through four behavioral dimensions:

1. **Financial Account Ownership**
2. 💰 **Borrowing** – How do people access credit, and what are the formal vs. informal borrowing trends?  
3. 🪙 **Saving** – How do individuals save, and for what purposes (e.g. old age)?  
4. 💳 **Spending** – How are digital financial services (DFS) like mobile money and online payments transforming financial participation?  
---

## 📝 Analysis Notebook
[Please click here](https://github.com/christianvibar/mab2115_finals/blob/e4d17d9b8ad75c4c4c62889dfb211ce1f42447e9/notebooks/final/mab2115_finals_group_3.ipynb)

## 🗂️ Dataset  
**Primary Dataset:** World Bank Global Findex Database (2025 Release): https://www.worldbank.org/en/publication/globalfindex/download-data
* [Raw file](https://github.com/christianvibar/mab2115_finals/blob/e4d17d9b8ad75c4c4c62889dfb211ce1f42447e9/data/raw/GlobalFindexDatabase2025.csv)
  
**Secondary Dataset:** Global Findex Microdata (2025 Release): https://microdata.worldbank.org/index.php/catalog/7860/study-description
* [Raw file](https://github.com/christianvibar/mab2115_finals/blob/e4d17d9b8ad75c4c4c62889dfb211ce1f42447e9/data/raw/findex_microdata_2025_labelled.csv)

**Key Features:**
- 🌏 Over **120,000 respondents** across 120+ economies  
- 💬 Indicators covering **account ownership, savings, borrowing, and digital finance use**  
- 🎯 Designed to support research in **financial inclusion and development economics**

| Category | Key Variables | Description |
|-----------|----------------|-------------|
| **Digital Channels** | `fiaccount_t_d`, `mobileaccount_t_d` | |
| **Borrowing** | `fin22a`, `fin22a_1`, `fin22b`, `fin22c` | Source and purpose of loans (formal, informal, family/friends) |
| **Saving** | `fin17a`, `fin17b`, `fin17c`, `fin17f` | Savings behavior and purpose (old age, emergencies, etc.) |
| **Spending** | `g20_made`, `fin22g`, `fin26b`, 'anydigpayment` | Use of digital payments, online purchases, and mobile money |

---

## 🧰 Tools and Libraries  
Developed using the following libraries:

| Category | Libraries |
|-----------|------------|
| **Data Wrangling** | `pandas`, `numpy` |
| **Visualization** | `matplotlib`, `seaborn` |
| **Documentation & Reporting** | `jupyter`, `markdown` |

---

## 🔍 Key Insights  


- **Spending**: Filipinos prefer online payments over traditional banking, marking a decisive shift toward digital-first transactions. This rapid digital payment adoption signals vast untapped potential in the fintech sector, particularly in adjacent services like digital lending and wealth management.

- **Saving**: Mobile wallet savings surged 147% while bank savings collapsed 46%, with digital adoption (+12pts) exceeding bank decline (-9pts). This suggests digital platforms are not only displacing traditional banks but also capturing previously unbanked savers, potentially from informal savings networks.

- **Borrowing**: Despite digital adoption in spending and saving, Filipinos remain heavily reliant on informal borrowing from family and friends. This shows that Filipinos embrace digital platforms for transactions and savings, yet avoid digital lending. Barriers likely include fear of debt traps, lack of credit history recognition, or unfamiliarity with digital loan terms.

Each notebook includes:
- Data cleaning and preparation  
- Visual exploration (bar plots, histograms, heatmaps)  
- Insights and interpretations linked to financial inclusion  

---

## 👩‍💻 Authors

- **Eleanor Geniston**
- **Angelene Lacar**
- **Jennifer Lacaza**
- **Jonas Macasero**
- **Christian Vibar**


Master in Applied Business Analytics (MABA) <br>
University of Asia and the Pacific 
