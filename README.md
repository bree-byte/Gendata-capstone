#  Suicide Mortality Analysis in Kenya and African Countries (2015–2021)

##  Project Overview

### Problem Statement

**The Silent Crisis: Understanding and Preventing Suicide in Kenya and Africa**

Suicide remains one of the most under-reported and misunderstood public health crises in Africa. In Kenya alone, approximately **4 people die by suicide every day**, yet there is limited comprehensive data analysis to inform prevention strategies.  

Key problems include:

- **Lack of Data-Driven Insights**: Mental health policies are often created without understanding which demographics are most vulnerable, when deaths peak, or how Kenya compares to neighboring countries.  
- **Resource Allocation Challenges**: With limited mental health budgets, governments and NGOs need to know WHERE and WHEN to deploy crisis intervention services most effectively.  
- **Stigma and Silence**: The lack of visible, evidence-based analysis perpetuates the stigma around suicide, preventing communities from addressing it openly.  
- **Gender and Age Disparities**: Young men aged 25–44 are 5 times more likely to die by suicide than women, yet intervention programs aren't targeted to this group.  

**Why This Matters:**  
Every suicide represents a preventable death. Families are devastated, communities lose productive members, and the economic cost (lost productivity, healthcare, funeral costs) is estimated at over **KES 50 million annually** in Kenya alone. Without data-driven insights, we're fighting this crisis blindfolded.

---

##  Tools and Technologies Used

This project demonstrates proficiency across the data analysis pipeline using industry-standard tools.

### 1. **Microsoft Excel** (Data Cleaning & Preliminary Analysis)
- Data import and validation  
- Initial exploratory data analysis (EDA)  
- Calculating summary statistics (mean, median, gender ratios)  
- Creating pivot tables for monthly and yearly aggregations  
- Data quality checks and handling missing values  

### 2. **SQL** (Data Querying & Advanced Analysis)
- Database design and data import  
- Complex queries to answer business questions  
- Joins between Kenya dataset and Africa comparison dataset  
- Aggregations and GROUP BY operations for temporal analysis  
- Window functions for ranking countries and identifying trends  
- Subqueries for comparative analysis  

### 3. **Tableau** (Data Visualization & Dashboard Creation)
- Interactive dashboards showing:
  - Time-series trends (2015–2021)  
  - Geographic comparisons across 7 African countries  
  - Age group vulnerability heat maps  
  - Monthly seasonal patterns  
  - Gender disparity visualizations  
- Filters for dynamic exploration by year, country, and age group  
- Story points to guide stakeholders through key insights  

**Technical Skills Demonstrated:**  
ETL (Extract, Transform, Load) processes, database management, SQL optimization, statistical trend identification, and dashboard storytelling for non-technical audiences.

---

##  Key Research Questions

### Demographics & Vulnerability
1. **Which age groups are most vulnerable to suicide in Kenya?**  
   - Hypothesis: Young adults (25–44) and older persons (55–64) are at highest risk.  
   - Impact: Target crisis hotlines and mental health services to these demographics.  

2. **What is the gender disparity in suicide deaths?**  
   - Hypothesis: Male deaths are 5x higher than female deaths.  
   - Impact: Design gender-specific intervention programs.  

3. **How do suicide rates vary by age group across African countries?**  
   - Impact: Learn from countries with better outcomes in specific demographics.  

### Temporal Patterns
4. **Are there seasonal patterns in suicide deaths?**  
   - Identify months with the highest suicide rates.  
   - Compare patterns between countries.  
   - Impact: Deploy additional resources during high-risk periods.  

5. **What are the year-over-year trends (2015–2021)?**  
   - Are suicide rates increasing or decreasing?  
   - Did COVID-19 (2020–2021) affect suicide rates?  
   - Impact: Evaluate effectiveness of prevention programs.  

### Geographic Comparisons
6. **How does Kenya’s suicide rate compare to other African countries?**  
   - Which countries have the highest or lowest rates?  
   - What can Kenya learn from countries with declining rates?  

7. **What is the suicide burden per 100,000 population across Africa?**  
   - Calculate age-standardized mortality rates.  
   - Impact: Understand the crisis scale relative to population size.  

### Economic & Social Impact
8. **How many lives were lost to suicide in Kenya (2015–2021)?**  
   - Quantify the human toll and economic loss.  

9. **Which country has the highest annual growth in suicide deaths?**  
   - Identify countries needing urgent intervention.  

10. **What percentage of deaths occur in vulnerable age groups?**  
    - Measure potential prevention success through targeted programs.  

---

##  Expected Insights & Solutions

### Key “Aha!” Moments

1. **The "Peak Danger" Insight:**  
   If specific months (e.g., January, April) show 30–40% higher deaths, crisis hotlines can increase staffing during these periods.  
   *→ Solution: Predictive resource allocation for mental health services.*  

2. **The "Young Men Crisis":**  
   If men aged 25–44 account for 40%+ of deaths, implement workplace mental health programs.  
   *→ Solution: Male-focused counseling and wellness initiatives.*  

3. **The "Hidden Trend" Discovery:**  
   If Kenya’s rate declines while neighbors’ rise, analyze effective local interventions.  
   *→ Solution: Share Kenya’s strategies regionally.*  

4. **The "Weekend Effect":**  
   If certain days show spikes, deploy targeted crisis interventions.  
   *→ Solution: Weekend-focused mental health support programs.*  

5. **The "COVID Impact":**  
   Quantify changes during pandemic years.  
   *→ Solution: Strengthen mental health systems for future crises.*  

---

##  Business & Community Impact

### Quantifiable Benefits

| Impact Area | Description | Measurable Outcome |
|--------------|-------------|--------------------|
| **Lives Saved** | Reduce suicide deaths by 15% through targeted interventions | ~127 lives saved yearly |
| **Economic Savings** | Lower economic loss from suicide | KES 254–381M saved annually |
| **Healthcare Efficiency** | Better staff allocation and early interventions | 25–40% improvement |
| **Policy Effectiveness** | Faster, data-driven decision-making | 40% quicker policy actions |
| **Community Awareness** | Normalize mental health conversations | Stigma reduction and earlier help-seeking |

### Stakeholder Value

| Stakeholder | Problem Solved | Value Delivered |
|--------------|----------------|-----------------|
| **Ministry of Health** | Blind budget allocation | Data-driven resource distribution |
| **County Governments** | Unknown local trends | Identify high-risk counties |
| **Crisis Hotlines** | Random staffing | Predictive scheduling during high-risk months |
| **NGOs (e.g., Befrienders Kenya)** | Generic programs | Targeted interventions for men aged 25–44 |
| **Employers** | Employee wellness gaps | Evidence-based mental health programs |

---

##  Deliverables

1. **Cleaned Datasets (CSV)**  
   - Kenya monthly suicide data by age and gender  
   - African comparison data (7 countries, 2015–2021)  

2. **SQL Analysis Scripts**  
   - Schema design and data loading  
   - Analytical queries and comparative views  

3. **Excel Workbook**  
   - Pivot tables, charts, and summary statistics  

4. **Tableau Dashboard**  
   - Multi-page dashboard with:
     - Temporal trends  
     - Geographic and demographic analysis  
     - Actionable insights  

5. **Technical Report**  
   - Findings, recommendations, limitations, and future directions  

---

##  Getting Started

### Requirements
- Microsoft Excel 2016 or later  
- SQL (MySQL/PostgreSQL)  
- Tableau Desktop or Tableau Public  

### Setup Steps
1. Download and review both CSV datasets.  
2. Clean and validate in Excel.  
3. Load into SQL database.  
4. Connect Tableau to visualize.  

---

##  Success Metrics

✅ Identify at least 3 actionable demographic patterns  
✅ Reveal temporal trends to guide intervention timing  
✅ Create dashboards used by at least one mental health organization  
✅ Provide policy insights aligned with Kenya’s National Mental Health Policy  
✅ Demonstrate technical proficiency in SQL, Excel, and Tableau  

---

##  Data Sources & Limitations

### Sources
- World Health Organization (WHO) Global Health Observatory  
- Kenya National Bureau of Statistics (KNBS)  
- Civil Registration Services (2018–2021)  
- World Bank Development Indicators  

### Limitations
- Under-reporting due to stigma (~30%)  
- Data quality gaps in some countries  
- Misclassification of cause of death  
- Missing socioeconomic factors  

### Ethical Considerations
- Data used solely for prevention and awareness  
- Aggregated to protect privacy  
- Aims to reduce stigma, not sensationalize deaths  

---

##  Contact & Contributions

**Project Lead:** Brenda Chebet
**Email:** koskeybrenda1@gmail.com  
 

**Contributions Welcome:**  
Open to collaboration with data scientists, health experts, and policy researchers.

---

##  Acknowledgments
- Befrienders Kenya for advocacy  
- WHO for health data  
- Kenya Ministry of Health for official statistics  
- Data analysts dedicated to social impact work  

---

##  License
This project is shared under the **MIT License** — free to use for research, policy, and educational purposes.

---

**Remember:** Behind every statistic is a person, a family, and a community.  
This project exists to save lives.  

**National Crisis Hotline (Kenya):** 0800 720 990 (Toll-free, 24/7)
 

Together, they demonstrate how **data storytelling** can inspire both **policy action** and **social change** — turning insights into impact.
