# Labor Force Survey (LFS) – Econometrics I  
**Problem Set 1 | Questions 1–4**

This notebook contains the solutions to Questions 1–4 of Problem Set 1 for the *Econometrics I* course.  
The analysis is based on microdata from the Iranian **Labor Force Survey (LFS)** and focuses on labor market indicators and working conditions.

---

## File Description

- **LFS_Data_cleaning.ipynb**  
  Python notebook implementing data cleaning, aggregation, visualization, and statistical analysis for LFS data.

---

## Dataset

- Source: Statistical Center of Iran – Labor Force Survey
- Format: Microsoft Access database (`.mdb`)
- Table used: `LFS_RawData`

### Key Variables
- Gender
- Age
- Education level
- Activity status (employed, unemployed, inactive)
- Industry code (ISIC)
- Occupation code (ISCO)
- Insurance status
- Weekly working hours

---

## Questions Overview

### Question 1  
**Labor Force Participation Rate (LFPR)** and **Unemployment Rate** by:
- Gender
- Education level  

Education levels are grouped into:
- Below high school
- High school
- Bachelor
- Master
- Above master
- Unknown  

Rates are computed using standard labor market definitions.

---

### Question 2  
- Unemployment rate by age  
- Employment-to-population ratio by age  
- Sample restricted to individuals aged **15–65**  
- Results visualized using bar charts

---

### Question 3  
Employment distribution across three economic sectors:
- Agriculture
- Industry
- Services  

Sector classification is based on **ISIC codes**, and results are reported by **establishment size** using a stacked bar chart.

---

### Question 4  
- Average weekly working hours by:
  - Occupation group (based on ISCO major groups)
  - Insurance status (insured vs uninsured)
- Comparison of working hours between insured and uninsured workers using **ANOVA**
- Visualization using boxplots

---

## How to Run

1. Place the LFS Access database file in a local directory (e.g. `data/`).
2. Update the database file path in the notebook.
3. Run all cells sequentially.

---

## Dependencies

```bash
pip install pandas numpy matplotlib scipy pyodbc
