# Impact of AI Adoption on European Employment (2023–2024)

**Bachelor’s Thesis — Economics, UAB** • **Author:** Eduardo Fernández Dionicio  
**Distinction:** Highest Honors (top 5% of cohort)

This project studies how **AI adoption** relates to shifts in the **structure of employment** across Europe (2023–2024), disaggregated by **sectors (NACE Rev.2)** and **occupations (ISCO-08)**. Using **Eurostat** data, I build panel datasets and estimate **fixed-effects** models to assess changes in **relative employment shares**.

---

## Highlights
- **Data wrangling:** multi-table Eurostat merges, panel shaping, large files.
- **Modeling:** fixed effects (country, year), **clustered SEs**, sector/occupation interactions.
- **Visualization:** clear sector/occupation comparisons with 95% CIs.
- **Reproducibility:** open code, dependencies pinned, documented pipeline.
- **Stack:** Python (pandas, statsmodels, linearmodels, matplotlib, seaborn), **mdb-tools**.

---

## Data & Methods (brief)
- **AI Adoption (`IA_Adoption`)**: % of firms using any AI tech (sector × country × year).
- **Employment shares**: `Share_Sector` (NACE) and `Share_Occupation` (ISCO-08).
- **Controls**: real GDP per capita (PPP), tertiary education rate, unemployment rate.
- **Models**: OLS with **country & year fixed effects**; robust **clustered** SEs.
