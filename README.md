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

### 2.2 Communication

Facilitates messaging, approvals, notifications across Sales, HR, Support.
**Workflows:** Proposals, Orders, Contracts, Vendor Management, Subscriptions, Interventions

### 2.3 Projects & Tasks

Plan projects, assign tasks, track time, and analyze progress.
**Workflows:** Leads, Project Lists, Task Tracking, Time Logging

### 2.4 Sales & Lead Generation (Third Parties)

Central CRM for leads, clients, vendors, contacts.
**Workflows:** Third Party, Prospects, Customers, Vendors, Addresses

### 2.5 Billing

Professional invoicing for customers and vendors.
**Workflows:** Invoices, Templates, Payments, Tax Management, Recurring Bills

### 2.6 Banking

Track cash flow and reconcile accounts.
**Workflows:** Bank Creation, Entries, Transfers, POS, Stripe Integration

### 2.7 Accounting

Maintain journals, ledgers, P\&L, and fiscal compliance.
**Workflows:** Sales, Purchases, Expense Reports, Trial Balance, Closure

### 2.8 Document Management

Centralized file system tied to modules.
**Workflows:** Manual Directories, Object Linked Folders

### 2.9 Agenda

Shared calendar for events, reminders, and team tasks.
**Workflows:** Events, Calendar Views, Resource Booking

### 2.10 Tickets

Internal/external issue tracking and support documentation.
**Workflows:** Tickets, My Tickets, Knowledge Base, Categories

### 2.11 Tools

Includes imports/exports, polls, mass emails, logs, and BI reports.
**Workflows:** Email Templates, Poll Creation, Barcode Printing

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
