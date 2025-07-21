# 🪐 Kepler Exoplanet Dashboard (Power BI)

This Power BI project explores the **Kepler mission dataset**, visualizing key metrics and insights from over 10,000 stars observed for exoplanet activity.

🔭 **What is this data?**  
The Kepler mission measured flux (light intensity) from stars. If a star's light dims periodically, it may indicate an orbiting planet. This dashboard helps visualize that behavior.

---

## 📊 Dashboard Overview

### 📄 Page 1: General Statistics
- KPIs: Total Stars, Stars with Exoplanets, Confirmed Systems
- Pie chart of planet vs non-planet stars
- Contextual summary

### 📄 Page 2: Flux & Planet Presence
- Histogram of Flux bins
- % of high flux stars
- Correlation between flux and exoplanet presence

### 📄 Page 3: Exploratory Visuals
- Advanced visuals: Donut chart, slicers, and tooltip-enhanced graphs
- Grouped bar charts with legend and small multiples
- Styled with space-themed aesthetics

---

## 📦 Files

| File | Description |
|------|-------------|
| `.pbix` | The Power BI dashboard |
| `screenshots/` | PNG exports of each page |
| `pdf_export/` | Printable version of the dashboard |
| `docs/` | Measure definitions and dataset notes |

---

## ⚙️ Measures used (DAX)
- `%HighFlux`
- `Total Exoplanet Stars`
- `FluxCategory`
- Others available in `docs/measures_used.md`

---

## 🧠 Author

**Ezequiel Maurig**  
Data Science student, tech entrepreneur & dashboard enthusiast  
📫 ezequiel@email.com (replace with real one)  
🌎 [LinkedIn](https://linkedin.com/in/ezequielmaurig)


