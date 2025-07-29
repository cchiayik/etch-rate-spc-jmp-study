# etch-rate-spc-jmp-study
As GitHub unable to render large file, readers are advised to download the PDF report, sorry for any inconveniences caused.
`Etch_Rate_Case_Study_Report.pdf`  report download [click here](https://github.com/cchiayik/etch-rate-spc-jmp-study/raw/e29e534266b0b4f19dacc533ff7cdf34b3fff8ee/Etch%20Rate%20Case%20Study(Chew%20Chia%20Yik).pdf)

# 📊 Etch Rate SPC Case Study – Semiconductor Manufacturing

**Author:** Chew Chia Yik  
**Date:** July 2025  
**Tools Used:** JMP by SAS | Microsoft Excel  
**Contact:** ccyik0205@gmail.com

---

## 🎯 Project Objective

This case study applies Statistical Process Control (SPC) techniques to assess the stability and performance of semiconductor etching processes. Using data from multiple etch lines, the analysis identifies sources of process variation and evaluates the feasibility of process capability studies using JMP.

---

## 🧰 Tools & Files

| File Name                  | Description |
|---------------------------|-------------|
| `Etch_Rate_Case_Study_Report.pdf` | Full technical report summarizing findings, charts, and recommendations |
| `Etch_Rate_Data.xlsx`     | Raw and cleaned etch rate data from multiple etching lines |
| `Etch_Rate_Analysis.jmp`  | JMP project file containing statistical analysis, histograms, control charts, and 2-tailed tests |
| `README.md`               | This readme document |


---

## 🔍 Key Findings

- **All etching lines (B, C, D) failed stability checks** due to special cause variation.
- Control charts (X-bar and S) showed inconsistent within-wafer and between-run behavior.
- Mean etch rates fell below the target value of 620 Å/min for all lines.
- **Etch Rate C** showed significant improvement after recalibration but remained unstable overall.
- **Process capability study was deemed infeasible** due to statistical instability.
- **Recommendations include** implementing real-time SPC, root cause analysis, Gage R&R, and DOE.

---

## 📂 How to Use

### 1. **Open Excel File**
- Open `Etch_Rate_Data.xlsx` in Microsoft Excel to review raw etch rate values and calibration groupings.

### 2. **Open JMP File**
- Open `Etch_Rate_Analysis.jmp` using **JMP Pro (version 16 or higher)**.
- Navigate through:
  - **Histograms** and **Boxplots** for Line B, C, D
  - **Control Charts** under Graph Builder or Control Chart platform
  - **T-tests and CIs** under Distribution or Fit Y by X tools

> If prompted for data linking, use the `.xlsx` file located in the same folder.

---

## 📝 Reference

Potcner, K. (2025). *JMP064: Variation in Semiconductor Etching Process*. SAS Institute.  
[Access the case study here](https://www.jmp.com/en/academic/case-study-library/variation-in-semiconductor-etching-process.html)

---

For questions or collaboration inquiries, feel free to reach out via email:  
📧 **ccyik0205@gmail.com**

