<img width="1317" height="739" alt="Screenshot 2026-10-26 142928" src="https://github.com/user-attachments/assets/9edd9566-cb88-41c2-9ed2-1d5085d515fc" />


# Healthcare Claims Financial & Revenue Leakage Dashboard

## 1. Project Overview
This project delivers a high-impact Healthcare Claims Financial & Revenue Cycle Dashboard designed to minimize financial leakage and accelerate revenue recovery for medical billing organizations. By consolidating complex billing data across multiple insurance streams, the dashboard provides revenue cycle management (RCM) teams with immediate visibility into active accounts receivable (AR), claims inventory processing mixtures, and the root causes behind costly claim denials.

## 2. Tools & Technologies Used
* **Business Intelligence:** Microsoft Power BI (Desktop & Service)
* **Data Engineering & Preparation:** SQL Server / Power Query (ETL pipelines, mapping denial reason codes, string formatting)
* **Data Modeling & Calculations:** DAX (Data Analysis Expressions) for calculated financial measures (Paid-to-Billed Variance, Financial Aging metrics)
* **Visual Interface Elements:** Waterfall Charts, Layered Combo Bar Visuals, Stacked Columns, and Segmented Pie Charts

## 3. Key Keywords
* Revenue Cycle Management (RCM)
* Accounts Receivable (AR) Financial Aging
* Revenue Leakage Analysis
* Claim Denial Root Cause
* Payer Performance Tracking
* Billed vs. Paid Revenue Variance
* Claims Inventory Processing Mix
* DAX Financial Measures
* Dynamic Cross-Filtering

## 4. Core Metrics & Visual Components Explained
* **Financial KPI Cards:** Displays high-level core revenue aggregates for the evaluated cohort, measuring a Total Billed Value of 2,368, a Total Paid Value of 423, and a Total Claim Volume of 8 unique processing clusters.
* **Billed vs. Paid Revenue Comparison:** Provides a direct, side-by-side value analysis between what was billed vs. what was collected across distinct insurance categories: Commercial, Medicaid, Self-Pay, and Medicare. Visually highlights collection efficiency gaps where Commercial holds the highest billed threshold (79K billed vs. 53K paid).
* **Claims Inventory Processing Mix:** Segregates the lifecycle stage of all submitted claims into three critical operational buckets: Paid (33.4%), Under Review (32.8%), and Denied (33.8%) via an interactive donut chart.
* **Allowed Value Revenue Leakage Waterfall:** Uses a financial waterfall visual to map out step-down deviations from the initial allowed baseline down to final insurance payouts, showing exactly where cash flow breaks down.
* **Top Denial Root Clause Analysis:** Ranks the top operational reasons why insurance companies refuse payouts using count tracking, identifying "Authorization not obtained" (154 counts) and "Incorrect billing information" (142 counts) as the two primary culprits.
* **AR Financial Aging Distribution:** Tracks aging outstanding claim balances across specific collections statuses (Open, Closed, Pending, On Hold, Partially Paid, and Denied) using a clean pie chart breakdown (e.g., 184 Partially Paid, 177 On Hold, 157 Denied).

## 5. Project Outcome & Impact
* **Leakage Reduction:** Provided direct visibility into unpaid insurance value drops, significantly reducing untracked financial leakage points across Medicare and Commercial streams.
* **Proactive Denial Management:** Isolated the exact operational friction points (such as missing pre-authorizations or formatting typos), enabling hospital networks to fix billing workflows at the front desk.
* **Optimized Cash Flows:** Developed an Accounts Receivable (AR) aging distribution model that allows cash-posters and follow-up teams to immediately isolate "On Hold" and "Partially Paid" claims to optimize organizational liquidity.
