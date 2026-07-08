# United Airlines Network Planning Analytics Project

**A data-driven route performance analysis and schedule optimization recommendation for United Airlines.**

This project was built as part of an application for the **Associate Analyst – Network Planning & Analytics** role at United Airlines (Gurugram, India). It demonstrates the ability to analyze operational performance, diagnose delay root causes, and propose schedule changes that improve on-time performance and margins — all core responsibilities of the role.

---

## 📊 Project Overview

**Objective:** Identify a high-impact operational issue on United’s network and recommend a data-backed scheduling change.

**Methodology:**
- Extracted 40,873 United Airlines mainline flights from the US DOT On-Time Performance dataset (2015).
- Aggregated flight-level data to route-level KPIs (flights, cancellation rate, delay minutes).
- Diagnosed delay causes using the breakdown (Air System, Security, Airline, Late Aircraft, Weather).
- Simulated a 10-minute block time buffer on the worst-performing route (SFO → ORD).
- Calculated on-time performance improvement from 42% → 63% and a total delay reduction of 206 minutes.

**Key Insight:** Airline-controllable delays (Airline + Late Aircraft) accounted for >85% of delays on SFO → ORD, not weather. A small schedule adjustment yields significant reliability gains.

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `index.html` | Interactive, United-branded executive report with charts, tables, and the buffer simulation. |
| `UA_Network_Analysis.ipynb` | Python analysis notebook (Pandas) with all data processing, aggregation, and simulation code. |
| `United_Network_Planning_Presentation.pdf` | A polished slide deck summarizing findings for leadership (created with LLM assistance). |
| `README.md` | This file. |

---

## 🛠️ Tools & Skills Demonstrated

- **Python** (Pandas) for data cleaning, grouping, and simulation.
- **Operational analytics**: delay root cause analysis, KPI calculation, schedule buffer modeling.
- **Data visualization**: stacked bar chart (Chart.js), route performance tables.
- **Executive communication**: structured narrative, before/after comparisons, actionable recommendation.
- **Branded reporting**: United Airlines visual identity applied to a standalone HTML report.
- **GitHub Pages**: live deployment of the interactive report.

---

## 🔗 Live Links

- **Interactive Report:** [https://gauravchauhan18215-cmyk.github.io/ua-network-analysis/](https://gauravchauhan18215-cmyk.github.io/ua-network-analysis/)
- **View Notebook:** [UA_Network_Analysis.ipynb](./UA_Network_Analysis.ipynb)
- **Download PDF Slides:** [United_Network_Planning_Presentation.pdf](./United_Network_Planning_Presentation.pdf)

---

## 🎯 Relevance to the Job

This project directly mirrors the responsibilities listed in the United Airlines job description:
- Analyze operational/commercial performance and recommend improvements.
- Help develop strategic plans to maximize margin potential.
- Create presentations for United leadership.
- Proactively experiment with new tools and data-driven methods.

---

## 👤 Author

**Gaurav Chauhan**  
*Application for Associate Analyst – Network Planning & Analytics*  
08-07-2026

---

*This project was completed independently using publicly available US DOT data. United Airlines branding is used solely for demonstration purposes.*
