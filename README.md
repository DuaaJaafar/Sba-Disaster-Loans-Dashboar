# SBA Disaster Loans Overview — Executive Tableau Dashboard

An executive, high-contrast, interactive Business Intelligence dashboard analyzing the U.S. Small Business Administration (SBA) Disaster Loans dataset. The dashboard provides critical insights into total verified losses, approved loan amounts, and disaster relief coverage across affected states and cities.

---

## 📊 Live Interactive Dashboard
👉 *[View the Live Dashboard on Tableau Public](ttps://public.tableau.com)*

---

## 📸 Dashboard Preview
![Dashboard Preview](<Dashboard 1 (2).png>)

---

## 🎯 Business Problem & Objectives
Following major natural disasters, federal and state decision-makers require immediate visibility into:
1. The scale of property and commercial damage (Total Verified Loss).
2. The extent of financial support deployed (Total Approved Loans).
3. The overall relief coverage percentage to allocate further emergency funding.

---

## 📈 Key Metrics & Insights
* *Total Verified Loss:* $522.0M across impacted regions.
* *Total Approved Loans:* $103.4M disbursed in assistance.
* *Relief Coverage Rate:* 19.8% recovery coverage.
* *Geographic Distribution:* Heavy concentrations of verified losses were observed in specific coastal and storm-affected cities (e.g., Fort Myers Beach, Sanibel, Mayfield).

---

## 🛠️ Dashboard Architecture & Design Choices
* *Visual Hierarchy:* Card-based KPI layouts with clean borders and padding for executive-level scanning.
* *Palette:* Minimalist light aesthetic utilizing high-contrast Deep Plum (#581845) and Warm Amber (#B6894E) for clean visual differentiation.
* *Interactivity:*
  * Interactive cross-filtering enabled across map and bar charts.
  * Viz-in-Tooltip integration for granular drill-downs into localized city damage.
  * De-cluttered charts with unnecessary headers and zero-lines removed for optimal UX.

---

## 📁 Repository Structure
```text
├── DASH BOARD.twbx         # Packaged Tableau Workbook
├── Dashboard 1 (1).png     # High-resolution dashboard preview
└── README.md               # Executive project documentation
