

# 🧪 Manual Testing Project – E-commerce Web Application

## 📌 Project Overview

This project demonstrates end-to-end **manual testing** of an e-commerce web application.
The objective was to validate core business workflows, identify defects, and manage them using industry-standard defect tracking practices.

Website Under Test: [https://automationexercise.com](https://automationexercise.com)

---

## 🎯 Objectives

* Design structured test scenarios and test cases
* Perform functional, negative, and boundary testing
* Identify and classify defects based on severity & priority
* Log and track defects using Jira
* Simulate real-world defect lifecycle management

---

## 🔍 Scope of Testing

### Modules Covered

* User Registration
* User Login
* Product Browsing
* Cart Management
* Checkout & Payment

### Testing Types Performed

* Functional Testing
* Negative Testing
* Boundary Testing
* Security Testing (SQL Injection, Weak Password Validation)
* Regression Testing

---

## 📊 Test Case Summary

* Total Test Cases Designed: **50**
* High Priority Test Cases: 20+
* Critical Business Flows Covered:

  * Authentication
  * Cart total validation
  * Pricing consistency
  * Payment validation
  * Session handling



## 🐞 Defect Summary

* Total Defects Identified: **6**
* Critical Severity: 2
* High Severity: 3
* Medium Severity: 1

### Sample Critical Defects

* SQL Injection login bypass vulnerability
* Payment processed successfully with expired card
* Cart total calculation mismatch

All defects were logged and tracked in **Jira**.

---

## 🔄 Defect Lifecycle Followed

Open → In Progress → Resolved → Retested → Closed

Defect tracking screenshots are available in:

```
/Screenshots
```

---

## 🛠 Tools & Technologies Used

* Jira (Defect Tracking)
* Microsoft Excel (Test Case Management)
* Chrome Browser (Execution Environment)
* Git & GitHub (Version Control)

---

## 📁 Repository Structure

```
ecommerce-manual-testing/
│
├── Detailed_Ecommerce_Manual_Test_Cases_50.xlsx
├── Screenshots/
│     ├── jira_board.png
│     ├── bug_sql_injection.png
│     ├── bug_cart_total.png
│
└── README.md
```

---

## 💡 Key Learnings

* Writing structured and traceable test cases
* Differentiating Severity vs Priority
* Identifying business-impacting defects
* Managing defects using Agile workflow
* Understanding regression suite design

---

## 🚀 Future Enhancements

* Automating regression suite using Selenium
* API testing using Postman
* Performance testing for checkout module

---



* Trim this into a more concise recruiter-focused version
* Or upgrade it to look more “SDET Intern” aligned specifically for Flam.
