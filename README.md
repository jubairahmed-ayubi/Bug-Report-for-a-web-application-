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

1) Summary  
2) Where the report is  
3) How to reproduce & use the spreadsheet  
4) Severity definitions  
5) How to Contribute   ✅ (new, paste my table + code block here)  
6) Issue Template  
7) Suggested Labels & Triage Checklist  
8) Quick Links / Contact  ✅ (new, paste my table here)  

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
---

## 5) How to Contribute

You can contribute either through the **GitHub Web Interface** or via the **Git CLI**.

### 📌 Option A — GitHub Web

| Step | Action |
|------|--------|
| 1 | Go to your repository on GitHub |
| 2 | Click **Add file → Upload files** |
| 3 | Drag & drop the updated `Bug_Report.xlsx` or edit `README.md` |
| 4 | Add a commit message and click **Commit changes** |

---

### 📌 Option B — Git CLI

      ```bash
      # 1. Clone the repository
      git clone https://github.com/jubairahmed-ayubi/Bug-Report-for-a-web-application-.git
      cd Bug-Report-for-a-web-application-
      
      # 2. Create a new branch
      git checkout -b docs/bug-report
      
      # 3. Add new/updated files
      git add Bug_Report.xlsx README.md
      
      # 4. Commit changes
      git commit -m "Update bug report and README"
      
      # 5. Push branch & open PR
       git push -u origin docs/bug-report

| Resource           | Link                                                                                           |
| ------------------ | ---------------------------------------------------------------------------------------------- |
| **Test site**      | [https://with-bugs.practicesoftwaretesting.com](https://with-bugs.practicesoftwaretesting.com) |
| **Author / QA**    | Jubair Ahmed                                                                                   |
| **GitHub Profile** | [https://github.com/jubairahmed-ayubi](https://github.com/jubairahmed-ayubi)                   |
  ---

