
# Task 3:  Perform a Basic Vulnerability Scan on Your PC.

This repository documents the process and results of a basic network vulnerability scan conducted using **Tenable Nessus**.

---

## Objective: Use free tools to identify common vulnerabilities on your computer.


## 📸 Scan Workflow (Screenshots)

1. **Scan In Progress**
   - ![Scan In Progress](./scan-in-progress.png)
   - The scan was initiated and shows active host discovery and plugin enumeration.

2. **Scan Completed**
   - ![Scan Completed](./scan-completed.png)
   - The scan completed successfully with full coverage of the target system(s).

3. **Top Vulnerabilities**
   - ![Top Vulnerabilities](./top-vulnerabilities.png)
   - This screen shows an overview of detected vulnerabilities by severity and frequency.

4. **CVE Details**
   - ![CVE Details](./cve-details.png)
   - Detailed CVE view, including associated plugins and risk factors.

---

## 🧾 Report Summary

- The complete vulnerability report has been exported from Nessus as a `.nessus` file and converted to a human-readable PDF.
- 📄 View the report here: [report.pdf](./report.pdf)

---

## 🔍 Findings

- All identified findings were **informational** in nature.
- No high or critical vulnerabilities were detected.
- Common informational plugins included software inventory, OS identification, and system patch state.

---

## 🛠️ Tools Used

- **Tenable Nessus Essentials**
- **PDF Generator** via script to transform `.nessus` into `.pdf`
- **Screenshots** taken during each phase for documentation

---

## 🔐 Notes

- No sensitive credentials, passwords, or personal data are included in this documentation.
- Internal IPs may appear in the report but pose no external risk.

