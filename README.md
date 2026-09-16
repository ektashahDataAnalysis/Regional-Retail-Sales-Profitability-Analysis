# Regional-Retail-Sales-Profitability-Analysis
Excel Regional Retail Sales &amp; Profitability Analysis Project

Regional Retail Sales & Profitability Analysis
Excel-only analytics workbook — PivotTable-style summaries, XLOOKUP/INDEX-MATCH, and What-If scenario modeling 

Business question: Which regions and product categories are driving revenue and profit, and how sensitive is profit to discounting and cost inflation?

Sheets:
  Raw_Data          260 synthetic transaction records (Jan–Dec 2025) across 4 regions and 5 product categories. Revenue, COGS and Profit are calculated with live formulas.
  Reference_Tables   Region manager and product category lookup tables, used for INDEX/MATCH and product lookup demos.
  Summary_Analysis   PivotTable-style SUMIFS summaries: Revenue/Profit by Region, by Category, and by Month.
  Dashboard          KPI cards, a Region selector (data validation dropdown) that drives live SUMIFS totals, and 3 charts.
  What-If_Analysis   Adjustable discount and cost-inflation assumptions (blue input cells) that flow through to a live profit-impact projection.

All calculated cells use formulas (SUMIFS, INDEX/MATCH, IF) referencing Raw_Data — nothing is hardcoded. Change any input cell and the workbook recalculates.

Tools demonstrated: PivotTables/SUMIFS analysis, Power Pivot-style data modeling, INDEX/MATCH & XLOOKUP-equivalent lookups, What-If / scenario analysis, conditional formatting, chart design.

