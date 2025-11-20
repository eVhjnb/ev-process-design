# ev-process-design

Process and system design portfolio for a service operations and analytics ecosystem.

This repository showcases:

- End-to-end value chain design (Level 0)
- Domain-level process architecture (Level 1)
- Core processes modeled at a more detailed level (Level 2)

The models describe an anonymized company **("ServiceCo")**, a remote services / operations 
organization with:

- Recruitment and talent operations
- Finance and billing
- HR and people processes
- Service delivery and incident management
- Data & analytics (scorecards, KPIs, automation)

The goal is to demonstrate process architecture skills rather than expose 
any confidential information. All company names are anonymized.

---

## Levels

- **Level 0 – Value Chain**  
  High-level view of ServiceCo’s value chain (from demand generation to service delivery, billing and retention).

- **Level 1 – Domains**  
  Main process domains:
  - Finance
  - Recruitment
  - HR
  - Operations / Service Delivery

- **Level 2 – Core Processes**  
  Detailed views of selected key processes, for example:
  - Invoice-to-Cash
  - Vendor Payments
  - Budgeting Cycle
  - Recruitment Pipeline
  - Onboarding / Offboarding
  - Incident Management

---

## Relation to other repositories

These processes connect directly to the technical implementation:

- **ev-kpi-factory**  
  Python-based KPI factory using DWH + scheduled jobs + Google Sheets.

- **ev-airtable-webhooks**  
  Forms and operational data ingestion via Airtable automations and webhooks.

- **ev-sql-toolkit**  
  Business logic and KPI definitions in SQL.

- **ev-excel-analytics**  
  Advanced Excel tools for operational analytics and forecasting.

This repository focuses on the **process architecture** that underpins those 
technical implementations.
