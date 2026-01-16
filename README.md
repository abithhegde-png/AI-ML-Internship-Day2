# AI & ML Internship – Task 2  
## Data Cleaning & Missing Value Handling

### Objective
Learn how to clean datasets, handle missing values, and prepare data for machine learning.  

We worked with **two datasets**:  

---

### Datasets

1. **House Prices Dataset**  
   - Columns: price, area, bedrooms, bathrooms, stories, mainroad, guestroom, basement, hotwaterheating, airconditioning, parking, prefarea, furnishingstatus  
   - Goal: Check and clean missing/invalid values.

2. **Medical Appointment No Shows Dataset**  
   - Columns: PatientId, AppointmentID, Gender, ScheduledDay, AppointmentDay, Age, Neighbourhood, Scholarship, Hipertension, Diabetes, Alcoholism, Handcap, SMS_received, No-show  
   - Goal: Handle missing values and convert **No-show** to 0/1.

---

### Steps Done

#### House Prices Dataset
- Loaded dataset in Pandas.
- Checked missing values with `isnull().sum()`.
- Visualized missing values using bar chart.
- Showed how to fill missing numerical values with mean/median.
- Showed how to fill missing categorical values with mode.
- Checked numerical, categorical, and binary columns.
- Saved cleaned dataset: `cleaned_house_prices.csv`.

#### Medical Appointment No Shows Dataset
- Loaded dataset in Pandas.
- Checked missing values with `isnull().sum()`.
- Visualized missing values using bar chart.
- Removed invalid rows (like negative ages).
- Converted **No-show** column: `No` → 0, `Yes` → 1.
- Saved cleaned dataset: `cleaned_medical_no_shows.csv`.

---

### Outcome
- Both datasets cleaned and ready for ML.
- Missing values handled or explained.
- Target variables ready for modeling.



