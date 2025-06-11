# 🚚 Supply Chain Optimization – IP

A supply chain analytics and optimization project for AgReliant Genetics, aimed at reducing costs and delivery complexity through advanced modeling.

---

## 📌 Problem Statement

Inefficiencies in shipment consolidation, warehouse mapping, and frequent intercompany transfers increased costs and complexity for AgReliant Genetics.

---

## 🎯 Objective

Use analytics and optimization to **reduce excess shipments, minimize transfers, and optimize warehouse-to-customer assignments** for operational efficiency.

---

## 🗂️ Dataset Overview

- Five years of shipment, inventory, transfer, and production data
- Customer and warehouse geographic information

---

## 🧹 Data Engineering

- Cleaned, standardized, and engineered features (e.g., beginning inventory, forecasted demand, cohort segmentation)
- Calculated KPIs: Excess shipment %, retention rate, transfer ratios

---

## 🧠 Analytics & Optimization

- Analyzed root causes of shipment fragmentation and transfer dependence
- Forecasted inventory shortfalls using EWMA
- Built a **two-stage stochastic linear programming model** (Python/PuLP) for optimal warehouse assignments

---

## 📈 Results

- **54% reduction** in intercompany transfers for eligible products
- **3% decrease** in total delivery distance; improved truck utilization
- Customer retention insights driven by improved shipment consolidation

---

## 🧪 Libraries Used

- `pandas`, `numpy`, `PuLP` (linear programming), `matplotlib`, `seaborn`
- Tableau (visualization)

---

## 🧠 Key Learnings

- Analytics and mathematical modeling can unlock significant supply chain savings
- Shipment consolidation and safety stock optimization drive retention and efficiency
- Stochastic modeling is valuable for real-world supply chain uncertainty

---

## 🚀 Future Work

- Integrate with real-time ERP and warehouse data feeds
- Extend optimization to production planning and last-mile delivery
- Live Tableau dashboard deployment for supply chain managers

---

## 🤝 Acknowledgements

- AgReliant Genetics (case dataset)
- PuLP and Tableau documentation

---

## 🚚 Example Dashboard

> Coming soon: Interactive Tableau dashboard demo for warehouse assignment and transfer planning.
