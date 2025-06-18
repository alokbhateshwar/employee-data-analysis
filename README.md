# employee-data-analysis
# 🧹 Employee Data Cleaning and Analysis

This project focuses on cleaning and analyzing a dataset of employee records using Python, Pandas, NumPy, and Matplotlib.

---

## 📁 Dataset Overview

- Contains employee details such as:
  - Name
  - Age
  - City
  - Salary
  - Email
  - Join Date
  - Employee ID

---

## ✅ Cleaning Tasks Performed

1. **Missing Data Handling**
   - Filled missing values in `Age`, `Salary`, `City`, and `Name`.

2. **Standardization**
   - Standardized city names (`NY` → `New York`, etc.).
   - Corrected name formatting and removed special characters.
   - Converted `Join Date` to datetime.

3. **Outliers and Validation**
   - Removed unrealistic age and salary values.
   - Identified and flagged invalid emails.

4. **Duplicates**
   - Removed duplicate entries based on `Name` or `Employee ID`.

5. **Feature Engineering**
   - Extracted `Join_Year` from `Join Date`.
   - Created valid email formats using employee names.
   - Added a `Data_Quality_Flag` column for rows with issues.

---

## 📊 Visualizations

- Bar chart showing average age and salary.
- Join trends per year with color-coded bars.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib

---

## 📌 Author

Alok Bhateshwar  
GitHub: [@alokbhateshwar](https://github.com/alokbhateshwar)

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
