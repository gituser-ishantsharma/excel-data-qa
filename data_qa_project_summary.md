# 🧪 Excel Data QA Project

This project demonstrates **manual data validation and QA testing** on an Excel dataset containing customer information. The goal is to identify common data quality issues using test cases, document defects, and showcase structured QA analysis without the use of automation.

---

## ✅ Objective

To simulate a real-world QA scenario where data from a source system must be validated before use in analytics or processing pipelines. The focus is on **data integrity**, **format validation**, and **manual QA techniques**.

---

## 📊 Dataset Description

**File:** `sample_data.xlsx`  
This Excel file contains customer records with intentional issues such as:
- Duplicate customer IDs
- Invalid or malformed email addresses
- Missing values in required fields (Name, Email)
- Incorrect date formats

---

## 🧾 Test Cases

**File:** `data_validation_test_cases.xlsx`  
This file includes manually written test cases that validate:
- Field-level constraints (e.g., Email must contain '@')
- Uniqueness checks (Customer ID)
- Null value checks (Name, Email)
- Date format consistency

Each test case includes:
- Test Case ID
- Test Scenario
- Expected Result
- Actual Result
- Status (Pass/Fail)

---

## 💡 QA Concepts Demonstrated

- Manual Test Case Design
- Data Integrity Verification
- Defect Identification and Documentation
- Reproducible Test Reporting in Excel
- Structured QA Folder Organization

---

## 🚀 How to Use

1. Open `sample_data.xlsx` to review the test dataset.
2. Open `data_validation_test_cases.xlsx` to view test cases and results.
3. Analyze the defects and see how they are documented manually.
4. Modify, extend, or automate tests based on your learning goals!

---

## 🔄 Possible Extensions

- Add **automated validation using Python or VBA**
- Integrate with **ETL tools like Pentaho** for QA automation
- Apply **data profiling tools** for large-scale QA
- Create **charts or pivot tables** to summarize issues

---

## 🙌 Author

**Ishant Sharma**  
QA Analyst | Software Tester | Data Quality Enthusiast  
[GitHub Profile](https://github.com/ishantsharma1994)
