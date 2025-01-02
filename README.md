# Healthcare Insights Dashboard using Power BI

## Executive Summary
This project utilizes Power BI to analyze inpatient discharge data from healthcare facilities, focusing on procedures like total hip replacements. The dashboard highlights key metrics such as treatment costs, length of stay, patient demographics, and outcomes. These insights can guide healthcare administrators in optimizing operational efficiency and improving patient outcomes.

## Tools and Skills
Power BI: Developed dynamic visualizations and an interactive dashboard.

Data Analysis: Performed in-depth analysis of hospital and patient data to derive meaningful insights.

Statistical Analysis: Applied statistical methods to uncover trends and correlations in the data.

Healthcare Domain Expertise: Interpreted analytical results with a strong understanding of healthcare operations and patient care.

## Datasets
This project leverages hospital inpatient discharge data provided by the New York State Department of Health. The dataset contains 30 columns, as described below:

1. Facility Information

health_service_area: Description of the health service area where the hospital is located.

hospital_county: County where the hospital is located.

operating_certificate_number: Facility Operating Certificate Number assigned by NYSDOH.

facility_id: Permanent Facility Identifier (PFI).

facility_name: Name of the facility where services were performed.


2. Patient Demographics

age_group: Patient's age grouped into categories (e.g., 0 to 17, 18 to 29, etc.).

zip_code_3_digits: First three digits of the patient’s ZIP code.

gender: Patient gender (Male, Female, or Unknown).

race: Patient’s racial category (e.g., White, Black/African American, etc.).

ethnicity: Patient ethnicity (e.g., Hispanic, Non-Hispanic, etc.).


3. Hospital Stay Details

length_of_stay: Total number of days the patient stayed in the hospital.

type_of_admission: Manner of admission (e.g., Elective, Emergency, etc.).

patient_disposition: Patient’s status upon discharge.

discharge_year: Year of discharge.


4. Diagnosis and Procedure Details

ccs_diagnosis_code: AHRQ Clinical Classification Software Diagnosis Code.

ccs_diagnosis_description: Description of the diagnosis code.

ccs_procedure_code: AHRQ Clinical Classification Software Procedure Code.

ccs_procedure_description: Description of the procedure code.


5. APR (All Patient Refined) Classification

apr_drg_code: All Patient Refined Diagnosis Related Group (APR-DRG) code.

apr_drg_description: Description of the APR-DRG code.

apr_mdc_code: All Patient Refined Major Diagnostic Category code.

apr_mdc_description: Description of the APR Major Diagnostic Category.

apr_severity_of_illness_code: Severity of illness code (1 = Minor, 2 = Moderate, etc.).

apr_severity_of_illness_description: Description of severity (e.g., Minor, Major).

apr_risk_of_mortality: Risk of mortality classification (e.g., Minor, Major).

apr_medical_surgical_description: Classification (Medical or Surgical).


6. Provider Information

attending_provider_license_number: License number of the attending healthcare provider.

operating_provider_license_number: License number of the provider who performed the procedure.


7. Financial Information

total_charges: Total charges billed for the patient’s hospital stay.

total_costs: Total estimated costs incurred by the hospital.


## Business Question
