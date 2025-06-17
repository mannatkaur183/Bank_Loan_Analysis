# Bank Loan Report Dashboard in Tableau

This project presents a comprehensive **Bank Loan Report** built entirely using **Tableau**. It provides a multi-dashboard analytical view of a bank’s lending activities, designed to monitor KPIs, identify trends, and assess the quality of the loan portfolio through interactive visualizations.

---

## Dashboards Overview
![image](https://github.com/user-attachments/assets/55822c9e-8cc7-493b-abdd-51a759aa272d)
![image](https://github.com/user-attachments/assets/f2bf5d5d-f033-42fb-bfd4-be98200280d4)
![image](https://github.com/user-attachments/assets/8b9463ce-8f1b-49b2-96df-6373a0916225)
![image](https://github.com/user-attachments/assets/dbed3768-231f-4a40-86b3-54b2827460ce)


###  **Dashboard 1: Summary**
**Platform:** Tableau  
**Focus:** High-level KPIs to evaluate lending performance and portfolio health.

####  Key Performance Indicators (KPIs):
- **Total Loan Applications**
  - Tracks overall, Month-to-Date (MTD), and Month-over-Month (MoM) application counts.
- **Total Funded Amount**
  - Measures total disbursed loans with MTD and MoM changes.
- **Total Amount Received**
  - Represents repayments received from borrowers (MTD + MoM).
- **Average Interest Rate**
  - Calculates average across all loans with monthly comparison.
- **Average Debt-to-Income (DTI) Ratio**
  - Evaluates borrower financial condition (overall + monthly).

---

#### ✅ Good Loan vs Bad Loan Analysis:
**Criteria:**
- **Good Loans** → `Fully Paid` or `Current`
- **Bad Loans** → `Charged Off`

**Metrics Include:**
- Application counts and percentages
- Total Funded Amount
- Total Received Amount

---

#### Loan Status Grid View:
A tabular visualization in Tableau displaying per-loan-status:
- Applications
- Funded Amount
- Received Amount
- MTD metrics
- Avg. Interest Rate & DTI

---

### **Dashboard 2: Overview**
**Platform:** Tableau  
**Focus:** Exploratory insights via visual analytics.

#### Visualizations:

1. **Monthly Trends**
   - Metrics: Applications, Funded Amount, Received Amount
   - Based on `Issue Date`

2. **Regional Analysis by State**
   - State-wise distribution of loan activities

3. **Loan Term Analysis**
   - Distribution across 36-month and 60-month terms

4. **Employee Length Analysis**
   - Segmentation by borrower job duration

5. **Loan Purpose Breakdown**
   - Shows top reasons for loan applications (e.g., debt consolidation)

6. **Home Ownership Analysis**
   - Lending metrics segmented by ownership status (own, rent, mortgage)

---

###  **Dashboard 3: Details**
**Platform:** Tableau  
**Focus:** Drill-down view of all loan records and borrower details.

Includes:
- Full loan dataset with filtering
- Per-borrower insights
- Metrics: Loan Amount, Interest Rate, DTI, Purpose, Repayment, and Status
---

## Objective

- Provide decision-makers with a complete view of bank lending performance.
- Help identify borrower behavior trends and regional patterns.
- Track key financial metrics like repayments, interest, and DTI in real time.
