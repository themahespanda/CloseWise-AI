<div align="center">

# 🧾 CloseWise AI

### Intelligent Sales. Smarter Decisions. Better Closures.

AI-Powered Sales & Deal Intelligence Platform

[![Live Demo](https://img.shields.io/badge/✦_LIVE_DEMO-Explore_Now-6366F1?style=for-the-badge)](https://themahespanda.github.io/CloseWise-AI/)

</div>

CloseWise AI – Month-End Financial Close & Expense Audit Agent
Enterprise Streamlit Financial Intelligence & Audit Automation Platform (v3.1)
CloseWise AI is an institutional-grade financial intelligence application designed for Controllers, CFOs, Internal Auditors, and Governance Committees. It automates manual month-end financial closes into an auditable, risk-managed workflow built with native Python, Pandas, Streamlit, and Plotly in Indian Rupees (₹).

🏛️ Executive Summary & Key Highlights
Currency Standard: Formatted exclusively and consistently in Indian Rupees (₹) across all KPI cards, tables, charts, exports, and audit logs.
Data Rigor & Dual-Layer Architecture:
Aggregate Population: 1,159 disbursements totaling ₹48,32,190.00 across 4 operational categories (Hardware & Infrastructure: ₹18,42,500; Cloud & SaaS Subscriptions: ₹12,15,800; Professional Services & Advisory: ₹9,84,390; Travel & Corporate Entertainment: ₹7,89,500).
Forensic Sample Batch: 15 detailed sample records (₹2,98,060.00) with complete factor-level explainability, evidence attachments, and audit notes.
Single Source of Truth: Reconciles 100% across all 8 modules, reports, and downloads.
Unique Feature — CloseWise Impact Chain: End-to-end interactive 6-stage causal financial pipeline: 
Suspicious Expense
⟶
Risk Detection
⟶
Payment Hold
⟶
Evidence Verification
⟶
Human Approval
⟶
Month-End Close Update
Enterprise SOX 404 & Governance: Built-in Segregation of Duties (Maker-Checker model), controls matrix (CTRL-AC-01 through CTRL-AC-06), and tamper-evident SHA-256 audit logging.
📁 Project Architecture
CloseWise_AI/
│
├── app.py                      # Main entry point, navigation router & What-If simulator
├── data_source.json            # Reconciled benchmark baseline data model (INR ₹)
├── requirements.txt            # Python dependencies (streamlit, pandas, plotly, openpyxl)
├── run_app.bat                 # One-click Windows batch launcher
├── run_app.ps1                 # One-click Windows PowerShell launcher
├── test_streamlit_engine.py    # Automated test suite for calculations & state engine
├── CLOSEWISE_README.md         # Full product documentation & MBA presentation guide
│
└── modules/
    ├── __init__.py             # Python package descriptor
    ├── styles.py               # Minimalist white theme CSS, custom KPI cards, badges
    ├── data.py                 # Session state initialization & audit trail logging
    ├── calculations.py         # Financial analytics & reconciliation calculations (INR ₹)
    ├── overview.py             # Module 1: Executive Overview & 6-Stage Impact Chain
    ├── close.py                # Module 2: Month-End Close (Kanban War Room & Gating)
    ├── audit.py                # Module 3: Expense Audit (Forensics, Waterfall, Maker-Checker)
    ├── reconciliation.py       # Module 4: Bank Reconciliation (Two-Way Waterfall Bridge)
    ├── copilot.py              # Module 5: AI Audit Copilot (Finding / Impact / Action)
    ├── reports.py              # Module 6: Financial Reports (CSV & Multi-Sheet Excel .xlsx)
    ├── governance.py           # Module 7: Governance & SOX 404 Controls Matrix
    └── data_explorer.py        # Module 8: Dual-Layer Data Explorer & CSV Ingestion Parser
🚀 How to Run the Application
Option 1: Live Local Server
The application is currently running live at: http://localhost:8501

Option 2: One-Click Launchers (Windows)
Batch file: Double-click run_app.bat
PowerShell: Right-click and choose Run with PowerShell, or execute:
cd C:\Users\Mahesh\Downloads
.\run_app.ps1
Option 3: Command Line
C:\Users\Mahesh\AppData\Local\Programs\Python\Python313\python.exe -m streamlit run app.py
🧭 The 8 Core Modules
1. Executive Overview
4 Focused KPI Cards:
Total Disbursements: ₹4,832,190 (Aggregate Demo Model • 100% Reconciled)
Close Completion: 72.0% (8 of 12 Tasks Finalized • Day +2 of 5)
High/Critical Risk Txns: 47 Items (₹2,84,500 Held • 14 Critical, 33 High)
Bank Reconciliation Rate: 96.4% (270 of 286 Matched • Net Var: ₹18,420)
Visual Section: Close Progress (Day +2/5, velocity gauge), Financial Risk Distribution Donut (Critical: 14, High: 33, Medium: 182, Clean: 930), and Bank Reconciliation Status (96.4% match rate).
Top 3 Priority Audit Exceptions:
EXP-11082 (Apex Global Advisory, ₹48,500) – Critical split PO & kickback risk.
CT-109 (ASC 606 Rev Rec, 70%) – Critical closing path bottleneck gating CT-110 & CT-112.
REC-1002 (Chase Operating, ₹18,420 Net) – 16 open reconciling items.
Unique Feature — CloseWise Impact Chain: Compact 6-stage interactive pipeline: Suspicious Expense → Risk Detection → Payment Hold → Evidence Verification → Human Approval → Month-End Close Update Select any stage to inspect the transaction dossier, explanation, workflow effect, and month-end closing impact.
2. Month-End Close (Kanban War Room)
Interactive Kanban board with 4 columns: Completed (8), In Progress (2), Delayed / Blocked (1), Pending Gated (1).
Dependency Gating Engine: CT-109 (ASC 606 Rev Rec) actively gates CT-110 (Tax Provision) and CT-112 (CFO Board Deck Sign-Off).
Simulation Advance: Click "Advance Sim (+1)" to step the close schedule forward in real time.
3. Expense Audit & Forensic Lab
Forensic Table: Complete search and severity filtering in INR (₹).
AI Fraud Investigation Room:
Plotly Explainability Factor Waterfall: Visual breakdown of anomaly contributions (Spend Outlier +35 pts, Missing Tax Form +25 pts, Policy Cap Structuring +20 pts, IsolationForest Distance +16 pts = 96/100).
Maker-Checker Action Suite: Segregation of duties enforced:
Senior Auditor (Maker): Can flag, escalate, or request evidence.
Financial Controller (Checker): Can approve up to ₹10,000; vouchers >₹10,000 require Level 2 CFO sign-off.
Vendor Risk Intelligence & Smart Evidence Locker: Inspect counterparty spend and verify documents.
4. Bank Reconciliation & Cash Tie-Out
Population Summary: 286 total bank lines; 270 matched (96.4%), 16 unmatched (₹18,420 net variance).
Two-Way Waterfall Bridge: Plotly bridge chart reconciling General Ledger Cash (Account 1100) to Chase Commercial statement balance.
Adjusting Journal Entry (AJE) Posting: Interactive modal to formulate and record balancing journal entries directly into the audit ledger.
5. AI Audit Copilot
Grounded conversational assistant with 6 executive prompt chips.
Structured 3-Heading Responses:
### Finding
### Financial Impact
### Recommended Action
Transparent Demonstration Disclosure: Clear disclosures that responses are generated using internal rule logic grounded in the benchmark dataset, with no claims of external unverified APIs.
6. Financial Reports & Certified Exports
4 Executive Report Packages:
Executive Close Pack: Top-line balance tie-outs and category spend breakdown in INR (₹).
Expense Findings Register: Forensic audit log of flagged items with auditor notes.
Bank Reconciliation Schedule: Two-way tie-out with unmatched items ledger.
SOX 404 Compliance Certificate: Internal control health and risk ratings.
Certified Downloads: One-click CSV and multi-sheet Excel file (CloseWise_AI_FY26Q4_Comprehensive_Close_Pack.xlsx).
7. Governance & SOX 404 Controls Matrix
Controls Matrix tracking CTRL-AC-01 through CTRL-AC-06.
Role Switcher: Switch between Elena Rostova (Controller - L1 Reviewer), Marcus Vance (CFO - L2 Executive Sign-Off), and David Chen (Treasury Analyst - Maker).
Immutable Audit Trail: Chronological log capturing timestamp, actor, operation, target entity, notes, and SHA-256 cryptographic digest.
8. Data Explorer & CSV Ingestion Pipeline
Transparent Scope Disclosure: Clearly delineates between the 1,159 aggregate population records and the 15 forensic sample records.
Robust CSV Ingestion & Parser:
Displays uploaded filename, total rows, valid rows, and invalid rows.
Small data preview of the first 5 parsed records.
Detailed row-by-row validation error log inside an expandable area.
Genuine record commitment to active session state and audit log.
🎓 10-Step MBA Demonstration Presentation Walkthrough
Follow this scripted walkthrough for an MBA examination or executive presentation:

Step	Action	Executive Speaking Points
1. Overview & 4 KPIs	Open Executive Overview. Point out the 4 KPI cards.	"Welcome to CloseWise AI. Traditional month-end closes take 10 to 14 days and carry massive audit exposure. CloseWise monitors ₹48.32L in disbursements across 1,159 transactions, delivering a 72% close completion rate, 96.4% bank reconciliation accuracy, and isolating 47 high-risk items."
2. The Impact Chain	Scroll to CloseWise Impact Chain. Click through Stages 1 to 6.	"Our signature feature is the CloseWise Impact Chain. When an anomalous ₹48,500 split PO is detected, the agent triggers an automated payment hold under SOX CTRL-AC-02, verifies vendor contracts, mandates controller sign-off, and isolates the item before it corrupts bank reconciliation or blocks month-end close."
3. Priority Triage	In the Priority Section, click Investigate EXP-11082 →.	"Rather than sifting through 1,000+ rows, the dashboard surfaces our top 3 operational exceptions. Let's drill directly into our highest-risk invoice."
4. Forensic Deep-Dive	In Expense Audit, expand the Explainability Waterfall.	"Black-box AI is unacceptable to auditors. CloseWise provides factor-level explainability: we see exactly how spend outlier (+35 pts), missing tax clearance (+25 pts), and structuring (+20 pts) combine into a 96/100 risk score."
5. Segregation of Duties	Test the Maker-Checker buttons; attempt to approve as Controller, then switch to CFO.	"CloseWise enforces SOX 404 Segregation of Duties. A Controller cannot approve invoices exceeding ₹10,000; Level 2 CFO authorization is required, strictly complying with control CTRL-AC-01."
6. Close War Room	Navigate to Month-End Close. Point out CT-109.	"In the Close War Room, 8 of 12 tasks are complete. However, task CT-109—ASC 606 Revenue Recognition—is delayed at 70%. Notice the dependency gating: CT-110 and CT-112 are locked to prevent uneliminated balances from corrupting the balance sheet."
7. Bank Reconciliation	Open Bank Reconciliation. Highlight the Two-Way Bridge.	"Our cash reconciliation engine matched 270 of 286 items (96.4%). The Plotly waterfall clearly visualizes the ₹18,420 bridge between our General Ledger and bank statement, with full support for posting adjusting entries."
8. AI Audit Copilot	Open AI Audit Copilot and click "Explain why EXP-11082 was flagged".	"Our Copilot provides structured, audit-ready answers formatted with Finding, Financial Impact, and Recommended Action, grounded in verified ledger data."
9. SOX 404 & Audit Trail	Navigate to Governance & SOX.	"Every single action taken—flagging invoices, releasing holds, posting adjusting entries—is permanently recorded in our SHA-256 tamper-evident audit trail, ready for Big 4 audit sign-off."
10. Data Explorer & CSV	Open Data Explorer > CSV Ingestion & Parser.	"The system provides a robust CSV parser with row-level validation, displaying valid vs invalid rows, small previews, and expandable error logs before committing to the ledger."
🛠️ Verification & Test Suite
CloseWise AI includes an automated test verification script. To run all checks:

C:\Users\Mahesh\AppData\Local\Programs\Python\Python313\python.exe test_streamlit_engine.py
Verification Results:

✅ 4 Core Executive KPIs verified (₹4,832,190 disbursements, 72.0% close, 47 high-risk items, 96.4% rec accuracy).
✅ Category spend strictly reconciles to ₹4,832,190.00 across 4 categories.
✅ Financial Risk Distribution verified: Critical 14, High 33, Medium 182, Clean 930.
✅ Forensic sample batch verified (15 records, primary case EXP-11082: ₹48,500, score 96).
✅ Close task dependency gating verified (12 tasks, CT-109 gating CT-110 & CT-112).
✅ Bank reconciliation verified: 270 of 286 matched, 96.4% accuracy, ₹18,420 net variance.
✅ CloseWise Impact Chain verified: Exact 6 stages implemented.
✅ AI Copilot structured with Finding, Financial Impact, Recommended Action, and demo disclosures.
✅ Certified report downloads verified (CSV and multi-sheet Excel .xlsx).
