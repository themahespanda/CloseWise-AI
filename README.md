<div align="center">

# 🧾 CloseWise AI

### Intelligent Sales. Smarter Decisions. Better Closures.

AI-Powered Sales & Deal Intelligence Platform

[![Live Demo](https://img.shields.io/badge/✦_LIVE_DEMO-Explore_Now-6366F1?style=for-the-badge)](https://themahespanda.github.io/CloseWise-AI/)

</div>



---

## Overview

CloseWise AI is a browser-based financial operations dashboard designed to streamline and demonstrate key month-end financial close and expense audit activities.

The platform brings financial monitoring, transaction-level risk investigation, bank reconciliation, governance controls, and reporting into a unified interface. It helps users identify potential financial exceptions, monitor closing progress, and understand the impact of audit findings across connected workflows.

Built as an academic technology project, CloseWise AI demonstrates how automation, structured audit rules, financial analytics, and human-in-the-loop controls can support modern finance operations.

## Key Features

- **Executive Financial Dashboard** – Consolidated view of financial performance, disbursements, risk exposure, and reconciliation status.
- **Month-End Close Monitoring** – Tracks closing milestones, task completion, and critical dependencies.
- **Forensic Expense Audit** – Identifies potentially unusual transactions using deterministic policy rules and anomaly-scoring demonstrations.
- **Bank Reconciliation** – Displays matched and unmatched transactions and reconciliation differences.
- **AI Audit Copilot** – Provides structured findings, financial impact, and recommended actions using predefined demonstration logic.
- **Maker-Checker Workflow** – Demonstrates role switching, approval authority limits, and financial review controls.
- **CloseWise Impact Chain** – Connects expense risk detection with payment controls, evidence review, approval, reconciliation, and month-end close.
- **Data Explorer** – Supports CSV and Excel uploads, validation, and transaction-level data exploration.
- **Financial Reporting** – Generates financial summaries and CSV/Excel exports.
- **Governance & SOX Controls** – Demonstrates internal control monitoring and audit activity tracking.

## Dashboard Preview

### 1. Executive Financial Overview

The command center provides a consolidated view of financial activity, month-end closing progress, risk exposure, and bank reconciliation performance.

![CloseWise AI Executive Overview](assets/closewise-overview.jpg)

### 2. Expense Audit & Investigation Room

The forensic investigation interface displays transaction risk scores, severity classifications, and explainability factors contributing to flagged expenses.

![CloseWise AI Expense Audit](assets/expense-audit-investigation.jpg)

### 3. Data Explorer & CSV/Excel Ingestion

The Data Explorer allows users to upload transaction files, validate records, review import results, and add valid records to the active expense dataset.

![CloseWise AI Data Explorer](assets/data-explorer-upload.jpg)

## Dashboard Modules

| Module | Description |
|---|---|
| Executive Overview | Financial KPIs, risk indicators, and operational summaries |
| Month-End Close | Closing milestones, task status, and dependencies |
| Expense Audit | Transaction investigation, risk scoring, and audit exceptions |
| Reconciliation | Bank and general ledger matching |
| AI Audit Copilot | Structured financial findings and recommended actions |
| Financial Reports | Financial summaries and export functionality |
| Governance & SOX | Internal controls, approval workflows, and audit trail |
| Data Explorer | CSV/Excel ingestion, validation, and transaction exploration |

## Signature Feature – CloseWise Impact Chain

The CloseWise Impact Chain demonstrates how a potentially suspicious expense can move through a connected financial control workflow.

**Workflow:**

1. Transaction identification
2. Risk detection
3. Payment hold
4. Evidence verification
5. Human approval
6. Bank reconciliation
7. Month-end close

This feature demonstrates how expense audit findings can influence downstream financial control activities while keeping final approval decisions under human supervision.

## Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Dashboard structure |
| CSS3 | Interface styling |
| JavaScript | Application logic and interactions |
| Tailwind CSS | Utility-based styling |
| Chart.js | Financial charts and visualizations |
| SheetJS (xlsx) | Excel file reading and export |
| Google Fonts | Inter and JetBrains Mono typography |
| Google Antigravity | Development environment |

## Key Dashboard Metrics

The demonstration dashboard displays the following financial indicators:

| Metric | Value |
|---|---:|
| Total Disbursements | ₹48,32,190 |
| Total Transactions | 1,159 |
| Journal Entries | 568 |
| Month-End Close Completion | 72% |
| High/Critical Risk Transactions | 47 |
| Risk Exposure | ₹2,84,500 |
| Reconciliation Accuracy | 96.4% |
| Matched Bank Transactions | 270 / 286 |
| Unmatched Transactions | 16 |
| Hours Saved | 142.5 |
| Automation Coverage | 84.2% |
| Data Quality | 98.4% |

*All displayed metrics are configured demonstration values and are not independently audited production results.*

## Data Handling

The dashboard uses two separate data scopes:

- **Enterprise Aggregate Model:** 1,159 monitored transactions totaling ₹48,32,190 across 568 journal entries.
- **Detailed Forensic Session Ledger:** 15 initial transaction-level sample records totaling ₹2,98,060.

The detailed sample is used for forensic investigation and should not be interpreted as the complete aggregate transaction population.

### Supported File Uploads

The Data Explorer supports:

- CSV (`.csv`)
- Excel (`.xlsx`)
- Excel 97–2003 (`.xls`)

Required transaction fields:

```text
tx_id, date, vendor, amount, category
```

Uploaded files are checked for required fields, duplicate transaction IDs, valid dates, and valid positive amounts. Valid records are added to the active expense dataset within the application session.

## Getting Started

### Prerequisites

- Modern web browser (Chrome, Edge, Firefox, or Safari).
- Downloaded or cloned project source code.
- Internet connection for externally loaded frontend libraries and fonts.

### Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/CloseWise-AI.git
```

### Navigate to the Project

```bash
cd CloseWise-AI
```

### Run the Dashboard

Open the main HTML file:

```text
closewise_dashboard.html
```

Alternatively, start a local development server:

```bash
python -m http.server 8000
```

Open the following address in your browser:

```text
http://localhost:8000/closewise_dashboard.html
```

The supplied implementation is a client-side HTML application and does not require a separate Python backend.



## Implementation Notes

- The AI Audit Copilot uses predefined deterministic demonstration logic.
- No live external LLM or third-party ERP API is connected.
- Financial figures are demonstration data.
- Banking and accounting platforms are not connected to live systems.
- Maker-checker controls demonstrate approval workflows rather than production identity management.
- The audit trail is a demonstration feature, not a certified immutable audit log.
- Uploaded records are handled within the browser application's active session; enterprise database persistence is not demonstrated.

## Future Enhancements

- Live ERP and accounting system integration.
- Automated bank statement synchronization.
- Secure database integration and persistent storage.
- Production-grade AI anomaly detection.
- Automated invoice and supporting-document verification.
- Enterprise authentication and role-based access control.
- Advanced financial forecasting and analytics.
- Cloud deployment and enhanced audit logging.

## Team Contributions

This project was collaboratively developed by five MBA group members.

| Member | Contribution |
|---|---|
| Maheshwar Panda (M1) | Process mapping, current-state workflow, and problem analysis |
| Mahesh Singh (M2) | System design, architecture, agent roles, shared state, and human approvals |
| Rathod Pavan (M3) | Solution design and technical implementation documentation |
| P. Saketh Kanishka (M4) | Dashboard, financial analysis, expense review, reconciliation, and data presentation |
| Maley Harika (M5) | Testing, evaluation, validation, results, and limitations |

## Disclaimer

CloseWise AI is an academic group project developed for educational and demonstration purposes. It demonstrates AI-assisted concepts in financial close management, expense auditing, reconciliation, and financial governance.

It is not a production financial system and does not replace professional accounting judgment, statutory audits, or authorized financial approvals.

---

<div align="center">

**CloseWise AI**

*Bringing financial close visibility, expense review, and control workflows together.*

</div>
