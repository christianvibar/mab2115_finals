# Final Project for MAB2115 (Computing for Analytics)

-----
# 📜 Analytics Story
### *An Investigation Into Financial Inclusion in the Phillipines: Patterns, Gaps, and Opportunities*
---

## 📌 Overview  
The Philippines is experiencing a dramatic transformation in how its citizens manage money. This analysis investigates three fundamental dimensions of Filipino financial behavior—**spending, saving, and borrowing**—to understand how Filipinos interact with both traditional and digital financial systems.

Drawing on a decade of data (2014-2024) from the **World Bank Global Findex Database**, we examine trends in digital payment adoption, the shift from traditional banks to mobile wallets, and the persistent reliance on informal credit networks across the ASEAN-6 region (Philippines, Indonesia, Malaysia, Singapore, Thailand, and Vietnam). By analyzing demographic patterns across income levels, educational attainment, and generational cohorts, this investigation reveals critical gaps in financial inclusion and offers insights into the structural barriers that prevent full digital adoption.

Finally, this report provides evidence-based findings for policymakers, fintech companies, and financial institutions seeking to understand the complexities of Filipino financial behavior and identifies pathways toward more inclusive and effective digital financial services.

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

## 👩‍💻 Researchers

- **Eleanor Geniston**
- **Angelene Lacar**
- **Jennifer Lacaza**
- **Jonas Macasero**
- **Christian Vibar**


Master in Applied Business Analytics (MABA) <br>
University of Asia and the Pacific 
