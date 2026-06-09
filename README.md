# 🧪 OrangeHRM - Manual Testing Project

This repository contains a comprehensive manual testing suite for the OrangeHRM Management System web application (Open-Source Demo). The project demonstrates the application of software testing methodologies to ensure the application's functionality, usability, and reliability across core human resource management workflows.

---

## 🎯 Project Overview

The objective of this project is to perform end-to-end manual testing on the OrangeHRM platform. Testing focused on critical user journeys, administrative security, edge cases, and UI/UX validation to identify defects, enforce data integrity, and ensure a seamless user experience.

## 🔍 Scope of Testing

**🔐 Authentication Module (Login & Logout)**
<br>Verifying session timeouts, cross-tab behavior, invalid credentials handling, and secure logouts.

**🔑 Forgot Password Feature**
<br>Validating security links, username existence checks, error messaging, and input criteria (special characters/spaces).

**👤 PIM - Add Employee**
<br>Testing strict data validation rules on mandatory fields, profile picture uploads, unique Employee ID generation, and "Create Login Details" logic.

**📋 PIM - Employee List & Search**
<br>Verifying complex filtering using multiple criteria (Employee Name, ID, Job Title, Sub Unit) and Autocomplete hints.

**📊 PIM - Reports**
<br>Validating the behavior of system-defined pre-loaded reports, custom report queries, search resets, and record counts.

---

## 📊 Project Artifacts

### 1️⃣ Test Cases
A comprehensive set of 89 test cases divided by features to ensure maximum test coverage.

🟢 [Click Here to View the Full Live Google Sheet (All Features)](https://docs.google.com/spreadsheets/d/1cFOsZXKNAsAAug7JS4JopjPVP3i3RycegJGBG4Ng8Mo/edit?usp=sharing)

📂 Quick Previews on GitHub (Tab-separated CSV Files):
* [Authentication Test Cases (Login & Logout)](Authentication_Login_Logout.csv)
* [Forgot Password Test Cases](Forgot_Password.csv)
* [PIM - Add Employee Test Cases](PIM_Add_Employee.csv)
* [PIM - Employee List Test Cases](PIM_Employee_List.csv)
* [PIM - Reports Test Cases](PIM_Reports.csv)

### 2️⃣ Bug Reports
Detailed defect reports documented with clear steps to reproduce, actual vs. expected results, severity, and environment.

📂 GitHub Preview:
* 🔴 [Click Here to View Bug Reports](Bug_Report.csv)

### 3️⃣ Test Execution Summary
A high-level dashboard combining key metrics, execution ratios, pass/fail statistics, and bug severity tracking.

📂 GitHub Preview:
* [Click Here to View the Test Summary Report File](Test_Summary_Report.csv)

---

## 📊 Comprehensive Testing Dashboard

<small>
  
| Metric | Value | Percentage | Feature Tested | Test Cases Number | Passed | Failed | Status / Result |
| :--- | :---: | :---: | :--- | :---: | :---: | :---: | :--- |
| **Total Test Cases Planned** | 89 | 100% | **Authentication** | 17 | 16 | 1 | 🔴 FAILED (Hold) |
| **Total Test Cases Executed** | 89 | 100% | **Forgot Password** | 10 | 8 | 2 | 🔴 FAILED (Hold) |
| **Total Test Cases Passed** | 79 | 88.76% | **PIM - Add Employee** | 42 | 35 | 7 | 🔴 FAILED (Hold) |
| **Total Test Cases Failed** | 10 | 11.24% | **PIM - Employee List** | 12 | 12 | 0 | 🟢 PASSED |
| **Critical Bugs** | 1 | -- | **PIM - Reports** | 8 | 8 | 0 | 🟢 PASSED |
| **High Bugs** | 5 | -- | **Final Decision** | **89** | **79** | **10** | 🛑 **HOLD RELEASE** |
| **Medium Bugs** | 4 | -- | | | | | |
| **Low Bugs** | 0 | -- | | | | | |

</small>
---

## 📂 Repository Structure

```text
OrangeHRM-Manual-Testing-Project
│
├── 📄 Authentication_Login_Logout.csv
├── 📄 Forgot_Password.csv
├── 📄 PIM_Add_Employee.csv
├── 📄 PIM_Employee_List.csv
├── 📄 PIM_Reports.csv
├── 📄 Bug_Report.csv
├── 📄 Test_Summary_Report.csv
└── 📜 README.md


## 📂 Repository Structure

```text
OrangeHRM-Manual-Testing-Project
│
├── 📄 Authentication_Login_Logout.csv
├── 📄 Forgot_Password.csv
├── 📄 PIM_Add_Employee.csv
├── 📄 PIM_Employee_List.csv
├── 📄 PIM_Reports.csv
├── 📄 Bug_Report.csv
├── 📄 Test_Summary_Report.csv
└── 📜 README.md
```

## 🛠️ Testing Techniques Applied

* **Black Box Testing Techniques:** Boundary Value Analysis (BVA) & Equivalence Partitioning (EP) for Employee ID, input text constraints, and name combinations.
* **Functional & Security Testing:** UI/UX verification, cross-browser sanity (Chrome & Edge), field level validation, and multi-tab session behavior.

## 🧰 Tools & Technologies

* **Google Sheets / CSV format:** Test management, defect tracking, and metric calculation cleanly organized.
* **GitHub:** Portfolio hosting and project documentation.

## 🔗 Quick Links

* **Tested Application:** [OrangeHRM Open-Source Demo](https://opensource-demo.orangehrmlive.com)

---

## 👤 Author

**Ahmed Farag** *Junior Software Tester / QA Engineer*
