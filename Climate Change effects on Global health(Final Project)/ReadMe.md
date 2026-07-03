<div align="center">

# 🌍 Climate Change Effects on Global Health

### An interactive Power BI dashboard exploring how climate anomalies drive health outcomes worldwide

<br/>

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)

</div>

<br/>

## 📌 About the Project

Rising global temperatures, shifting precipitation patterns, and worsening air quality don't just change the weather — they change health outcomes. This project analyses a **14,100-row, 30-column** global dataset to uncover how climate anomalies (temperature, AQI, PM2.5, precipitation) connect to disease trends, food security, and healthcare access across countries and income levels.

The end-to-end workflow — cleaning in **Python**, exploration in **Excel**, and visualization in **Power BI** — was built as part of a Summer Training project.

**Target audience:** Health boards · Hospitals · Elder-care services · Climate researchers

<br/>

## 🧭 Table of Contents

- [About the Project](#-about-the-project)
- [Tech Stack](#️-tech-stack)
- [Dataset](#-dataset)
- [Workflow](#-workflow)
- [Key Findings](#-key-findings)
- [Repository Structure](#-repository-structure)
- [How to View](#-how-to-view)
- [Author](#-author)

<br/>

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| <img src="https://img.shields.io/badge/-Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white" alt="Colab"/> **Google Colab (Python)** | Data cleaning & validation with **NumPy** and **Pandas** |
| <img src="https://img.shields.io/badge/-Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white" alt="Excel"/> **Microsoft Excel** | Pivot tables & exploratory visuals to understand column relationships |
| <img src="https://img.shields.io/badge/-Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" alt="Power BI"/> **Power BI** | DAX measures, data modelling, and the final interactive dashboard |
| <img src="https://img.shields.io/badge/-Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white" alt="Kaggle"/> **Kaggle** | Source of the raw dataset |

<br/>

## 🗃️ Dataset

| Attribute | Detail |
|---|---|
| **Source** | Kaggle |
| **Format** | CSV |
| **Rows** | 14,100 |
| **Columns** | 30 |
| **Timeframe** | 2015 – 2025 |

**Key columns:**

| Column | Role |
|---|---|
| `Country name` | Represents each country |
| `Year` | Timeline comparisons |
| `Healthcare access` | Access to healthcare per country |
| `Income level` | Country grouping by income |
| `Food security` | Food quality security index |
| `Temperature Anomalies` | Deviation from predicted average temperature |

<br/>

## ⚙️ Workflow

```mermaid
flowchart LR
    A[🗂️ Raw Dataset — Kaggle] --> B[🐍 Clean & Analyse — Python / Colab]
    B --> C[📊 Pivot Tables & Visuals — Excel]
    C --> D[⚡ DAX Measures & Modelling — Power BI]
    D --> E[📈 Interactive Dashboard]
```

1. **Check & clean** the dataset using Python (NumPy, Pandas) in Google Colab
2. **Explore relationships** between columns using Excel pivot tables and visuals
3. **Model the data & write DAX measures** in Power BI
4. **Design and publish** the final interactive dashboard

<br/>

## 🔎 Key Findings

- 🌡️ Global average temperature rose **steadily from 2015 to 2025**
- 🔥 Heat-related admissions **spiked sharply in 2025**
- 🏥 Healthcare access is closely tied to income level — **~85 avg. (High income)** vs **~45 avg. (Lower-middle income)**
- 🫁 **Respiratory diseases** were the most common climate-linked health issue
- 💨 Highest AQI recorded globally: **302**
- 🌱 **Spring** saw the sharpest rise in climate-linked disease cases
- 🦟 Vector-borne disease risk climbs sharply once precipitation crosses **110 mm**
- ❤️ Cardio mortality spiked alongside the **2023 PM2.5 peak**
- 🇧🇷 Brazil: highest cardio mortality (**31.22%**) · 🇹🇭 Thailand: lowest (**30.37%**)
- 🇬🇧 UK: highest food security index (**98.9**) · 🇵🇭 Philippines: lowest (**85.9**)

<br/>

## 📁 Repository Structure

```
📦 climate-change-global-health
├── 📄 README.md
├── 📊 dashboard.pbix
├── 🐍 data_cleaning.ipynb
├── 📈 dataset.csv
├── 📑 Project_Report.docx
└── 🖥️ Final_Project_Presentation.pptx
```

<br/>

## ▶️ How to View

1. Clone this repository
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   ```
2. Open **`dashboard.pbix`** in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) to explore the live dashboard
3. Open **`data_cleaning.ipynb`** in [Google Colab](https://colab.research.google.com/) to review the data cleaning steps

<br/>

## 👤 Author

**Arshveer Singh**
B.Tech Blockchain · Roll No. 2405043242
Guided by Dr. Ashima & Ms. Mandeep Kaur

<br/>

<div align="center">
<sub>Built with 🌍 data, 📊 dashboards, and a lot of ☕ during Summer Training</sub>
</div>
