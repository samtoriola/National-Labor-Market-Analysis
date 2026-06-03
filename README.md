# LMI Dashboard — Streamlit

## Setup

```bash
pip install -r requirements.txt
```

## Data files
Place both CSV files in the **same directory** as `lmi_dashboard.py`:
- `Occupation_Table_All_Occupations_in_United_States_8e5b5573e5945249.csv`
- `Industry_Table_All_Industries_in_United_States_0dd365ca70ddadd0.csv`

## Run

```bash
streamlit run lmi_dashboard.py
```

## Pages (left sidebar)

| Section | Pages |
|---|---|
| Labor Supply | Occupation Overview · Industry Overview |
| Labor Demand | Job Postings & Hires · Growth Projections |
| Compensation | Wages by Occupation · Wages by Industry |
| Demographics | Age & Gender · Race & Ethnicity |
| Sector Analysis | **Sector Bubble Chart** |

## Filters (top bar, apply to all pages)
- **SOC Major Group** — filter by occupational category
- **Entry-Level Education** — filter by credential requirement
- **Industry Sector** — filter NAICS sector
- **Min. jobs (thousands)** — hide small occupations

## Source
Lightcast Q2 2026 · 798 SOC occupations · 947 NAICS industries · U.S. national
