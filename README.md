# QuickBooks Online End-to-End Accounting Simulation: Elevate Creative Group

## 📌 Project Overview
This repository contains a comprehensive, simulated bookkeeping and accounting engagement for **Elevate Creative Group**, a small creative-services business. The project demonstrates a complete, end-to-end accounting workflow within QuickBooks Online (QBO) covering a **full financial quarter**. 

The goal of this engagement is to showcase practical bookkeeping accuracy, rigorous account classification, financial control implementation, and the production of decision-useful financial reports.

---

## 📁 Repository Structure

*   `📁 Project-Governance-Planning/` — Internal planning, strategy, and accounting rule frameworks.
    *   `Business Profile.pdf`
    *   `Accounting Assumptions and Policies.pdf`
    *   `Accounting Process Map.pdf`
    *   `Chart of Accounts Design and Account Mapping Document.pdf`
    *   `Elevate Creative Group — End-to-End QuickBooks Online Accounting & Month-End Close.pdf`
    *   `Elevate-Creative-Group_qb_performance_08-26-26.pdf`
    *   `Elevate_Creative_Group_Engagement_Summary.pdf`
*   `📁 Source-Data/` — Raw operational records imported into the system.
    *   `Elevate_Creative_Group_1110_Operating_Checking_Transactions.csv`
    *   `Elevate_Creative_Group_2120_Credit_Card_Transactions.csv`
    *   `Elevate_Creative_Group_Customer_Invoice_Dataset.csv`
    *   `Elevate_Creative_Group_Customer_Invoice_Dataset 2.csv`
    *   `Elevate_Creative_Group_Customer_Payment_Dataset.csv`
    *   `Elevate_Creative_Group_Income_Bank_Matching_1110.csv`
    *   `Elevate_Creative_Group_Operating_Expense_Dataset.csv`
    *   `Elevate_Creative_Group_Vendor_Bill_Dataset.csv`
    *   `Elevate_Creative_Group_Vendor_Payment_Dataset.csv`
    *   `Services Catalogue.csv`
*   `📁 Financial-Statements/` — Final management report packages.
    *   `BalanceSheet.pdf`
    *   `ProfitandLoss(Beta).pdf`
    *   `StatementofCashFlows.pdf`
*   `📁 Subledgers-Aging/` — Specialized monitoring reports for working capital control.
    *   `AR_Aging_Summary.pdf`
    *   `AP_Aging_Summary.pdf`
*   `📁 Audit-Trails-Ledgers/` — Data integrity logs and reconciliation worksheets.
    *   `TrialBalance.pdf`
    *   `GeneralLedger.pdf`
    *   `Reconciliation Report.pdf`
*   `README.md` — Project description and workflow documentation (this file).

---

## 🛠️ Core Skills & Workflows Demonstrated

*   **System Infrastructure & Governance:** Designed a customized Chart of Accounts and comprehensive account mapping structures tailored specifically for agency and creative-service business models.
*   **Data Migration & Processing:** Managed raw multi-channel data imports (CSV format) covering credit card logs, operational checking, checking matches, and vendor billing schedules.
*   **Revenue Cycle Workflow Control:** Audited and structured strict invoicing pathways to avoid duplicate income reporting by carefully separating upfront Sales Receipts from deferred Invoice Payments.
*   **Credit & Working Capital Management:** Monitored customer credit risk and supplier payment terms utilizing detailed Aging Subledgers.
*   **Reconciliations & Quarter-End Close:** Executed cross-ledger verification of bank and credit card accounts alongside quarter-end adjustments to guarantee zero transaction discrepancies.

---

## 🧩 Key Accounting Challenges & Resolutions

### 1. Revenue Cycle Workflow Optimization (Invoice Payments vs. Sales Receipts)
*   **The Challenge:** During high-volume transaction processing across the full financial quarter, a major hurdle was correctly matching incoming bank feed deposits to their proper QBO source documents. It was easy to confuse **Invoice Payments** (money received for prior credit sales) with direct **Sales Receipts** (immediate payments). Misclassifying these would either double-count revenue or leave accounts receivable balances artificially inflated.
*   **The Resolution:** Developed a strict workflow review process based on contract types. For credit clients, bank deposits were explicitly matched to the **Receive Payment** window to draw down open accounts receivable balances. Direct sales were recorded as standalone **Sales Receipts** bypassing the subledger, completely clearing out duplicate entry risks.

### 2. Multi-Month Data Continuity & Quarterly Cutoff
*   **The Challenge:** Managing a full quarter of financial data meant tracking cumulative balances over three distinct months. Ensuring that revenue and expenses were recognized in the exact month they occurred (proper cutoff) was critical before closing the books.
*   **The Resolution:** Implemented a rigorous month-by-month reconciliation checklist for both the bank and credit card accounts. This guaranteed that timing differences at the end of each month did not bleed into and distort the next month's financial performance.

---

## 🚀 Technical Tools Used
*   **Accounting Software:** QuickBooks Online (QBO)
*   **Data Management & Source Files:** Microsoft Excel / CSV
*   **Documentation & Version Control:** Git / GitHub / Markdown

---

## 💼 Connect With Me
*   **LinkedIn:** [www.linkedin.com/in/kellen-kavosa)
*   **Email:** [kavosakellen@gmail.com](mailto:your.email@example.com)nths. Ensuring that revenue and expenses were recognized in the exact month they occurred (proper cutoff) was critical before closing the books.
*   **The Resolution:** Implemented a rigorous month-by-month reconciliation checklist for both the bank and credit card accounts. This guaranteed that timing differences at the end of each month did not bleed into and distort the next month's financial performance.
