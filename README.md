# 🚴 Seoul Public Bicycle Analysis
**Ddareungi August-September 2024 Breakdown Rate Analysis and 2025 Preparedness Strategy**

## ⚡ TL;DR (Quick Summary)

- 📈 **Issue Identified:** Increase in breakdown rate (Notably in 2024, compared to th previous year)
- 🔍 **Root Causes:** Maintenance backlog, extreme heat, and increased usage.
- 🎯 **Solution:** Optimize repair team deployment & create an early warning dashboard.
- 📊 **Expected Impact:** Reduce failures by **15%** through proactive maintenance.

---

## 📌 Project Overview

### **Why This Project?**

Seoul’s public bicycle system (Ddareungi) experiences seasonal fluctuations in breakdown rate**, with a notable difference between August and September.** 

Our goal:
✅ **Identify why September 2024 saw an increase in breakdown rates.**

✅ **Develop data-driven maintenance strategies for summer 2025.**

### **Key Findings**

- 📉 **Breakdown Rate Trends:**
    - 2023: September breakdowns **plummeted**
    - 2024: September breakdowns **increased**
- 🔥 **Extreme heat events led to increased breakdowns.**
- ⚠ **Reactive maintenance strategies were ineffective.**

---

## 🛠 Key Research Questions

1️⃣ **What caused breakdown rates increase in September 2024?**

2️⃣ **How effective was the existing maintenance system?**

3️⃣ **What preventive strategies should be implemented for August 2025?**  

4️⃣ **How can data-driven insights optimize maintenance scheduling?**

---

## 📊 Data Analysis Process

✔ **Monthly breakdown rate comparison (2023 vs. 2024).**

✔ **District-wise breakdown rate mapping (Aug-Sep 2024).**

✔ **Correlation analysis between August & September breakdown rates.**

✔ **Component-level btrakdown analysis based on rental history.**

✔ **Time-based breakdown reporting trends (August 2024).**

---

## 🔎 Findings & Insights

### **1️⃣ Correlation Between August & September Breakdowns**
![2023vs2024](https://github.com/user-attachments/assets/51f45490-3d10-442d-a99c-4906bc60519f)





💡 **Hypothesis:** A higher breakdown rate in August would lead to a lower rate in September.

📊 **Result:** The opposite was true—**higher August failures correlated with higher September failures.**
![image](https://github.com/user-attachments/assets/a5cf107b-085b-437b-bed7-814e9f66f192)



🛠 **Implication:** Maintenance efforts in August were insufficient to reduce failures in September.

### **2️⃣ Impact of Temperature on Breakdown Rates**

🔥 **Hypothesis:** Higher temperatures increase breakdown rates.

📊 **Result:**

| Faulty Components | OCEF (Regression Coefficient) | R-squared | P-value |
| --- | --- | --- | --- |
| Tire | 102.8782 | 0.800 | 0.0000000038 |
| Pedal | 54.2495 | 0.632 | 0.0000035 |
| Terminal Unit | 14.5144 | 0.574 | 0.00002 |
| Chain | 82.9222 | 0.536 | 0.00005 |
| Other | 50.6681 | 0.271 | 0.0091 |
| Saddle | 33.4392 | 0.175 | 0.0419 |

![image](https://github.com/user-attachments/assets/157c508d-e010-45bf-97c7-55a8af16d926)


- 🚴‍♂️ **Component breakdown spiked with rising temperatures.**
- 🌡 **September 2024 saw record-breaking heatwaves & tropical nights.**
- 💡 **Conclusion:** Heat was a major factor in the breakdown surge.

---

## 🚨 Problems in the Current Maintenance System

### **1️⃣ Gaps in the Current Repair Model**

- 🔄 **Existing Repair Process:**
    - User reports  → Bicycle collected → Sent to repair shop → Fixed & redeployed
- ❌ **Issue:**
    - **Too many steps = slow turnaround.**
    - **Overwhelmed repair shops couldn't keep up with rising demand.**

### **2️⃣ Reactive vs. Preventive Maintenance**

- 🔧 **2024’s approach:** Wait for breakdown → Fix them
- 🚀 **Proposed 2025 strategy:** Identify at-risk bikes **before** they break → Fix them **early**

---

## 🚀 Strategy for August 2025: Proactive Breakdown Prevention

### ✅ **Solution 1: Deploy Preventive Maintenance Teams**

🔹 **On-Site Patrols at High-Risk Stations**

- **Instead of waiting for reports, dedicated teams inspect high-risk areas in advance.**

🔹 **Prioritizing High-Failure Districts**

![image](https://github.com/user-attachments/assets/e2928e3b-8efa-4b87-8c59-b06901550f59)


- **Top 3 "Emergency Zones" (Aug 2024 Data):**
    - 🏙 **Seocho-gu, Gangnam-gu, Geumcheon-gu**
- **August 2025 Plan:**
    - Deploy **real-time monitoring teams** in these districts.

🔹 **Component-Specific Pre-Checks**

- **Most common breakdowns (Aug 2024):**
    - 🛞 **Tires:** 3,487 cases
    - 🔗 **Chains:** 3,240 cases
    - 🛠 **Others (brakes, bells, gears):** 2,637 cases
- **August 2025 Plan:**
    - Preventive teams **focus on pre-checking these components** before breakdowns occur.

🔹 **Optimized Repair Shifts Based on Breakdown Timing**

- **Peak breakdown hours:** **18:00 - 21:00 (evening rush hour)**
- **Optimized team scheduling:**
    - ☀ **Morning (05:00 - 10:00)** → Routine inspections & minor repairs
    - 🔧 **Afternoon (12:00 - 18:00)** → Major component replacements
    - 🚨 **Evening (18:00 - 21:00)** → Emergency response teams deployed

---

### ✅ **Solution 2: Real-Time Breakdown Monitoring Dashboard**

📊 **A live dashboard** will support the maintenance team with **real-time decision-making**.

![대시보드 2](https://github.com/user-attachments/assets/0a0ad8d7-8a8a-4249-aefb-a8a1eef6b3b4)


🔹 **Key Dashboard Features:**


- **📉 Monthly breakdown trends** (real-time tracking)
- **📍 High-breakdown vs. low-breakdown districts**
- **🔥 Breakdown ranking system** (Legend / Manner King / Honor Student / Caution / Emergency)
- **🛠 Root cause analysis for top 3 high-breakdown districts**
- **⏰ Breakdown trends by time of day**



---

## 🎯 Expected Impact

✅ **Optimize repair team deployment** for improved efficiency.

✅ **Proactively manage breakdown rates** to ensure smoother operations.

✅ **Enable data-driven decision-making** for long-term sustainability.

---

## 📌 Final Conclusion

- 🔥 **The lack of preventive maintenance in August led to a surge in breakdowns in September.**
- 🚀 **August 2025 must focus on proactive maintenance efforts.**
- ⚙ **Optimizing maintenance team operations will improve breakdown prevention.**
- 📊 **Real-time data insights will help establish a sustainable maintenance strategy.**
