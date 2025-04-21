# task1_elevate_labs

# 🧼 Data Cleaning and Preprocessing - Medical Appointment No Shows

This project involves cleaning and preprocessing a real-world dataset titled *"Medical Appointment No Shows"* from Kaggle. The aim is to prepare the raw data for further analysis or modeling by addressing common data quality issues.

---

## 📁 Dataset Used
*Source:* [Kaggle - Medical Appointment No Shows](https://www.kaggle.com/datasets/joniarroba/noshowappointments)

*Filename:* KaggleV2-May-2016-dirty.csv

---

## 🛠 Tools Used
- Python
- Pandas
- NumPy
- Jupyter Notebook

---

## 🧾 Cleaning Tasks Performed

| Task | Description |
|------|-------------|
| *1. Load Dataset* | Used Pandas to load the CSV into a DataFrame |
| *2. Remove Duplicates* | Dropped duplicate records using .drop_duplicates() |
| *3. Handle Missing Values* | Dropped rows with critical nulls; filled others with defaults |
| *4. Standardize Text* | Converted Gender and Neighbourhood values to uppercase |
| *5. Fix Date Formats* | Parsed ScheduledDay and AppointmentDay to standard datetime |
| *6. Clean Column Names* | Converted all headers to lowercase and replaced spaces with underscores |
| *7. Fix Data Types* | Converted appropriate columns to int, datetime, or category |
| *8. Suppress Warnings* | Disabled unnecessary Jupyter warnings for clean output |

---

## ✅ Final Output

- cleaned_medical_appointments.csv: A clean, structured version of the dataset
- Cleaned DataFrame ready for:
  - Exploratory Data Analysis (EDA)
  - Visualization
  - Machine Learning Models

---

## 📊 Summary of Changes

- *Original Records:* 110,577
- *Duplicates Removed:* X rows (updated in notebook output)
- *Missing Value Treatment:* Mixed approach (drop + fill)
- *Standardized Columns:* gender, neighbourhood, dates, and headers
- *Exported Clean Dataset:* cleaned_medical_appointments.csv

---

## 📚 Interview Questions Covered

1. What are missing values and how do you handle them?
2. How do you treat duplicate records?
3. Difference between dropna() and fillna() in Pandas?
4. What is outlier treatment and why is it important?
5. Explain the process of standardizing data.
6. How do you handle inconsistent data formats (e.g., date/time)?
7. What are common data cleaning challenges?
8. How can you check data quality?

---

## 📎 How to Run

```bash
# Install required libraries
pip install pandas numpy

# Run the notebook
jupyter notebook data_cleaning.ipynb
