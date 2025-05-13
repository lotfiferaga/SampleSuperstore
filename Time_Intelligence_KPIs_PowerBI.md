
# Time Intelligence Functions & KPIs in Power BI

## 🕒 Time Intelligence Functions

**Time Intelligence functions** in Power BI (DAX - Data Analysis Expressions) allow you to perform calculations based on time-based data. These are essential for analyzing trends over time such as weeks, months, quarters, or years.

### ✅ Common Time Intelligence Functions

| Function | Description |
|----------|-------------|
| `TOTALYTD()` | Calculates Year-To-Date values |
| `TOTALQTD()` | Calculates Quarter-To-Date values |
| `TOTALMTD()` | Calculates Month-To-Date values |
| `SAMEPERIODLASTYEAR()` | Compares current period to the same period last year |
| `DATEADD()` | Shifts dates forward or backward (e.g., +1 year, -1 month) |
| `PARALLELPERIOD()` | Gets parallel period in previous or next time interval |
| `PREVIOUSMONTH()` / `PREVIOUSYEAR()` | Returns values from the previous period |
| `DATESYTD()` | Returns a set of dates from the start of the year to the current context |

> 🔸 **Note:** To use these functions properly, ensure you have a **Date Table** marked as a Date Table in Power BI.

---

## 📊 KPI (Key Performance Indicator) in Power BI

A **KPI visual** is used to **measure performance** against a **target** over time. It provides a quick visual cue about the state of a metric.

### ✅ KPI Components:
1. **Indicator**: The current value (e.g., total sales).
2. **Target**: The goal or benchmark (e.g., sales target).
3. **Trend Axis**: A time-based field (e.g., date or month).

### ✅ Example:
- **Indicator**: Actual Revenue
- **Target**: Budgeted Revenue
- **Trend Axis**: Month

The KPI visual will display:
- Current revenue
- Comparison with the target
- A trend line over time

> 🔹 **Visual cues** such as color (green/red) or arrows help quickly indicate whether the goal is met or missed.

---

## 🔄 Using Time Intelligence with KPIs

You can **combine Time Intelligence with KPIs** to create powerful business insights:
- Compare **MTD Sales** to **MTD Sales Last Year**
- Show a **KPI** where the target is the **previous year's total**, using `SAMEPERIODLASTYEAR()` or `DATEADD()`

---

Would you like sample DAX formulas or a KPI visual walkthrough?
