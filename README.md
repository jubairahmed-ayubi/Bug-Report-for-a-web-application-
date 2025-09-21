# Bug-Report-for-a-web-application-
# Bug Report — https://with-bugs.practicesoftwaretesting.com

Consolidated bug report and contribution guide for the test site [https://with-bugs.practicesoftwaretesting.com](https://with-bugs.practicesoftwaretesting.com/).

This repository contains:  
- The Excel bug report (`Bug_Report.xlsx`) created by **Jubair Ahmed**  
- Guidance for reproducing bugs, triaging, and contributing  
- An issue template for GitHub  
- Suggested labels and a triage checklist  

---

## Table of Contents

1. [Summary](#summary)  
2. [Where the Report Is](#where-the-report-is)  
3. [How to Reproduce & Use the Spreadsheet](#how-to-reproduce--use-the-spreadsheet)  
4. [Severity Definitions](#severity-definitions)  
5. [How to Contribute](#how-to-contribute)  
6. [Issue Template](#issue-template)  
7. [Suggested Labels & Triage Checklist](#suggested-labels--triage-checklist)  
8. [Quick Links / Contact](#quick-links--contact)  

---

## 1) Summary

- **Report file:** `Bug_Report.xlsx` (root of the repository)  
- **Author:** Jubair Ahmed  
- **Bug count:** 10 (across modules: Cart, UI, Category/Rental, Validation, Registration, Navigation)  
- **Columns in spreadsheet:** Bug ID, Module / Area, Bug Title, Steps to Reproduce, Expected Result, Actual Result, Severity, Created QA  

---

## 2) Where the Report Is

The Excel file is stored in this repository and is also available via SharePoint:  
[Download Bug Report (Excel)](https://mistedu-my.sharepoint.com/:x:/g/personal/202014018_student_mist_ac_bd/EQA_m_ADAf1Ou7XYkCuuoxMBJIqzNsZ6njjQweKa_GkCng?e=wHl1EK)


---

## 3) How to Reproduce & Use the Spreadsheet

Before reproducing bugs, collect environment data:  

- **Browser & version:** e.g., Chrome 117, Firefox 119  
- **OS:** Windows/macOS/Linux/Android/iOS  
- **Device type:** Desktop/Mobile  
- **Environment:** staging / production / local  

Use the **Steps to Reproduce** column in the spreadsheet for step-by-step verification.  

When you confirm a bug:  
1. Create a GitHub Issue using the template below  
2. Attach relevant screenshots  
3. Set the **Severity** label  

---

## 4) Severity Definitions

| Severity  | Description |
|-----------|-------------|
| **Critical** | Site or essential flow broken for all users (e.g., checkout failing, data loss, security/privacy hole) |
| **High** | Major functionality broken for many users (e.g., cannot remove items from cart, out-of-stock items purchasable, registration accepts invalid data) |
| **Medium** | Important but non-blocking functionality (e.g., quantity resets, back-button shows removed items) |
| **Low** | Cosmetic or content issues (e.g., spelling mistakes, minor UI irregularities) |

Use these definitions consistently when triaging bugs.  
## 5) How to Contribute

### Using GitHub Web
1. Go to repo → **Add file → Upload files**.  
2. Drag & drop updated `Bug_Report.xlsx` or edit `README.md`.  
3. Commit changes.  

### Using Git CLI
```bash
# clone
git clone https://github.com/jubairahmed-ayubi/Bug-Report-for-a-web-application-.git
cd Bug-Report-for-a-web-application-

# create branch
git checkout -b docs/bug-report

# add new/updated files
git add Bug_Report.xlsx README.md

# commit
git commit -m "Update bug report and README"

# push & open PR
git push -u origin docs/bug-report
---
---

## 8) Quick Links / Contact

- **Test site:** [https://with-bugs.practicesoftwaretesting.com](https://with-bugs.practicesoftwaretesting.com)  
- **Author / QA:** Jubair Ahmed  
- **GitHub profile:** [https://github.com/jubairahmed-ayubi](https://github.com/jubairahmed-ayubi)


