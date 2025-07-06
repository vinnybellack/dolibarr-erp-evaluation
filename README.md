# Dolibarr ERP Explained: Features, Workflows & Data Access

## Repository Overview

This GitHub repository serves as a comprehensive documentation and research project focused on evaluating the open-source **Dolibarr ERP and CRM system**. It is prepared by Vinod Balakrishnan for internal use at TEMS Tech Solutions, covering module-wise capabilities, workflows, integration patterns, benefits, limitations, and options for cloud vs. self-hosted setup.

---

## 📘 Table of Contents

1. Overview of Dolibarr ERP System
2. Summary of Key Modules and Their Functions
3. Benefits & Limitations
4. Suggestions & Recommendations
5. Interconnected Modules in Dolibarr
6. Data Extraction for Analysis

---

## 1. Overview of Dolibarr ERP System

Dolibarr is an open-source ERP and CRM system designed for freelancers, small businesses, and large organizations. It offers modules for HR, Sales, Inventory, Finance, Projects, and more. The interface is modular, intuitive, and supported by an active global community.

### Why Dolibarr Stands Out

* All-in-one platform for cross-functional use.
* Built-in integration between HR, Finance, Projects, and Sales.
* Zero-code customization using Module Builder.
* Seamless upgrades and data safety.

### Hosting Options

* **Self-hosted**: Full control, local server, developer access.
* **Cloud-hosted (SaaS)**: Easy deployment, automatic backups & updates.

### Trusted Cloud Providers

* DoliCloud (Official)
* DoliPlace, DoliOnDemand, Ma Gestion Cloud
* BitNami, UnboxCRM, DoliBox, DoliPlatform

### Demo Access

* Dedicated Instance: Full admin rights.
* Shared Public Demo: Fast preview (reset periodically).

---

## 2. Summary of Key Modules & Functions

### 2.1 HR, Attendance & Leave Management

Track employee data, leave balances, expenses, attendance, and recruitment.
**Workflows:**

* Leave: New, Collective, List, Balance, Statement, Logs
* Expenses: New, List, Payments, Stats
* Recruitment: New Job, Job List, Applications
  # 🧾 HR & Leave Management Module Summary (Dolibarr ERP)

This repository section summarizes the **HR & Attendance**, **Leave Management**, **Expense Reports**, **Recruitment**, and **Communication** modules from Dolibarr ERP. The content is extracted from an internal evaluation conducted for TEMS Tech Solutions.

---

## 📄 Summary Table – HR & Leave Management

| **Section**                   | **Purpose**                                                  |
|------------------------------|--------------------------------------------------------------|
| Leave → New                  | Submit individual leave requests                             |
| Leave → New Collective       | Assign leave to groups (e.g., holidays)                      |
| Leave → List                 | View all leave records                                       |
| Leave → Balance              | Show leave entitlement and remaining balance                 |
| Leave → Monthly Statement    | Monthly breakdown of leaves per employee                     |
| Leave → Change Logs          | Audit changes in leave records                               |
| Expense Reports → New        | Submit expense claim                                         |
| Expense Reports → List       | View all claims                                              |
| Expense Reports → Payments   | Mark reimbursements                                          |
| Expense Reports → Stats      | Analyze expense trends                                       |
| Time Tracking                | Log time against tasks/projects                              |
| Recruitment → New Job        | Add a new vacancy                                            |
| Recruitment → Job List       | See all job openings                                         |
| Recruitment → Application    | Add a new candidate                                          |
| Recruitment → App List       | View and track all applicants                                |


### 2.2 Communication

Facilitates messaging, approvals, notifications across Sales, HR, Support.
**Workflows:** Proposals, Orders, Contracts, Vendor Management, Subscriptions, Interventions
## 📄 Summary Table – Sales & Vendor Communication

| **Module**         | **Purpose / Use**                                                                 |
|--------------------|-----------------------------------------------------------------------------------|
| 📨 Communications   |                                                                                   |
| Commercial Proposals → New       | Create a sales quotation for a client before order confirmation.          |
| Commercial Proposals → List      | View and manage all sent proposals with status tracking.                  |
| Commercial Proposals → Statistics| Analyze proposal conversion rates and forecast revenue.                   |
| 🧾 Sales Orders     |                                                                                   |
| Sales Orders → New Order         | Place a new customer order manually or from an accepted proposal.         |
| Sales Orders → List              | View all customer orders with filters by status, customer, date, etc.     |
| Sales Orders → Lines of Orders   | See all product-level order details across sales orders.                  |
| Sales Orders → Statistics        | Monitor sales trends, top customers, and order volumes.                   |
| 📦 Vendor Proposals |                                                                                   |
| Vendor Proposals → New Request   | Create and send an RFQ (Request for Quotation) to suppliers.              |
| 📦 Vendor Proposals     |                                                                                            |
| Vendor Proposals → List        | Manage all received supplier quotations in one place.                                |
| Vendor Proposals → Statistics  | Track quote responses, vendor performance, and proposal success rates.               |
| 🛒 Purchase Orders       |                                                                                            |
| Purchase Orders → New Order   | Create a formal purchase order to procure goods/services from vendors.               |
| Purchase Orders → List        | View all POs with current status (ordered, received, billed).                        |
| Purchase Orders → Statistics  | Analyze purchase volume, frequent suppliers, and cost trends.                        |
| 📄 Contracts / Subscriptions |                                                                                            |
| Contracts → New Contract      | Start a new customer contract or service subscription (e.g., AMC, SaaS).             |
| Contracts → List              | Track ongoing, expired, or renewable contracts with customer info.                    |
| 🛠 Interventions (Services)   |                                                                                            |
| Interventions → New           | Log new on-site service work (support, repairs, etc.).                               |
| Interventions → List          | Manage and assign all field service tasks to team members.                           |
| Interventions → Statistics    | View service performance data, time taken, and team efficiency.                      |
### 2.3 Projects & Tasks

Plan projects, assign tasks, track time, and analyze progress.
**Workflows:** Leads, Project Lists, Task Tracking, Time Logging
## 📄 Summary Table – Projects, Tasks & Time Tracking

| **Module / Feature**     | **Purpose / Use**                                                                            |
|--------------------------|----------------------------------------------------------------------------------------------|
| 📁 Projects & Leads       |                                                                                              |
| Projects → New lead or project | Create a new business lead (potential project) or a confirmed project.                 |
| Projects → List               | View and manage all projects and leads in the system.                                   |
| Projects → List open leads    | View all ongoing or active leads not yet converted into projects.                      |
| Projects → List open projects | Track ongoing/active projects under execution.                                          |
| Projects → Statistics         | Analyze project metrics — number, success rate, average duration, budget usage.        |
| ✅ Tasks / Activities    |                                                                                              |
| Tasks → New task             | Create a new task within a project, assign team members, set deadlines.                 |
| Tasks → List                 | View all tasks across projects with filters (status, assignee, deadline).               |
| Tasks → Statistics           | Analyze task progress, completion rates, team productivity.                             |
| ⏱ Time Tracking        |                                                                                              |
| Time Tracking → List         | View logged working hours against tasks/projects for billing or analysis.              |

### 2.4 Sales & Lead Generation (Third Parties)

Central CRM for leads, clients, vendors, contacts.
**Workflows:** Third Party, Prospects, Customers, Vendors, Addresses
## 📄 Summary Table – CRM: Third Parties & Contacts

| **Module / Feature**         | **Purpose / Use**                                                                 |
|------------------------------|-----------------------------------------------------------------------------------|
| 👥 Third Parties              |                                                                                   |
| Third Party → New Third Party    | Create a general third-party profile (can be later marked as customer/vendor).     |
| Third Party → List               | View and manage all third-party entries — customers, vendors, and prospects.       |
| 🌱 Prospects                |                                                                                   |
| Prospects → New Prospect        | Add a new business prospect (potential customer).                                |
| 󰳖 Customers              |                                                                                   |
| Customers → New Customer       | Register a new customer with relevant business and contact information.           |
| 🏢 Vendors                |                                                                                   |
| Vendors → New Vendor           | Register a supplier or vendor to be used in purchases or services.                |
| 📇 Contacts / Addresses    |                                                                                   |
| Contacts → New Contact/Address | Add a contact person or additional address related to a third party.             |
| Contacts → List                | View all saved contacts and addresses, searchable by company or type.            |
| Contacts → Prospects           | Filter contact list to show only those related to prospects.                      |
| Contacts → Customers           | Filter contact list to show only those associated with customers.                 |
| Contacts → Vendors             | Filter contact list to show only vendor-related contacts.                         |
| Contacts → Other               | Contacts not directly tied to the above categories (e.g., partners, misc).        |

---
### 2.5 Billing

Professional invoicing for customers and vendors.
**Workflows:** Invoices, Templates, Payments, Tax Management, Recurring Bills
## 📄 Summary Table – Billing & Special Financial Transactions

| **Module / Feature**               | **Purpose / Use**                                                                 |
|------------------------------------|-----------------------------------------------------------------------------------|
| 💳 Billing                         |                                                                                   |
| 📄 Customer Invoices               |                                                                                   |
| Customer Invoices → New Invoice       | Create a new sales invoice for a customer. Can be linked to orders or proposals. |
| Customer Invoices → List              | View and manage all customer invoices (draft, validated, paid, overdue).         |
| Customer Invoices → List of Templates | Use predefined invoice templates for quicker billing.                            |
| Customer Invoices → Payments          | Record customer payments received for issued invoices.                           |
| Customer Invoices → Statistics        | Analyze sales billing data – totals, trends, outstanding balances.               |
| 🧾 Vendor Invoices                 |                                                                                   |
| Vendor Invoices → New Invoice         | Enter a new invoice received from a supplier/vendor.                             |
| Vendor Invoices → List                | View all vendor bills with due dates, payment status, and related documents.     |
| Vendor Invoices → List of Templates   | Use saved templates for recurring vendor invoice formats.                        |
| Vendor Invoices → Payments            | Record payments made to vendors.                                                 |
| Vendor Invoices → Statistics          | Analyze purchasing spend, vendor billing trends, and payment delays.             |
| 🧮 Billable Orders                | View customer orders eligible to be invoiced but not yet billed.                  |
| 🎁 Donations                    | Record financial or in-kind donations for NGOs or CSR reporting.                  |
| 🏛 Taxes & Special Expenses       |                                                                                   |
| Social/Fiscal Taxes                  | Manage regulatory payments like TDS, EPF, income tax, corporate tax, etc.        |
| IGST / CGST / SGST                  | Record and manage GST components as per Indian tax laws.                          |
| 👥 Salaries                      | Maintain employee salary disbursement records with optional linkage to payroll.  |
| 🧾 Loans & Misc. Payments         | Record business loans or irregular payments under special expense categories.     |
| 📊 Margins                       | Track margins per transaction or customer/project for profitability insights.     |

---
### 2.6 Banking

Track cash flow and reconcile accounts.
**Workflows:** Bank Creation, Entries, Transfers, POS, Stripe Integration
## 📄 Summary Table – Banking, POS, and Stripe

| **Module / Feature**                  | **Purpose / Use**                                                                 |
|--------------------------------------|-----------------------------------------------------------------------------------|
| 🏦 Banking – Banks / Cash             |                                                                                   |
| Banks / Cash → New Financial Account | Create a new bank account, cash register, or online wallet (e.g., Stripe, PayPal).|
| Banks / Cash → List                  | View all financial accounts created within the system.                            |
| Banks / Cash → List Entries          | Review all individual transactions per account — deposits, withdrawals, fees.     |
| Banks / Cash → List Entries by Category | Filter transactions based on categories (sales, purchases, salaries, etc.).     |
| Banks / Cash → Internal Transfer     | Transfer funds between internal accounts (e.g., Bank → Cash, Bank A → Bank B).    |
| Banks / Cash → Payment by Direct Debit | Record customer payments collected via direct debit.                            |
| Banks / Cash → Payment by Credit Transfer | Record vendor or employee payments made via bank transfer.                    |
| Banks / Cash → Deposit Slips         | Generate and track bank deposit slips for cash/check deposits.                    |
| 🧾 POS Cash Control                  |                                                                                   |
| POS Cash Control → New Cash Control | Log POS opening or closing balance, used for daily cash register audits.          |
| POS Cash Control → List             | View and manage all POS cash control logs across dates and locations.             |
| 💳 Stripe Integration               |                                                                                   |
| Stripe Account → List of Stripe Payouts | View and reconcile Stripe payments and automated transfers to your bank account.|

---

### 2.7 Accounting

Maintain journals, ledgers, P\&L, and fiscal compliance.
**Workflows:** Sales, Purchases, Expense Reports, Trial Balance, Closure
## 📄 Summary Table – Accounting & Reporting

| **Module / Feature**                    | **Purpose / Use**                                                                 |
|-----------------------------------------|-----------------------------------------------------------------------------------|
| 📘 Accounting – Core Entries & Journals |                                                                                   |
| Transfer in Accounting                  | Initiate the transfer of financial documents (invoices, expenses) into accounting.|
| Customer Invoice Binding                | Link customer invoices to appropriate accounting entries/accounts.                |
| Vendor Invoice Binding                  | Link supplier/vendor invoices to accounting.                                      |
| Expense Report Binding                  | Bind employee expense reports to general ledger accounts.                         |
| Recording in Accounting                 | Finalize accounting entries after verification (journal posting).                 |
| Sales (Sale Journal)                    | View and manage accounting entries from customer sales and invoices.              |
| Purchases (Purchase Journal)            | Track accounting records of all vendor purchases and bills.                       |
| Bank (Bank Journal)                     | Reflect bank transactions — deposits, payments, fees, transfers.                  |
| Expense Reports (Expense Report Journal)| Maintain records of employee expenses categorized for accounting.                 |
| 📂 Source Document Export & Ledger     |                                                                                   |
| Export Source Documents                 | Export invoices, expenses, or other documents to external systems (CSV, etc.).    |
| 📒 Accounting Reports                  |                                                                                   |
| Ledger                                  | View full general ledger showing all debit/credit entries by account.             |
| Journals                                | Browse entries by journal type (sales, purchase, bank, cash, etc.).              |
| Account Balance                         | See balances of individual accounts (assets, liabilities, income, expenses).      |
| Export Accountancy                      | Export full accounting data for third-party systems or audits.                    |
| Closure                                 | Perform fiscal year or period closing operations (lock entries, finalize books).  |
| 📊 Reporting                           |                                                                                   |
| Reporting                               | Generate key accounting reports: balance sheet, P&L, trial balance, etc.          |

---
### 2.8 Document Management

Centralized file system tied to modules.
**Workflows:** Manual Directories, Object Linked Folders
## 📄 Summary Table – Document Management

| **Module / Feature**        | **Purpose / Use**                                                                 |
|-----------------------------|-----------------------------------------------------------------------------------|
| 📂 Document Management (DMS / ECM) |                                                                               |
| DMS/ECM Area                 | Centralized space to manage all uploaded documents across the system (PDFs, images, contracts, etc.). |
| Manual Directories          | Create custom folders manually to organize internal or shared company files.     |
| Object Directories          | Automatically generated folders linked to Dolibarr objects (e.g., customers, invoices, projects), allowing contextual file storage. |

---
### 2.9 Agenda

Shared calendar for events, reminders, and team tasks.
**Workflows:** Events, Calendar Views, Resource Booking
## 📄 Summary Table – Agenda & Scheduling

| **Module / Feature**             | **Purpose / Use**                                                                 |
|----------------------------------|-----------------------------------------------------------------------------------|
| 🗓 Agenda – Events & Calendar    |                                                                                   |
| Events → New Event               | Create a new calendar event — meetings, tasks, calls, deadlines, etc.             |
| Events → List                    | View all created events with filters (date, user, type, project, etc.).           |
| Events → My Incomplete Events    | Shows user's upcoming or overdue events not yet marked as completed.              |
| Events → My Terminated Events    | Shows user's past events that are marked as completed.                            |
| Events → All Incomplete Events   | Displays all pending events across all users and teams.                           |
| Events → All Terminated Events   | Displays all completed events company-wide.                                       |
| 📅 Calendar View                |                                                                                   |
| Calendar → My Incomplete Events  | Calendar-style view of user's upcoming/pending events.                            |
| Calendar → My Terminated Events  | Calendar view showing user's completed events.                                    |
| Calendar → All Incomplete Events | Calendar view of all pending events for teams/departments.                        |
| Calendar → All Terminated Events | Calendar view showing completed events across the company.                        |
| 📊 Reporting                    |                                                                                   |
| Reporting                        | Generate event and calendar-based reports — by user, type, status, and time.      |
| 🧰 Resources                    |                                                                                   |
| Resources → New Resource         | Add a new shared resource (room, device, vehicle) that can be booked for events.  |
| Resources → List                 | View all resources available for scheduling and usage tracking.                   |

---

### 2.10 Tickets

Internal/external issue tracking and support documentation.
**Workflows:** Tickets, My Tickets, Knowledge Base, Categories
## 📄 Summary Table – Support & Tools

| **Module / Feature**           | **Purpose / Use**                                                                 |
|--------------------------------|-----------------------------------------------------------------------------------|
| 🎫 Tickets – Support & Issue Tracking |                                                                               |
| 📚 Knowledge Base              |                                                                                   |
| New Article                    | Create a help/support article for internal staff or end-users.                    |
| List of Articles               | View and manage all knowledge base content, with filters by topic or date.        |
| Tags/Categories (KB)           | Organize articles into searchable categories and tags for easy reference.         |
| 🆘 Ticketing System            |                                                                                   |
| New Ticket                     | Create a new support or service request — internal or customer-facing.            |
| List                           | View all tickets — open, pending, resolved, or closed.                            |
| My Tickets                     | Display tickets assigned to the logged-in user for resolution.                    |
| Statistics                     | Analyze ticket volumes, response/resolution times, and team performance.          |
| Tags/Categories (Tickets)      | Classify tickets by issue type, department, product, or urgency.                  |

---
### 2.11 Tools

Includes imports/exports, polls, mass emails, logs, and BI reports.
**Workflows:** Email Templates, Poll Creation, Barcode Printing

---
## 📄 Summary Table – Tools & Utilities

| **Module / Feature**        | **Purpose / Use**                                                                 |
|-----------------------------|-----------------------------------------------------------------------------------|
| 🛠 Tools – Utilities & Configurations |                                                                           |
| 🏷 Tags / Categories          | Create and manage reusable tags/categories used across modules (e.g., products, tickets, articles) to improve filtering and classification. |
| ✉ Email Templates            | Create predefined email templates for quick, consistent communication (used in proposals, invoices, support, etc.). |
| 📢 Mass Emails               |                                                                                   |
| New Mass Email               | Draft and send bulk emails to selected users, customers, or prospects.            |
| List                         | View history and status of all mass email campaigns (sent, scheduled, drafts).    |
| 📥 Imports / Exports         |                                                                                   |
| New Import                   | Import data into Dolibarr from CSV or other supported formats (e.g., products, third parties, invoices). |
| New Export                   | Export Dolibarr data for backup, reporting, or integration purposes.              |
| 📊 Polls                    |                                                                                   |
| New Poll                     | Create an internal or external survey/poll for team feedback or decision-making.  |
| List                         | View all active, closed, or scheduled polls and their responses.                  |
| 📈 BI – Custom Reports       | Build or view custom business intelligence reports using Dolibarr’s built-in reporting tool. |
| 🏷 Print Barcodes            | Generate and print barcode labels for products, inventory items, or assets.       |
| 🔐 Unalterable Logs          | View secure, non-editable logs for sensitive system events and data changes — used for audits and compliance. |

---

## 3. Benefits & Limitations

### ✅ Advantages for Stakeholders

1. No Installation (Cloud)
2. Automatic Data Backups
3. Role-based User Access
4. GDPR Compliant
5. Custom Domain Options
6. Customizable & Scalable
7. Free Self-Hosted Setup
8. Unlimited Users

### ⚠ Limitations

1. UI design not modern like Zoho/Odoo
2. Performance depends on server config
3. Slower queries under load
4. Disk space limited on cloud plans

---

## 4. Suggestions & Recommendations

| Use Case                   | Recommendation     |
| -------------------------- | ------------------ |
| Intern Training / Demo     | ✅ DoliCloud (SaaS) |
| No IT Team / Server Skills | ✅ Cloud-Hosted     |
| Custom Long-Term Workflow  | ✅ Self-Hosted      |
| High Storage / Performance | ✅ Self-Hosted      |

---

## 5. Interconnected Modules in Dolibarr

| Module           | Connected With                    | Interaction Notes                              |
| ---------------- | --------------------------------- | ---------------------------------------------- |
| Products         | Sales, Purchases, Stock, Projects | Auto-fill invoices, adjust stock, reporting    |
| Third Parties    | Orders, Invoices, Projects        | CRM-to-accounting linkage                      |
| Projects & Tasks | Agenda, Invoices, Timesheets      | Track & bill time, schedule deliverables       |
| Invoicing        | Accounting, Bank, Orders          | Real-time ledger updates                       |
| Stock            | Orders, Inventory, Alerts         | Real-time adjustments, low-stock warnings      |
| Agenda           | Projects, Contracts, Tasks        | Deadlines, team sync                           |
| HR / Users       | Timesheets, Leave, Payroll        | Employee tracking, linked to tasks and finance |
| DMS              | All Modules                       | Module-specific document folders               |

---

## 6. Data Extraction for Analysis

### Option 1: Direct SQL Access (Advanced)

* Tools: phpMyAdmin, DBeaver
* Tables: `llx_societe`, `llx_product`, `llx_facture`, `llx_commande`, `llx_projet`, `llx_user`

### Option 2: UI Export (No-Code)

* Export Lists → CSV or Excel
* Use Excel, Power BI, Tableau for analysis

### Option 3: REST API

* Pull real-time data into external dashboards
* Automate reporting and integrations

### Analysis Use Cases

* Sales Trends
* Top Products
* Project Time Logs
* Client Reports
* HR Metrics
* Financial Health

---

### 📎 Demo Link: [Dolibarr Public Demo](https://demo.dolibarr.org/public/demo/index.php)

### 📧 Feedback & Queries: [vinod.tems@gmail.com](mailto:vinod.tems@gmail.com)
