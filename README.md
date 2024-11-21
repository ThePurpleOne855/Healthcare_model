# Healthcare Data Analysis #


"Through my analysis of healthcare data, I aimed to uncover critical patterns in patient demographics and disease prevalence. By examining age, gender, and geographic distribution alongside the most common medical conditions, I identified key trends that provide insights into the healthcare needs of different populations. This story highlights actionable findings that can inform better decision-making in patient care and resource allocation."

## Overview  
This project involves analyzing a healthcare dataset to uncover trends in patient demographics and disease prevalence. Using Python and Power BI, I transformed raw data into actionable insights through data cleaning, modeling, and visualization.

## My Work

1. **Data Transformation**  
   - I obtained the uncleaned dataset from Kaggle.  
   - Using Python's Pandas library, I converted the dataset from CSV to Excel format for further processing.

2. **Data Cleaning**  
   - I normalized text fields to ensure consistency.  
   - Eliminated duplicate values and empty rows to improve data quality.  
   - Added a unique `ID` column for each patient to facilitate tracking and analysis.

3. **Data Modeling in Power BI**  
   - I created new dimensional tables to structure the data:
     - `dim_doctor`  
     - `dim_hospital`  
     - `dim_insurance_provider`  
     - `dim_patient`  
   - Designed a fact table, `fact_admission`, to store core transactional data.  
   - Established a **star schema** by creating relationships between all dimension tables and the fact table.

4. **Data Visualization in Power BI**  
   - I built interactive charts and dashboards to highlight key insights:
     - **Patient demographics**: Visualized age, blood group, and gender distribution.  
     - **Medical conditions and treatments**: Displayed the prevalence of different conditions and treatments.  
     - **Age group analysis**: Identified which age groups are most affected by illnesses.

## Technologies Used
- Python (Pandas)
- Power BI
- Excel
- Kaggle

## Findings

1. **Blood Type Distribution**  
   The distribution of blood types across the dataset is symmetrical, with nearly equal representation of each blood type:
   - O-, O+, A+, A-, AB+, B+, B-, AB-
   ![Screenshot 2024-11-20 195743](https://github.com/user-attachments/assets/578f820c-34e9-4c8d-acdb-052346d80bef)


2. **Gender Distribution**  
   The gender distribution is almost symmetrical between women and men, with women representing 50.05% and men representing 49.95%.


   ![Screenshot 2024-11-20 195824](https://github.com/user-attachments/assets/2f5c91d8-e1c5-4a3a-8d85-ce0fc0b98d7e)


4. **Age Group Analysis**  
   The most affected age group in this dataset is **middle adulthood (40-64 years old)**, followed by:
   - **Late adulthood (+65 years old)**
   - **Young adulthood (30-39 years old)**
   - **Adolescence (13-19 years old)**


![Screenshot 2024-11-20 195913](https://github.com/user-attachments/assets/2c03fe8c-0d0f-4034-9f1e-1f920d039e4e)

   
**Medical Conditions and Treatments**  
   The dataset includes patients with the following medical conditions:
   - Arthritis
   - Diabetes
   - Hypertension
   - Obesity
   - Asthma
   - Cancer

![Screenshot 2024-11-20 200408](https://github.com/user-attachments/assets/1403ed2a-d7ec-48a9-b3c6-5878410bcfe5)

** Illness Distribution Across Age Group

![Screenshot 2024-11-20 200434](https://github.com/user-attachments/assets/77205ac9-5759-4262-a3a3-c5567ec46c70)

   These conditions were treated with the following medications:
   - **Aspirin**
   - **Ibuprofen**
   - **Lipitor**
   - **Paracetamol**
   - **Penicillin**
![Screenshot 2024-11-20 200441](https://github.com/user-attachments/assets/219361cf-df71-48bb-b74d-48d4ecd8c8c5)
