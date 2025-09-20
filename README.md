📋 Test Summary Report – BD Jobs (Manual Testing)

**Project/Module Name:** BD Jobs
**Test Type:** Manual Testing
**Prepared By:** Rezwanul Rimel
**Date of Creation:** 18-09-2025
**Date of Review:** 21-09-2025

---

## 🎯 Objective

The goal of this testing cycle was to validate the key workflows of the BD Jobs portal. I focused on making sure that features like registration, login, profile updates, job search, and applications work as expected. I also checked UI/UX consistency, security vulnerabilities, browser compatibility, and notifications.

---

## 🖼 Scope

**In Scope:**

* Registration, Login, Profile management
* Job search (by keyword, location, company, and filters)
* Job application (apply, withdraw)
* UI/UX checks: responsiveness, alignment, fonts, broken links
* Security testing: SQL Injection, XSS, Session Timeout
* Compatibility testing on Chrome, Firefox, Safari, Edge
* Notifications (job alerts, success messages)
* Misc features: Terms & Conditions, Contact Us, Language switch

**Out of Scope:**

* API Testing
* Payment/Subscription modules

---

## 🛠 Test Environment

* **Browsers:** Chrome, Firefox, Safari, Edge
* **Devices:** Desktop, Mobile, Tablet
* **Test Data:** Valid/Invalid user credentials, CV files (PDF/DOCX/Invalid), job postings, emails

---

## 📊 Test Execution Summary

| Status           | Count |
| ---------------- | ----- |
| Total Test Cases | 42    |
| ✅ Passed         | 38    |
| ❌ Failed         | 4     |
| 🚫 Blocked/NA    | 0     |

**Pass Rate:** 90.5%

---

## 🔎 Failed Test Cases

| TC ID | Module     | Issue Observed                                          |
| ----- | ---------- | ------------------------------------------------------- |
| 18    | Job Search | Searching by company also showed unrelated jobs         |
| 19    | Job Search | Blank keyword displayed all jobs instead of restricting |
| 24    | Job Apply  | Withdraw application option missing (no button)         |
| 31    | Security   | Session timeout didn’t log out the user after 30 mins   |

---

## 🐞 Defect Summary

* **Total Defects:** 4
* **Severity Breakdown:**

  * High: 2 (Job Search inaccuracy, Session timeout issue)
  * Medium: 1 (Withdraw button missing)
  * Low: 1 (Blank keyword search)
