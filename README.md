# Data-Driven Course Design: Forecasting Graduate Course Enrollment Patterns

This project was originally developed as part of INFO-698 Capstone.  
Now maintained by Sindhu Goshika to showcase graduate-level course data analysis, visualization, and modeling.

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)


## 🧠 Project Goals

- Visualize course enrollment trends across formats, durations, and schedules.
- Identify bottleneck courses using a custom Course Bottleneck Index (CBI).
- Offer actionable recommendations for course scheduling.
- Build a Power BI dashboard for interactive exploration.

---

## 🔍 Methods & Tools

- **Languages:** Python (Pandas, Matplotlib, Seaborn), Power BI
- **Techniques:** Trend analysis, fill-rate calculations, custom bottleneck metrics
- **Dashboard Features:** DR, OFS, IAS, PCS + filtering by course and term

---

## 📊 Key Results

- Midday and afternoon slots dominate course schedules.
- TR (Tuesday/Thursday) is the most frequently used schedule.
- Online courses maintain high enrollment overall; in-person peaks in Fall terms.
- No major bottlenecks found, but some slots (TR afternoons) may lead to overlap.
- Dashboard allows dynamic exploration of enrollment patterns.

---

## 🚧 Limitations

- Dataset size limited to ~88 graduate-level courses.
- Many courses are newly introduced, affecting trend consistency.
- Predictive modeling was not feasible due to insufficient historical depth.

---

## 🔮 Future Enhancements

- Expand dataset with more terms and more courses.
- Introduce real-time data pipelines and API integrations.
- Develop predictive models once sufficient data is available.
- Enhancing the CBI model with factors like student satisfaction, course outcomes, or feedback.

---

## 👩‍💻 Team

- [Sindhu Goshika](https://github.com/sindhugoshika)
- [Ram Teja Vangari](https://github.com/Ramtejavangari)

Supervised by **Professor Sean Kramer-Lazar** 

Guided by **Professor Greg Chism**

INFO 698 – College of Information Science, University of Arizona (Spring 2025)

---

## 🔗 Dashboard Screenshort

- 📊 *Dashboard file : Graduate Course Analysis Dashboard

  
![image](https://github.com/user-attachments/assets/5a8dcda6-fe23-46b1-bc6d-bdca74218a66)



--- 

## 📁 Repository Structure
<pre> ```
grad-census-modeling/
│
├── analysis/ # Core analysis components
│ ├── logs/ # Progress logs 
│ │ └── log.md
│ │
│ ├── data/ # All data-related folders
│ │ ├── rawData/ # Original enrollment data provided
│ │ └── derivedData/ # Processed/cleaned data for analysis
│
├── src/ # Scripts for data processing & analysis
│ └── script.* # Scripts to wrangle data, generate figures, compute metrics
│
├── dashboard/ # Power BI dashboard and screenshots
│
├── Executive_Summary.pdf # Final summary and key project insights
│
└── README.md # Project documentation (this file)
    ``` </pre>

        



