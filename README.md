# 🧪 OrangeHRM - Manual Testing Project

This repository contains a comprehensive manual testing suite for the OrangeHRM web application (Open-Source Demo). The project demonstrates the application of software testing methodologies to ensure the application's functionality, usability, and reliability across core human resource management workflows.

---

## 🎯 Project Overview

The objective of this project is to perform end-to-end manual testing on the OrangeHRM platform. Testing focused on critical user journeys, administrative security, edge cases, and UI/UX validation to identify defects, enforce data integrity, and ensure a seamless user experience.

## 🔍 Scope of Testing

* **Authentication Module (Login & Logout):** Verifying session timeouts, cross-tab behavior, invalid credentials handling, and secure logouts.
* **Forgot Password Feature:** Validating security links, username existence checks, error messaging, and input criteria (special characters/spaces).
* **PIM - Add Employee:** Testing strict data validation rules on mandatory fields, profile picture uploads, unique Employee ID generation, and "Create Login Details" logic.
* **PIM - Employee List & Search:** Verifying complex filtering using multiple criteria (Employee Name, ID, Job Title, Sub Unit) and Autocomplete hints.
* **PIM - Reports:** Validating the behavior of system-defined pre-loaded reports, custom report queries, search resets, and record counts.

## 📊 Project Artifacts

### 1️⃣ Test Cases
A comprehensive set of test cases divided by features to ensure maximum test coverage.

🟢 Click Here to View the Full Live Google Sheet (All Features) https://docs.google.com/spreadsheets/d/1cFOsZXKNAsAAug7JS4JopjPVP3i3RycegJGBG4Ng8Mo/edit?usp=sharing

📂 Quick Previews on GitHub (Tab-separated CSV Files):
* [Authentication Test Cases](OrangeHRM%20Manual%20Testing%20Project%20-%20Authentication.csv)
* [Forgot Password Test Cases](OrangeHRM%20Manual%20Testing%20Project%20-%20Forget%20password%20%281%29.csv)
* [PIM - Add Employee Test Cases](OrangeHRM%20Manual%20Testing%20Project%20-%20PIM-%20Add%20Employee%20%281%29.csv)
* [PIM - Employee List & Search Test Cases](OrangeHRM%20Manual%20Testing%20Project%20-%20PIM%20-%20Employee%20List.csv)
* [PIM - Reports Test Cases](OrangeHRM%20Manual%20Testing%20Project%20-%20PIM%20-%20Reports.csv)

### 2️⃣ Bug Reports
Detailed defect reports documented with clear steps to reproduce, actual vs. expected results, severity, and environment.
* [Click Here to View the Bug Report File](OrangeHRM%20Manual%20Testing%20Project%20-%20Bug%20Report.csv)

### 3️⃣ Test Execution Summary
A high-level dashboard combining key metrics, execution ratios, pass/fail statistics, and bug severity tracking.
* [Click Here to View the Test Summary Report File](OrangeHRM%20Manual%20Testing%20Project%20-%20Test%20Summary%20Report.csv)

---


## 📂 Repository Structure

```text
OrangeHRM-Manual-Testing-Project
│
├── Test Cases
│   ├── Authentication_Login_Logout.csv
│   ├── Forgot_Password.csv
│   ├── PIM_Add_Employee.csv
│   ├── PIM_Employee_List.csv
│   └── PIM_Reports.csv
│
├── Bug Reports
│   └── Bug_Report.csv
│
├── Test Summary Report
│   └── Test_Summary_Report.csv
│
└── README.md
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
