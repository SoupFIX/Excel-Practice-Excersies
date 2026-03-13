### 📕 4. Excel_Practice_If_or_nested.xlsx

> **Topic:** IF Logic, Nested IFs & Conditional Formatting

The most advanced file in the repo! It covers **three formatting challenge sheets**, each testing a different aspect of conditional logic and formatting.

**🎨 Formatting Sheet 1 — Above/Below Average Highlighting:**
- Apply conditional formatting so cells **above average turn GREEN**, cells below turn **RED**
- Use `AVERAGE()` as a dynamic threshold
- Identify which rows are entirely above or below average

**📋 Formatting Sheet 2 — Training Batch Tracker:**
- Work with a structured dataset: Batch No., Pax Count, Timeslots, Session Dates, Trainers
- Apply formatting rules based on batch conditions
- Practice date-based formatting

**📅 Formatting Sheet 3 — Month-Based Column Formatting:**
- Format an entire column dynamically **based on a selected month in cell C5**
- Use `IF()` and conditional formatting together
- Understand how formula-driven rules work

**📌 Key Functions & Features Used:**
```excel
=IF(condition, value_if_true, value_if_false)
=AVERAGE()               → Used as a dynamic threshold
Conditional Formatting   → Home Tab → Conditional Formatting
  ├── Highlight Cell Rules
  ├── New Rule → Use a formula
  └── =A1 > AVERAGE($A$1:$A$10)
```
