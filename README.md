# 💳 Consumer Financial Complaints Analysis

_Exploring complaint patterns, response timeliness, and company performance in the U.S. financial sector (2017–2023)._

---

## Quick Look

- **Total Complaints (2017–2023):** ~63,000  
- **High-Complaint States:** California, Florida, Texas, New York, Georgia (~40% of complaints)  
- **Top Products:** Checking/savings accounts, credit cards (~65% of complaints)  
- **Timely Response:** Overall 93.8%, dropped to 78% in 2023  
- **Peak Complaint Month:** July (~32% higher than January)  
- **Interactive Dashboard:** [View Power BI Report](https://app.powerbi.com/view?r=eyJrIjoiNzc0MzI5ZjktNmNkOS00Y2Y4LWFkNmEtMzI2MGIyNDA3ZDkxIiwidCI6IjdlMGI1ZmNmLTEyYzQtNGVmZi05NmI2LTQ2NjRmMjVkYzdkYSIsImMiOjEwfQ%3D%3D)  
- **Full Story & Deep Dive:** [Read Full Analysis on Medium](https://medium.com/@odzainab1/consumer-complaint-finance-555044ea3101)


---

## Introduction

Millions of U.S. consumers raise complaints about financial products annually. Beyond individual grievances, these records reveal **systemic patterns in company performance, responsiveness, and consumer protection gaps**.

This analysis leverages the **CFPB consumer complaints dataset (2017–2023, Onyx Data Challenge)** to uncover:

- Regional and product-based complaint concentration  
- Seasonal trends and peak periods  
- Company response timeliness and operational efficiency  

The goal is to provide actionable insights for **regulators, companies, journalists, and consumers** to improve oversight, operational performance, and transparency.

---

## Business Problem

Consumer complaint data is critical for:

- **Regulatory oversight:** identifying systemic risk and operational gaps  
- **Journalistic investigation:** highlighting fairness and compliance issues  
- **Consumer transparency:** understanding how financial institutions handle complaints  

By analyzing complaint trends, response timeliness, and company behavior, this project supports actionable decisions to **strengthen consumer protection and operational accountability**.

---

## Dataset & Tools

**Key Tables:**  
- Complaints (Complaint ID, Date submitted/received, Timely response?)  
- Consumer & Submission Info (State, Region, Submission channel)  
- Product & Issue Info (Product, Sub-product, Issue, Sub-issue)  
- Company Response (Public response, Response time, Company ID)

**Tools Used:**  
- Power Query – Data cleaning, transformation  
- Power BI – Data modeling, DAX measures, and visualization  

---

## Data Preparation & Validation

- Standardized core attributes (product, sub-product, issue, sub-issue)  
- Replaced missing or ambiguous values with **“Unknown”**  
- Trimmed text fields for consistency across company names and responses  
- Rounded numeric metrics (response times, market share percentages)  
- Checked for duplicates to ensure accurate complaint and company counts  
- Validated calculated metrics such as complaints per 1% market share  
- Created company ranking indicators based on complaint volumes and response performance  
- Built two Date dimension tables (submission & response dates) to enable trend and timeliness analysis  

**Outcome:** an **analysis-ready dataset** structured for cross-dimensional insights into complaint drivers, response efficiency, and company accountability.

---
## Data Visualization


<img width="1050" height="596" alt="Screenshot 2026-01-09 220854" src="https://github.com/user-attachments/assets/e17657c6-2733-4a23-bdcb-76e6da08849d" />



<img width="1069" height="610" alt="Screenshot 2026-01-09 220905" src="https://github.com/user-attachments/assets/843502c0-c5e3-439d-9a14-fc834107b730" />




<img width="1062" height="603" alt="Screenshot 2026-01-09 220918" src="https://github.com/user-attachments/assets/b0d8868f-e83f-4a2c-96ed-d7e593314227" />



<img width="1085" height="602" alt="Screenshot 2026-01-09 220931" src="https://github.com/user-attachments/assets/fa230926-75fb-48be-ac17-56510b7a6c00" />



## Key Insights

### 1. Regional concentration drives systemic risk
Top 5 states (CA, FL, TX, NY, GA) account for ~40% of complaints. The South and West regions generate nearly 70% of complaints, indicating geographic hotspots for oversight and operational focus.

### 2. Product and issue patterns highlight operational gaps
Checking/savings accounts and credit cards dominate complaints (~65%). Common issues like **“Managing an account”** and **“Incorrect information”** make up ~33% of total complaints.

### 3. Digital channels are high-leverage points
Web and Referrals comprise over 50% of complaints, highlighting critical touchpoints that affect consumer experience. Seasonal surges in July (+32%) emphasize the need for workflow planning and resource allocation.

### 4. Company performance and market share
- Smaller firms handle the bulk of complaints (~70%) but maintain high timely response rates  
- Top 10 companies represent a disproportionate share of complaints relative to market share  
- Timely responses dropped to 78% in 2023, with “In-Progress” complaints rising to 15.5%  

### 5. Seasonal & operational implications
Complaint volume peaks mid-year; operational bottlenecks appear even when overall response times remain consistent. These trends reveal priority areas for staffing, process improvement, and regulatory focus.

---

## Recommendations

1. **Target High-Risk Products & Regions**  
   Prioritize monitoring and auditing for checking/savings, credit cards, and top complaint states (CA, FL, TX, NY, GA).

2. **Enhance Digital Channel Management**  
   Streamline Web and Referral complaint handling with automated tracking, prompt acknowledgment, and workflow improvements.

3. **Focus on Companies with Disproportionate Complaint Volume**  
   Conduct targeted process audits and staff training to reduce complaint density relative to market share.

4. **Plan for Seasonal Peaks**  
   Adopt dynamic staffing and flexible processes to handle mid-year complaint surges.

5. **Monitor KPIs Continuously**  
   Implement dashboards to track complaints, response timeliness, and company performance trends over time.

---

## Next Steps

- Automate complaint workflows and response tracking  
- Provide targeted employee training for high-volume complaint types  
- Maintain KPI dashboards for ongoing monitoring  
- Engage proactively with consumers to prevent repeat complaints  

---

## Conclusion

While most firms maintain high timely response rates, complaint concentration in specific products, regions, and channels, along with seasonal peaks and emerging bottlenecks, points to **opportunities for operational optimization and targeted oversight**. Implementing these strategies will improve **consumer satisfaction, regulatory compliance, and overall financial service performance**.
