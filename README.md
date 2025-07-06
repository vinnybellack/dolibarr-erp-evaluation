# Dolibarr ERP Explained: Features, Workflows & Data Access

## 1. Overview of Dolibarr ERP System

Dolibarr is an open-source ERP and CRM system designed to help businesses of all sizes manage operations from a unified platform. It integrates HR, sales, finance, inventory, and project management with modular flexibility and ease of use.

### Why Dolibarr Stands Out

* All-in-one platform for multiple business operations.
* No need for separate tools or complex integrations.
* Easy setup and modular scalability.

### Easy to Customize

* Built-in Module Builder for low-code customization.
* Plugin marketplace (Dolistore) and developer-friendly extensions.

### Hosting Options

* **Self-hosted**: Ideal for custom workflows, full control.
* **Cloud-based**: Fast setup, automatic backups, and updates.

### Cloud Hosting Providers

* DoliCloud (official)
* DoliPlace, DoliOnDemand, Ma Gestion Cloud, DoliBox, DoliPlatform, BitNami, UnboxCRM

### Demo Options

* Dedicated Instance
* Shared Public Demo

## 2. Summary of Key Modules & Their Functions

### 2.1 HR, Attendance & Leave Management

* Manage employee records, leave, attendance, expenses, recruitment.
* Subsections: Leave requests, Expense reports, Time tracking, Recruitment.

### 2.2 Communication

* Internal messaging, approvals, task updates.
* Integrated across sales, HR, and support functions.

### 2.3 Projects & Tasks

* Create and manage projects, assign tasks, track time and progress.
* Subsections: Leads, Projects, Tasks, Time logs.

### 2.4 Sales & Lead Generation (Third Parties)

* Manage leads, clients, quotes, sales orders, vendors.
* Subsections: Third parties, Prospects, Customers, Vendors, Contacts.

### 2.5 Billing

* Generate invoices, track payments, apply taxes.
* Subsections: Customer & Vendor Invoices, Recurring billing, Templates.

### 2.6 Banking

* Manage bank accounts, reconcile statements, POS, deposits.
* Subsections: Bank accounts, Transfers, Payments, POS cash control, Stripe payouts.

### 2.7 Accounting

* General ledger, journals, reports, compliance.
* Subsections: Journals, Transfers, Bindings, Ledger, Export.

### 2.8 Document Management

* Centralized storage linked to modules.
* Subsections: DMS/ECM area, Manual & Object directories.

### 2.9 Agenda

* Calendar of events, tasks, meetings.
* Subsections: Events, My/All Events, Reporting, Resources.

### 2.10 Tickets

* Issue tracking for support requests.
* Subsections: Tickets, Knowledge Base, Tags/Categories.

### 2.11 Tools

* Utilities such as imports, exports, notes, email campaigns, barcodes.
* Subsections: Mass Email, Polls, BI Reports, Logs.

## 3. Advantages for Stakeholders

1. No installation required (cloud).
2. Automatic updates and daily backups.
3. Role-based access control.
4. GDPR compliance.
5. Customizable and scalable.
6. Free self-hosting option.
7. Unlimited users.

## 4. Limitations

* UI is less modern compared to competitors.
* Performance may vary based on server resources.
* Limited disk space in basic cloud plans.

## 5. Suggestions & Recommendations

| Use Case                     | Recommendation        |
| ---------------------------- | --------------------- |
| Intern setup / short-term    | Use Cloud (DoliCloud) |
| No IT/server expertise       | Use Cloud             |
| Long-term with custom needs  | Self-hosted           |
| High storage or data scaling | Self-hosted           |

## 6. Interconnected Modules in Dolibarr

* Sales linked with Products, Orders, and Invoices.
* Projects integrated with Tasks, Timesheets, Agenda.
* Accounting tied to Invoices, Payments, Banking.
* Document Management accessible across modules.

## 7. Data Access & Analytics

### 1. Direct SQL Access

* Access via phpMyAdmin, DBeaver, etc.
* Key Tables: `llx_societe`, `llx_product`, `llx_facture`, `llx_commande`, `llx_projet`, `llx_user`

### 2. UI Export

* Export CSV/Excel from module list views.

### 3. API Access

* Use REST API for real-time integration and automation.

### Analytics Use Cases

* Sales trends
* Top products
* Client activity
* HR reports
* Financial dashboards

---

*Prepared by Vinod Balakrishnan — [vinod.tems@gmail.com](mailto:vinod.tems@gmail.com)*
