# 🏦 Banking Dashboard — Loan & Deposit Analytics

An interactive, multi-page business intelligence dashboard that analyses a bank's client base, loan portfolio, and deposit portfolio. It lets stakeholders slice performance by **banking relationship, gender, investment advisor, time period, nationality, income band, and client engagement timeframe**.

> **Tool:** Power BI &nbsp;|&nbsp; **Domain:** Banking & Financial Services &nbsp;|&nbsp; **Type:** Descriptive / Portfolio Analytics

---

## 📑 Table of Contents

- Project Overview
- Business Objectives
- Key Metrics (KPIs)
- Key Insights
- Filters & Interactivity
- Tech Stack
- Limitations & Future Improvements

---

## 📌 Project Overview

Banks manage thousands of clients across loans, deposits, credit cards, and fee-generating services. Leadership needs a single place to answer questions such as:

- How large is our loan and deposit book, and how is it composed?
- Which client segments (nationality, income band, tenure) drive the most value?
- How does the **Private Bank** segment compare with the overall bank?

This dashboard consolidates those answers into four navigable pages: **Home, Loan Analysis, Deposit Analysis, and Summary**.

---

## 🎯 Business Objectives

1. Provide a one-page executive view of the bank's total clients, loans, deposits, and fees.
2. Break down the loan portfolio by product type, nationality, income band, and engagement timeframe.
3. Break down the deposit portfolio by account type, nationality, income band, and engagement timeframe.
4. Enable fast, filter-driven comparison of client segments and time periods.

---

## 📊 Key Metrics (KPIs)

### Bank-wide (Home page — all clients, all time)

| KPI | Value |
|---|---|
| Total Clients | 2,940 |
| Total Loan | $4.38bn |
| Total Deposit | $3.77bn |
| Total Fees | $158.19M |
| Saving Account Amount | $698.73M |

### Private Bank segment (Loan, Deposit & Summary pages — all time)

| Category | KPI | Value |
|---|---|---|
| Clients | Total Clients | 1,333 |
| Loans | Total Loan | $1.99bn |
| | Bank Loan | $814.22M |
| | Business Lending | $1.17bn |
| | Credit Cards | $4.28M |
| Deposits | Total Deposit | $1.73bn |
| | Bank Deposit | $925.4M |
| | Checking Account Amount | $434.77M |
| | Saving Account Amount | $324.13M |
| | Foreign Currency Amount | $41.43M |
| Other | Total Fees | $72.6M |
| | Engagement Account | $7.85M |

---

## 💡 Key Insights

> All figures below are read directly from the dashboard visuals (Private Bank segment, All Time filter). Percentages are simple ratios calculated from those figures.

### Segment size
- The **Private Bank** segment accounts for **1,333 of 2,940 clients (~45%)**, yet holds **~45% of total loans** ($1.99bn of $4.38bn) and **~46% of total deposits** ($1.73bn of $3.77bn) — its contribution is broadly proportional to its client share.
- Private Bank generates **$72.6M of $158.19M in fees (~46%)**.

### Loan portfolio
- **Business Lending dominates** at $1.17bn (~59% of the Private Bank loan book), followed by Bank Loans at $814.22M (~41%). **Credit cards are negligible** at $4.28M (<1%).
- **Mid-income clients hold the largest share of Bank Loans**: $442.07M (~54%), vs. $201.93M for Low and $170.21M for High income bands.
- **European clients lead Bank Loans** by nationality ($358.41M, ~44%), followed by Asian ($198.93M), American ($134.7M), Australian ($72.41M), and African ($49.77M).
- By engagement timeframe, the **"< 20 Years" group carries the highest total loan balance ($0.75bn)**, and the "< 5 Years" group is minimal ($0.04bn).

### Deposit portfolio
- **Bank Deposit is the largest component** at $925.4M (~54% of total deposits), followed by Checking ($434.77M), Savings ($324.13M), and Foreign Currency ($41.43M).
- **Mid-income clients hold ~55% of Bank Deposits** ($510.43M), vs. $228.01M (Low) and $186.96M (High).
- **European clients lead deposits** by nationality (approx. $1.5bn across all deposit types), well ahead of Asian (~$0.8bn) and American (~$0.6bn) clients.
- Deposits are concentrated in long-tenured relationships: **"< 20 Years" ($0.67bn) and "> 20 Years" ($0.57bn)** together make up roughly 72% of total deposits, while the "< 5 Years" group holds only $0.03bn.

### Cross-cutting takeaways
- **Mid-income and European clients** are the core of both lending and deposits — the clearest segment to protect and grow.
- **Newer clients ("< 5 Years") contribute very little** to either loans or deposits — a possible onboarding/engagement opportunity.
- **Foreign currency deposits are under 3%** of total deposits, indicating limited penetration of this product.

---

## 🎛️ Filters & Interactivity

- **Time intelligence slicers:** All Time, Last 30 D, Last 90 D, Last 3 M, Last 6 M, Last 12 M, Last 24 M, CM (current month), CQ (current quarter), CY (current year)
- **Banking Relationship** (e.g., Private Bank)
- **Gender**
- **Investment Advisor**
- **Page navigation** via top menu and Home page buttons
- Cross-filtering across all visuals on a page

---

## 🛠️ Tech Stack

| Component | Tool |
|---|---|
| Visualisation / BI | Power BI Desktop |
| Data modelling & measures | DAX, Power Query |
| Source data | `[ADD: Excel / CSV / SQL source]` |

---

## ⚠️ Limitations & Future Improvements

- All insights are descriptive; no forecasting or statistical testing has been applied.
- Findings above reflect the **Private Bank** filter only; other banking relationships are not shown in the screenshots.
- Possible next steps: loan-to-deposit ratio, fee analysis by segment, client churn / retention analysis, and trend charts over time.

---

⭐ If you found this project useful, consider giving the repository a star.
