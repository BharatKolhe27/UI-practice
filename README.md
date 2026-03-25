# Manufacturing Dashboard UI (Practice Project)

A modern **dashboard UI built with React + TypeScript + Material UI**, focused on replicating real-world industrial analytics dashboards with charts, metrics, and data visualization.

---

## Overview

This project is a **UI-focused practice implementation** of a manufacturing analytics dashboard.

It includes:

*  Production tracking
*  Testing insights
* failure analysis
* Data visualization using charts

 This project uses **dummy data** and is intended for **UI/UX practice and component architecture learning**.

---

## 🛠️ Tech Stack

* **React**
* **TypeScript**
* **Material UI (MUI)**
* **Recharts** (for charts)
* **CSS-in-JS (MUI sx)**

---

## 📊 Dashboard Sections

### 🔹 1. Summary Cards

* Displays key metrics:

  * Active Production Orders
  * Orders in Assembly
  * Orders in Testing
  * Failed / Blocked
* Fully interactive (click + hover + active state)

---

### 🔹 2. Production Chart

* Bar chart showing:

  * Assembly vs Testing distribution
* Styled with:

  * Thin bars
  * Top-rounded edges
  * Custom tooltip

---

### 🔹 3. Cycle Time Chart

* Line chart showing trends over months
* Multiple breaker types:

  * 38kV
  * 72.5kV
  * 145kV

---

### 🔹 4. Man Hours Chart

* Stacked bar chart
* Monthly labor distribution

---

### 🔹 5. Breaker Quality Overview

* Donut charts showing:

  * Passed vs Failed units
* Includes:

  * Percentages
  * Failure badges

---

### 🔹 6. Failure Table

* Displays:

  * Test name
  * Failed breakers
  * Failure rate
* Clean alignment with UI design

---

## 📂 Project Structure

```id="q1v9tr"
src/
│
├── components/
│   ├── SummaryCard.tsx
│   ├── ChartCard.tsx
│   ├── FailureTable.tsx
│   └── BreakerQualityOverview.tsx
│
├── charts/
│   ├── ProductionBarChart.tsx
│   ├── CycleTimeLineChart.tsx
│   └── ManHoursStackedChart.tsx
│
├── pages/
│   └── Dashboard.tsx
│
├── App.tsx
└── main.tsx
```


