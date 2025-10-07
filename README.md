# Impact of AI Adoption on European Employment (2023–2024)

**Bachelor’s Thesis — Economics, UAB**

**Author:** Eduardo Fernández Dionicio  
**Grade:** Highest Honor Distinction (top 5% of cohort)

## Introduction
**Are we fully aware of the impact that Artificial Intelligence is having on the employment structure?**

The rapid adoption of AI in today’s economy has generated uncertainty about the future of the labor market.
Historically, automation has produced a heterogeneous substitution effect in employment structures, depending on the type of tasks most susceptible to being replaced by machines.
However, it has also led to the creation of new tasks, increasing the demand for labor in other areas and thus driving a structural shift in employment.

In this context, the question arises:

**Will artificial intelligence follow a similar pattern of previous technological advances?**

## 🎯 Project Objective

The objective of this research is to empirically analyze how the adoption of AI technologies by firms is affecting the employment structure in Europe. Specifically, this impact will be examined across different branches of economic activity (NACE Rev. 2 classification) and occupational groups (ISCO-08 classification) for the period 2023–2024.

To achieve this, the central hypothesis is that the adoption of AI will have a heterogeneous effect on employment depending on the predominant type of tasks. In particular, drawing on the theoretical framework of routine vs. non-routine tasks, it is expected that in sectors and occupations intensive in routine tasks, AI adoption will be associated with reductions in employment shares. Conversely, in sectors and occupations intensive in non-routine tasks, AI is likely to act more as a complement to human labor, leading to higher employment shares as AI adoption increases.

---

<img width="1026" height="1487" alt="image" src="https://github.com/user-attachments/assets/84bd8249-7a26-46f7-b577-3dfc46e20c6b" />

---

## 📊 Data Source
- Source: [Digital economy and society: Comprehensive database](https://ec.europa.eu/eurostat/web/digital-economy-and-society/database/comprehensive-database)  
- Dataset: *Statistics on enterprises*  
- Official dictionary: available in the same source  
- Download date: 27/05/2025

The comprehensive databases provide access to recent and historical data for the EU and members from the surveys on the use of ICT in households and by individuals and on ICT usage and e-commerce in enterprises, in MS-Access format. They also contain detailed statistics for many non-EU countries.

---

## 🛠️ Tools Used
- **Excel**: Dictionary, data manipulation, pivot chart.
- **Python**: ETL process, Exploratory data analysis, modeling, descriptive analysis, pandas, numpy, Statsmodels.
- **PowerPoint**: slides, academic poster.
  
---

## 📂 Repository Structure
```
data/                # Excel files: datasets
docs/                # Poster, slides, dictionaries and Thesis Documentation.
notebooks/           # Python notebooks with ETL process, mergin data, panel model, etc.
outputs/             # CSV: cleaned dataset
README.md            # Main project documentation
requirements.txt     # Python dependencies
LICENSE              # MIT license
```

---

## 🚀 How to Reproduce the Project
To clone and run the project locally:

```bash
git clone https://github.com/eduardo-fd/AI-Adoption-Employment-EU.git
cd AI-Adoption-Employment-EU

# Create virtual environment
python3 -m venv .venv
source .venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

---

## Citation
- Cite as: Fernández Dionicio, E. (2025). Impact of AI Adoption on the Structure of European Employment (2023–2024): An Empirical Analysis by Sectors and Occupations. UAB.
