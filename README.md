# HSBC 2012 AML Case Study – Red Flag Detection Using Excel  

## Project Overview  
This project replicates a case study based on **HSBC’s 2012 money laundering scandal**, where the bank was fined **$1.9B** due to compliance failures, weak controls, and ignored red flags across high-risk regions.  

Using **Excel** and a **simulated dataset of 5,000 transactions**, I performed **AML red flag detection** to identify suspicious activity and built a summary dashboard.  

## Steps Performed  

### 1. Data Preparation  
- Created a **sample dataset of 5,000 transactions** including:  
  - Transaction IDs & Customer IDs  
  - Transaction Dates & Amounts  
  - Countries (high-risk & low-risk regions)  
  - Entity Types (Individuals, Shell Companies, Corporates, NGOs)  
  - KYC Status (Yes/No)  
  - Transaction Types (Wire, Cash, Online, Cheque)  

File: **`HSBC_AML_CaseStudy_Sample.xlsx`**

### 2. Red Flag Detection Rules  
Applied AML detection criteria in Excel to flag suspicious transactions:  
- Transactions **> $500,000**  
- Transactions from **high-risk countries** (Mexico, Cayman Islands, Nigeria, Russia, Hong Kong)  
- **Shell companies** with large transfers (> $100,000)  
- Accounts with **incomplete KYC documentation**  

File: **`HSBC_AML_Suspicious_Transactions_with_Dashboard.xlsx`**

### 3. Results & Dashboard  
- Total transactions analyzed: **5,000**  
- Suspicious transactions flagged: **3,498 (~70%)**  
- Key Insights:  
  - High concentration of red flags in **Mexico & Cayman Islands**  
  - **Shell companies** accounted for a large share of suspicious transfers  
  - **15% of accounts** had missing KYC details  

**Dashboard Sheet Includes:**  
- Overall statistics (total, flagged, % suspicious)  
- Suspicious by **Country**  
- Suspicious by **Entity Type**  

## How to Use  
1. Open **`HSBC_AML_CaseStudy_Sample.xlsx`** to view the raw transaction dataset.  
2. Open **`HSBC_AML_Suspicious_Transactions_with_Dashboard.xlsx`** to explore:  
   - Flagged suspicious transactions  
   - Dashboard summary (with filters & tables)  
3. Use Excel’s **pivot tables, charts, or conditional formatting** to customize further analysis.  

## Key Learning  
This project demonstrates how **Excel can be applied in AML/KYC analysis** to:  
- Detect suspicious transaction patterns  
- Document red flags  
- Build compliance case studies relevant to **Investment Banking Operations & AML roles**  

It also highlights the importance of **robust internal controls** in preventing financial crimes like money laundering.  
