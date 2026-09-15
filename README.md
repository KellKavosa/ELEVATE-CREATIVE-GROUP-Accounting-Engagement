# QuickBooks Online End-to-End Accounting Simulation: Elevate Creative Group

## 📌 Project Overview
This repository contains a comprehensive, simulated bookkeeping and accounting engagement for **Elevate Creative Group**, a small creative-services business. The project demonstrates a complete, end-to-end accounting workflow within QuickBooks Online (QBO). 

The goal of this engagement is to showcase practical bookkeeping accuracy, rigorous account classification, financial control implementation, and the production of decision-useful financial reports.

---

## 🛠️ Core Skills & Workflows Demonstrated

*   **Company Setup & Chart of Accounts:** Established a customized Chart of Accounts tailored to a creative-services business model (tracking service revenues, contractor costs, and software subscriptions).
*   **Transaction Processing:** Managed daily operational accounting, including accounts receivable (invoicing and payments) and accounts payable (vendor bills and expenses).
*   **Banking & Credit Card Feeds:** Categorized and matched high-volume transactions from automated feeds using proper matching rules.
*   **Reconciliations:** Conducted full bank and credit card ledger reconciliations to verify data integrity against simulated monthly statements.
*   **Month-End Close:** Performed adjusting journal entries, accrued expenses, depreciation tracking, and period-end reviews.
*   **Financial Reporting:** Generated and compiled professional financial statement packages for management review.

---

## 📁 Repository Structure

*   `📁 Financial-Statements/` — Contains final PDF exports of key management reports.
    *   `Profit_and_Loss_Elevate_Creative.pdf`
    *   `Balance_Sheet_Elevate_Creative.pdf`
    *   `Statement_of_Cash_Flows_Elevate_Creative.pdf`
*   `📁 Audit-Trails-Ledgers/` — Contains general ledger data and verification reports.
    *   `Trial_Balance_Elevate_Creative.csv`
    *   `Reconciliation_Reports_Bank_CC.pdf`
*   `README.md` — Project description and workflow documentation (this file).

---

## 📊 Summary of Financial Insights & Outcomes
*(Tip: Replace these placeholder bullet points with a brief summary of how your simulated company performed at the end of your project!)*

*   **Revenue Performance:** High gross margins typical of creative services, with primary revenue driven by design and consulting contracts.
*   **Expense Control:** Effectively managed overhead costs, with software subscriptions and freelance contractors representing the largest operational outflows.
*   **Liquidity Position:** The ending Balance Sheet reflects strong working capital and a healthy cash runway moving into the next fiscal period.

---

## 🚀 Technical Tools Used
*   **Accounting Software:** QuickBooks Online (Global/US Edition)
*   **Data Analysis & Export:** Microsoft Excel / CSV
*   **Documentation:** Markdown
## 🧩 Key Accounting Challenges & Resolutions

### 1. Revenue Cycle Workflow Optimization (Invoice Payments vs. Sales Receipts)
*   **The Challenge:** During high-volume transaction processing across the full financial quarter, a major hurdle was correctly matching incoming bank feed deposits to their proper QBO source documents. It was easy to confuse **Invoice Payments** (money received for prior credit sales) with direct **Sales Receipts** (immediate payments). Misclassifying these would either double-count revenue or leave accounts receivable balances artificially inflated.
*   **The Resolution:** Developed a strict workflow review process. I verified whether a customer contract required an upfront invoice (tracking Accounts Receivable) or an immediate checkout. 
    *   For clients with credit terms, I ensured bank deposits were matched to the **Receive Payment** screen to clear out the open invoice.
    *   For point-of-sale transactions, I matched them directly to standalone **Sales Receipts**. 
    *   This eliminated duplicate income reporting and ensured 100% accurate accounts receivable aging logs.

### 2. Multi-Month Data Continuity & Quarterly Cutoff
*   **The Challenge:** Managing a full quarter of financial data meant tracking cumulative balances over three distinct months. Ensuring that revenue and expenses were recognized in the exact month they occurred (proper cutoff) was critical before closing the books.
*   **The Resolution:** Implemented a rigorous month-by-month reconciliation checklist for both the bank and credit card accounts. This guaranteed that timing differences at the end of each month did not bleed into and distort the next month's financial performance.
