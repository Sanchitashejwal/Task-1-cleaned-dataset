# Medical Appointment Dataset – Data Cleaning Report

## Introduction  
This report provides an overview of the cleaning and formatting changes made to the **Medical Appointment Dataset**. The dataset initially had issues such as extra spaces, special characters, inconsistent capitalization, and formatting errors, which needed to be fixed for better readability and analysis.  

---

## Changes Made  

### 1. Removing Unnecessary Spaces  
- Trimmed extra spaces in columns like **Neighbourhood** to ensure consistency.

### 2. Standardizing Text Formatting  
- Converted all uppercase names to **Title Case** (e.g., `JARDIM DA PENHA` → `Jardim Da Penha`).

### 3. Fixing Special Character Issues  
- Fixed corrupted characters in **Neighbourhood names** (e.g., `REPÃBLICA` → `REPÚBLICA`).

### 4. Checking Gender Column for Consistency  
- Ensured all values in **Gender** were either `Male` or `Female`.

### 5. Formatting Numerical Data  
- Checked **Age, PatientId, and AppointmentId** to ensure they only contained numbers.

### 6. Verifying Date Formatting  
- Made sure **ScheduledDay** and **AppointmentDay** were in `YYYY-MM-DD HH:MM` format.

### 7. Standardizing Categorical Values  
- Verified binary columns (**Scholarship, Hypertension, Diabetes, Alcoholism, Handicap**) contained only `0` or `1`.

---

## Final Outcome  
- The dataset is now **clean and structured**, ready for analysis.  
- The updated file is saved as https://github.com/sanchshejwal01/cleaned-Medical-appoinment-dataset/blob/main/cleaned_Medical_appoinment_dataset.xlsx

---

## Next Steps  
- Perform analysis in **Power BI, Excel, or Python**.  

---

This report documents the data cleaning process. Further refinements can be made as needed. 😊
