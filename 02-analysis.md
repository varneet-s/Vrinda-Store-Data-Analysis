# Analysis
[Vrinda_Store_Data_Analysis_Report_2022.xlsx](https://github.com/user-attachments/files/27118889/Vrinda_Store_Data_Analysis_Report_2022.xlsx)
---

## 1. Data Cleaning

### Situation  
The dataset contained inconsistencies in categorical and numerical fields that could affect analysis accuracy.

### Task  
Ensure data consistency so that aggregation and analysis produce correct results.

### Action  
- Standardized the **Gender** column:
  - Converted `M`, `Men` → `Men`
  - Converted `W`, `Women` → `Women`
- Cleaned the **Quantity** column:
  - Converted text values (`one`, `two`) into numeric format (`1`, `2`)

### Result  
- Ensured uniform categories for accurate grouping and comparison  
- Enabled correct numerical calculations for quantity-based analysis  

---

## 2. Data Processing

### Situation  
The raw dataset did not contain structured fields required for segmentation and time-based analysis.

### Task  
Prepare the dataset to enable meaningful segmentation and trend analysis.

### Action  

#### Age Group Creation  
- Created an **Age Group** column using the following logic:
  - `< 30` → Young Adult  
  - `30–49` → Adult  
  - `50+` → Senior  

#### Month Extraction  
- Extracted **Month** from the Date column to analyse monthly trends  

#### Contribution Calculation (for Insights)  
- Calculated percentage contribution using total values   

### Result  
- Enabled customer segmentation by age group  
- Allowed monthly trend analysis of sales and orders  

---

## 3. Data Analysis

### Situation  
After cleaning and structuring the data, analysis was required to identify key business drivers.

### Task  
Analyse sales data to identify patterns across customers, regions, and channels.

### Action  

#### Sales vs Orders Trend  
<img width="591" height="276" alt="sales-trend" src="https://github.com/user-attachments/assets/790f7b8b-d34e-4f6e-a24c-57c1a1084fcd" />

- Compared total sales and the number of orders across months  

#### Customer Segmentation
<img width="372" height="270" alt="customer-segmentation" src="https://github.com/user-attachments/assets/30c80cc6-1b89-4147-8158-a7f50c6901db" />

- Analysed order distribution by **Gender**  
- Evaluated contribution by **Age Group**  

#### Geographic Analysis
<img width="563" height="271" alt="state-analysis" src="https://github.com/user-attachments/assets/dbe9619a-87ed-4205-9b5e-6f6a6a9ddb0f" />

- Identified top states contributing to overall sales  

#### Channel Analysis
<img width="358" height="279" alt="channel-analysis" src="https://github.com/user-attachments/assets/154861e7-5311-4b2d-8a10-0813152b236d" />

- Compared the performance of different sales platforms  

#### Order Status Analysis
<img width="355" height="266" alt="order-status" src="https://github.com/user-attachments/assets/432a2fa5-1700-4099-ae32-ab20f85f4fbe" />

- Reviewed distribution of order statuses  

### Result
<img width="1473" height="635" alt="dashboard" src="https://github.com/user-attachments/assets/3846ece1-e78d-48c1-bd38-bd365588c50c" />

- Identified high-value customer segment (Women, 30–49 age group)  
- Identified top-performing states and channels  
- Highlighted concentration of sales across limited segments  

---
