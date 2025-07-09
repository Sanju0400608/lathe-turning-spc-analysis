# ⚙️ Lathe Turning SPC Analysis – MEEM 5650 Workshop 2

**📚 Course:** MEEM 5650 – Advanced Quality Engineering  
**👨‍🏫 Instructor:** Dr. Radheshyam Tewari  
**👥 Team Members:** Atharva Kanetkar | Sanjiv Suresh | Preet Harer  
**📅 Date Submitted:** December 11, 2024

---

## 📌 Project Overview
This project investigates a **lathe-turning process for bronze bushings** using TURNSIM and Minitab to apply **Statistical Process Control (SPC)**. The objective was to identify and eliminate **special causes of variation**, analyze **control chart signals**, and evaluate **process capability**.

---

## 🔬 Methodology

### 🧾 Data Collection
- Generated 40 samples from TURNSIM simulation.
- Surface Roughness Spec: **70 ± 15 µin**  
- Diameter Spec: **2.250 ± 0.002 in**

### 📉 Control Chart Analysis
- Created **X̄ (mean)** and **R (range)** charts in Minitab.
- Violations at Sample 20 (above UCL) & Sample 38 (below LCL).
- High variation at Samples 10 & 15 on R chart.

### 📊 Special Cause Investigation
Analyzed 10 potential special causes:  
Cutting Speed, Feed Rate, Setup Person, Operator, Tool Type, Tool Condition, Depth-to-Shoulder, Machine, Measuring Device, Rake Angle.  
Confirmed causes:
- ✅ Operator Variability  
- ✅ Tool Condition (Sharp vs. Dull)  
- ✅ Machine Instability (Rex)

---

## 📈 Process Capability Analysis

| Metric         | Value | Interpretation                                |
|----------------|-------|-----------------------------------------------|
| Cp             | 0.50  | Poor spread – variation too wide              |
| Cpk            | 0.42  | Process not centered                          |
| Out-of-Spec %  | 14.69%| High number of parts outside spec             |

---

## 🛠️ Recommendations
- Apply **Pareto**, **Fishbone**, **FMEA**, and **FTA**.
- Conduct tool maintenance and operator retraining.
- Standardize machine calibration routines.

---

## 🎯 Key Learnings
- Real-world linkage between charts and causes.
- Scatter plots confirmed SPC signals.
- Hands-on control over variation using SPC tools.

---

## 📂 Repo Contents
- `Workshop_2_5650Final_Team_1.pdf` – Final report
- `data/` – Raw measurements
- `charts/` – Control charts & scatter plots

---

## 🙏 Acknowledgments
Thanks to **Dr. Radheshyam Tewari** for guidance throughout the workshop.

> 📬 Questions or collab? Connect with [Sanjiv Suresh](https://www.linkedin.com/in/sanjivsuresh)

---

### 🔗 Tags
`#SPC` `#Minitab` `#QualityEngineering` `#LatheTurning` `#MEEM5650` `#Manufacturing`
