# qa-ecommerce-testing-project
Manual and API testing project for an e-commerce application including test cases, execution reports, bug tracking in Jira and API testing using Postman.

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

