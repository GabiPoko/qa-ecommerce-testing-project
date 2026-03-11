# qa-ecommerce-testing-project
Manual and API testing project for an e-commerce application including test cases, execution reports, bug tracking in Jira and API testing using Postman.
---------------------------

# E-commerce QA Testing Project

## Project Overview

This project demonstrates a complete QA testing process for a sample E-commerce application.  
The objective was to simulate the work of a QA engineer by creating a full testing workflow including test planning, test case design, execution, bug reporting, and API testing.

The application tested includes key modules such as Login, Cart, Checkout, and API endpoints.

---

# Testing Scope

The following modules were tested:

- Login functionality
- Cart behavior
- Checkout process
- Product API endpoints

Testing included both **positive and negative scenarios** to validate application behavior under different conditions.

---

# Testing Types Performed

- Manual Testing
- Functional Testing
- Negative Testing
- API Testing
- Bug Reporting

---

# Tools Used

- Postman (API Testing)
- Jira (Bug Tracking)
- Google Sheets / Excel (Test Cases & Execution Reports)
- GitHub (Project Documentation & Version Control)

---

# Project Structure
QA-Ecommerce-Testing-Project
│
├── Test-Plan
├── Test-Cases
├── Test-Execution-Report
├── Bug-Reports
├── Evidence
├── API-Testing
└── Test-Summary-Report

---------------------------

# Test Artifacts

This repository includes the following QA artifacts:

**Test Plan**
- Defines testing scope, strategy, objectives, and environments.

**Test Cases**
- Detailed scenarios designed to validate application functionality.

**Test Execution Report**
- Execution results including Pass / Fail status.

**Bug Reports**
- Defects documented and tracked using Jira.

**API Testing**
- Postman collection used to validate API endpoints.

**Evidence**
- Screenshots showing bug reproduction and validation.

**Test Summary Report**
- Final report summarizing testing results and findings.

---

# Key Bugs Identified

Some of the defects discovered during testing include:

- Cart total displaying incorrect decimal precision
- Checkout allowed with empty cart
- Checkout form accepting invalid data formats
- Cancel button redirecting to incorrect page
- Session remaining active after inactivity
- API returning status 200 for non-existing product ID

---

# API Testing

API testing was performed using Postman to validate product endpoints.

Example scenario tested:

GET Product by ID

Expected behavior:
- Valid ID → Status 200 with product data
- Invalid ID → Error response

Observed issue:
The API returned **status 200 with empty response** when requesting a non-existing product ID.

---

# Author

Gabriel Pokorasky  
QA Tester (Manual & Automation learning path)

Background:
- 13+ years of professional experience as a Biology teacher
- Strong analytical, communication, and problem-solving skills
- Currently transitioning into Software Quality Assurance

Technical skills currently being developed:

- Manual Testing
- Selenium Automation
- API Testing (Postman / RestAssured)
- Test Design
- Bug Reporting
- Git & GitHub

