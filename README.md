# 📊 Sales Performance Dashboard — Excel Project

An end-to-end Excel project analysing the sales performance of 141 sales executives across 8 regions in India. Built with formulas, pivot tables, charts, slicers, and VBA macros to deliver a fully interactive dashboard for business decision-making.

---

## 📁 Project Structure

```
sales-performance-dashboard/
│
├── Sales_Performance_Dashboard.xlsm   # Main Excel file
└── README.md                                             # Project documentation
```

---

## 🎯 Project Objective

Analyse daily sales data for 141 sales executives over a 5-day period to identify:

- **Top performing** sales executives by total sales
- **Underperformers** with the lowest total sales
- **Target achievement** percentages across the team
- **Executives furthest from target** who may need support
- **Regional performance** trends across 8 Indian cities

---

## 📊 Dataset Overview

### Sheet 1: RAW DATA — 141 rows, 12 columns

| Column | Description | Source |
|---|---|---|
| `Emp Code` | Unique employee code (e.g., Mum-TCL001) | Input |
| `Sales Executive` | Name of the sales executive | Input |
| `Region` | City assigned | Input |
| `Day1` – `Day5` | Daily sales figures | Input |
| `Total Sales` | Sum of Day1 to Day5 | Formula: `=SUM(D2:H2)` |
| `Target` | Monthly sales target (500 units) | Input |
| `Target Hit %` | Percentage of target achieved | Formula: `=I2/J2` |
| `Away From Target %` | Gap from target | Formula: `=100%-K2` |

**Regions covered:** Mumbai, Delhi, Nagpur, Chennai, Pune, Patna, Ranchi, Surat

### Sheet 2: DASHBOARD
An interactive dashboard built with four coordinated pivot tables, three charts, and a region slicer for filtering.

---

## 🔍 Dashboard Insights

### 🏆 Top 5 Sales Executives (by Total Sales)
| Rank | Sales Executive | Total Sales |
|---|---|---|
| 1 | Anikuttan | 382 |
| 2 | Ritu Bhatnagar | 371 |
| 3 | Rashid | 340 |
| 4 | Bhagwat Singh | 327 |
| 5 | ManjuTiwari Lab | 318 |

### ⚠️ Bottom 5 Sales Executives (Lowest Sales)
| Rank | Sales Executive | Total Sales |
|---|---|---|
| 1 | Jyoti Tulsani | 228 |
| 2 | Sanjiv Subherwal | 223 |
| 3 | Sushma Khandelwal | 213 |
| 4 | Mubeen Khan | 209 |
| 5 | Praveen Kumar | 166 |

### ✅ Top 5 by Target Hit %
| Rank | Sales Executive | Target Hit % |
|---|---|---|
| 1 | Anikuttan | 76.4% |
| 2 | Ritu Bhatnagar | 74.2% |
| 3 | Rashid | 68.0% |
| 4 | Bhagwat Singh | 65.4% |
| 5 | ManjuTiwari Lab | 63.6% |

### 📉 Bottom 5 — Furthest From Target %
| Rank | Sales Executive | Away From Target % |
|---|---|---|
| 1 | Praveen Kumar | 66.8% |
| 2 | Mubeen Khan | 58.2% |
| 3 | Sushma Khandelwal | 57.4% |
| 4 | Sanjiv Subherwal | 55.4% |
| 5 | Jyoti Tulsani | 54.4% |

---

## 🛠️ What's Built Into This Excel File

### Formulas
- `SUM` for calculating daily sales totals per executive
- Percentage formula `=I2/J2` for Target Hit %
- `=100%-K2` for Away From Target %

### Pivot Tables — 4 Total
- **Pivot 1** → Top 5 Sales Executives by Total Sales
- **Pivot 2** → Bottom 5 Sales Executives by Total Sales
- **Pivot 3** → Top 5 by Target Hit %
- **Pivot 4** → Bottom 5 by Away From Target %

### Charts — 3 Total
Visual representations of the pivot table data for quick insight consumption.

### Slicer
- **Region Slicer** — interactive filter allowing users to drill down by city (Mumbai, Delhi, Nagpur, Chennai, Pune, Patna, Ranchi, Surat)

### VBA Macros
Macros embedded in the workbook to automate dashboard refresh and interaction.

### Dashboard Design
Clean four-panel layout with all key views visible on a single screen for quick decision-making.

---

## 💡 Excel Skills Demonstrated

| Skill | Application |
|---|---|
| **Formulas** | `SUM`, percentage calculations for Total Sales, Target Hit %, Away From Target % |
| **Pivot Tables** | Four coordinated pivots summarising sales performance |
| **Charts** | Three charts visualising top and bottom performers |
| **Slicers** | Interactive region filter connecting multiple pivots |
| **VBA Macros** | Automation for refreshing and updating the dashboard |
| **Dashboard Design** | Multi-panel layout for at-a-glance insights |
| **Data Modelling** | Raw data sheet structured to feed all dashboard components |

---

## 💼 Business Value

This dashboard enables sales managers to:

- Quickly identify **star performers** for recognition and rewards
- Spot **underperformers** who may need coaching or support
- Monitor **target achievement** across the team at a glance
- **Filter by region** to drill down into specific city performance
- Make **data-driven decisions** on resource allocation and training needs

---

## 🚀 How to Use

1. Download the `.xlsm` file
2. Open in Microsoft Excel (with macros enabled)
3. Navigate to the **DASHBOARD** sheet for the summary view
4. Use the **Region slicer** to filter by city
5. View the **RAW DATA** sheet to see the underlying dataset

> ⚠️ This is a macro-enabled workbook (.xlsm). Make sure macros are enabled for full functionality.
