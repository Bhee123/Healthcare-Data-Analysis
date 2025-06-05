# Healthcare-Data-Analysis 

## INTRODUCTION

This project analyzes patient healthcare data using Microsoft Excel to uncover patterns, trends, and performance metrics in medical conditions, admission types, patient demographics, and healthcare costs. The aim was to derive insights that can guide better decision-making in hospital resource allocation and patient care strategies. 

## OBJECTIVES

-	Analyze distributions of medical conditions, test results, and admission types
-	Calculate average billing costs by condition, admission type and insurance provider
-	Evaluate operational metrics like average length of stay (LOS) by hospital and diagnosis
-	Generate KPIs for healthcare performance monitoring

## BACKGROUND & CONTEXT

-	Data Source: Kaggle.com
-	Scope of Analysis: Focus areas such as patient demographics, medical conditions, financial trends, and operational metrics

## TOOLS & METHODS

Microsoft Excel was used for the entire analysis. 
Key techniques included pivot tables to summarize data, bar charts to visualize condition and admission frequency, 
and conditional formatting to highlight cost and stay variations.

## DATASET DESCRIPTION

The dataset comprises records of patients admitted to various hospitals.
### Key fields include:
-	Patient demographics (Age, Gender, Blood type)
-	Medical information (Condition, Test results, Medications)
-	Hospital & Insurance Details (Doctor, Hospital, Insurance Provider)
-	Admission & Discharge data (Admission type, LOS, Billing Amount)

## DATA CLEANING & PREPARATION

-	Checked for missing or inconsistent values
-	Converted date fields to excel date formats
-	Ensured numeric columns (e.g., age, billing amount, length of stay) were correctly formatted.

  ## VISUALIZATIONS

 ![Image](https://github.com/user-attachments/assets/46dbd72f-ce48-4cbd-859b-c22839d7ec8d)
  
### Age Distribution
-	Created a bar chart to show patient age category
-	Majority of patients fall within the old and middle age brackets

### Medical Conditions
- A column chart visualizing the prevalence of various medical conditions (e.g., Cancer, Diabetes, Obesity)

### Admission Types
- A column chart comparing the average billing amounts by admission type which comprises Emergency, Urgent and Elective admissions

### Billing Analysis
- Average costs were highest for Emergency admission type and Blue-Cross insurance provider

### Length of Stay 
- Bar chart of length of hospital stay

### Blood group Distribution
- A line chart depicting counts of different blood groups against test results

You can interact with the live visualization [HERE](https://docs.google.com/spreadsheets/d/1EMGkQe6XurukYWbspWpWoTUdvssmVT88/edit?usp=drive_link&ouid=112568531909654830535&rtpof=true&sd=true)

## KEY INSIGHTS

-	Arthritis and Diabetes are the most common conditions treated
-	Elective admissions tend to result in higher average billing amount and longer stays
-	Patients with Blue-cross and Medicare insurance represent a significant portion of the dataset
-	Average billing for Obesity patients exceeds that of other conditions
-	Elderly patients (age bracket: 'Old') had the longest average hospital stays, particularly when treated for chronic conditions.
-	Lipitor and Ibuprofen was the most prescribed medication and had the highest association with abnormal test results.
  
## CONCLUSION AND RECOMMENDATIONS 
This analysis offers critical insights into healthcare utilization patterns. Excel’s built-in features like PivotTables, charts, and conditional formatting were instrumental in uncovering trends that could support data-driven decision making in hospital administration. I would recommend the following: 

-	Allocate more resources and specialized care for elderly patients with chronic diseases.
-	Reassess Ibuprofen prescriptions due to its correlation with abnormal test results.
-	Focus preventive care and support services around obesity, given its frequency and impact.

