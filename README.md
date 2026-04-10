# FUTURE_CS_03
API Security Risk Analysis – Testing public APIs for vulnerabilities like authentication flaws, data exposure, and security risks.
# 🔐 API Security Risk Analysis Project

## 📌 Overview

This project demonstrates a **read-only API Security Risk Assessment** performed on a public test API. The goal is to identify common API security issues and provide professional remediation recommendations.

---

## 🎯 Objectives

* Analyze API endpoints
* Identify security vulnerabilities
* Assess authentication and authorization
* Classify risks by severity
* Suggest mitigation strategies

---

## 🌐 Target API

* **Name:** JSONPlaceholder
* **URL:** https://jsonplaceholder.typicode.com
* **Type:** Public Test API

---

## 🛠️ Tools Used

* Kali Linux
* curl / httpie
* Browser Developer Tools

---

## 🔍 Methodology

1. Reviewed API documentation
2. Tested endpoints using GET requests
3. Inspected headers and responses
4. Analyzed authentication mechanisms
5. Identified security risks
6. Classified severity
7. Suggested remediation

---

## 🚨 Key Findings

### 🔴 No Authentication

* API accessible without login or token
* Risk: Unauthorized access

### 🟠 Excessive Data Exposure

* Sensitive user data returned
* Risk: Privacy leakage

### 🔴 No Rate Limiting

* Unlimited API requests allowed
* Risk: API abuse / DoS

### 🔴 Authorization Issues

* Access to other users’ data
* Risk: Privilege escalation

### 🟡 Missing Security Headers

* Lack of protective headers
* Risk: Increased attack surface

---

## 📊 Severity Summary

| Vulnerability        | Severity   |
| -------------------- | ---------- |
| No Authentication    | HIGH       |
| Data Exposure        | MEDIUM     |
| No Rate Limiting     | HIGH       |
| Authorization Issues | HIGH       |
| Missing Headers      | LOW–MEDIUM |

---

## 🛠️ Recommendations

* Implement JWT / OAuth authentication
* Apply role-based access control (RBAC)
* Add rate limiting and throttling
* Filter sensitive data in responses
* Configure HTTP security headers

---

## 📄 Report

Detailed report available in:
👉 `API_Security_Report.pdf`

---

## ⚠️ Disclaimer

This project was conducted for **educational purposes only** using a public test API.
No real systems were harmed or exploited.

---

## 👤 Author

**Mohammed Sinan**
Cyber Security Intern

---

## ⭐ Acknowledgment

Based on best practices from **OWASP API Security Top 10**
