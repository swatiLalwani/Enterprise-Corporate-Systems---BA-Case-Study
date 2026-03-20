# 🏢 Enterprise Corporate Systems — BA Case Study

> **Role:** Business Analyst Lead
> **Timeline:** January 2024 – April 2024
> **Domain:** Enterprise / Corporate IT
> **Methodology:** Agile (8 Sprints) | Waterfall Documentation

---

## 📌 Project Overview

This project involved the **end-to-end business analysis and QA planning** for a new Enterprise Corporate Systems platform built to replace fragmented legacy tools across HR, Finance, and Operations.

The platform consolidates **8 core business modules** into a single integrated system, enabling streamlined employee lifecycle management, financial processing, and internal support operations.

---

## 🧩 Modules Covered

| # | Module | Key Functionality |
|---|--------|-------------------|
| 1 | **Employee Onboarding** | HR approval flow, asset provisioning, credential generation, payroll enrollment |
| 2 | **Leave & Attendance Management** | Leave types, balance validation, manager approval, payroll deduction |
| 3 | **Payroll Processing** | Full-time/part-time pay, tax deductions, payslip generation, Finance integration |
| 4 | **Vendor Management** | Compliance verification, registration, activation, performance ratings |
| 5 | **Invoice Processing** | 3-way match (Invoice vs PO vs GR), payment scheduling and release |
| 6 | **Procurement** | Tiered PR approvals (<$5K / $5K–$50K / >$50K), PO conversion, budget check |
| 7 | **Asset Management** | Asset allocation, transfer, return, quarterly depreciation reporting |
| 8 | **Internal Ticketing Tool** | SLA tracking, auto-assignment, escalation rules, mandatory closure fields |

---

## 📂 Deliverables

```
📁 Enterprise-Corporate-Systems-BA-Case-Study/
├── 📄 QA_Test_Plan.docx                   ← 15-section Software QA Test Plan (v1.0)
├── 📊 BA_Case_Study_Workbook.xlsx         ← 5-tab Excel workbook
│   ├── BRD - Enterprise Systems           ← 8 Business Requirements
│   ├── FSD - Enterprise Systems           ← ~30 Functional Requirements
│   ├── Test Condition Matrix              ← Module-by-module condition tables
│   ├── Test Scenarios & Cases             ← 8 scenarios, 33 test cases
│   └── Traceability Matrix                ← BRD → FR → TC → Status mapping
└── README.md
```

---

## 🗂️ BA Artifacts Breakdown

### 1. Business Requirements Document (BRD)
- 8 high-level business requirements (BRD_1 through BRD_8)
- Each requirement maps directly to a platform module
- Covers both positive flows (approvals, activations) and negative flows (rejections, blocks)

### 2. Functional Specification Document (FSD)
- ~30 granular functional requirements with structured FR IDs
- Examples: `Onboard_Employee_New`, `PR_Under5K_ManagerApproval`, `Invoice_3WayMatch_Fail`
- Each FR specifies system behavior, conditions, and downstream actions

### 3. Test Condition Matrix
- Module-specific condition tables with relevant test dimensions
- Columns vary by module context (e.g., approval flags, SLA status, match results, budget tiers)
- Positive TC and Negative TC classification for every condition

### 4. Test Scenarios & Test Cases
- **8 Test Scenarios** mapped to BRD modules
- **33 Test Cases** with full descriptions, positive and negative coverage
- Naming convention: `TC_Onboarding_1.1`, `TC_Payroll_3.2`, `TC_Ticket_8.5`, etc.

### 5. Traceability Matrix
- Full chain: **BRD → Functional Requirement → Test Case → Run Status → Defects**
- All 33 test cases linked and tracked
- Run status: PASS (baseline) with open Defects column for live tracking

---

## 📋 QA Test Plan Highlights

The QA Test Plan follows a standard 15-section STLC structure:

| Section | Content |
|---------|---------|
| Testing Strategy | Unit, SIT, System, UAT, Automated Regression |
| Test Environments | HRMS ↔ Payroll, Procurement ↔ ERP, Asset ↔ HRMS, Ticketing ↔ SLA Engine |
| Entry / Exit Criteria | Module-specific conditions for test start and sign-off |
| In Scope | All 8 modules with detailed functional boundaries |
| Out of Scope | Tax portals, third-party benefits, GL posting, physical maintenance |
| Risk & Mitigations | Payroll discrepancies, SLA clock sync, partial GR match edge cases |
| Defect Lifecycle | 11 statuses: New → Assigned → Open → In Progress → Fixed → Verified → Closed |
| Tools | Selenium, JIRA, Postman, Apache JMeter, Excel, Word |

---

## 🗓️ Project Timeline

```
Jan 2024   →  BRD & FSD Review, Test Plan, Test Scenarios
Feb 2024   →  Test Case Design, Software Quality Testing (Sprints 1–4)
Mar 2024   →  Performance & Load Testing, UAT, Pilot Release (Sprints 5–8)
Apr 2024   →  Deployment → Project Retrospective
```

---

## 💡 Key BA Skills Demonstrated

- ✅ Requirements elicitation and documentation (BRD, FSD)
- ✅ Test planning and STLC ownership (QA Test Plan, Entry/Exit Criteria)
- ✅ End-to-end traceability management (BRD → TC → Defect)
- ✅ Cross-functional stakeholder alignment (HR, Finance, IT, Operations)
- ✅ Agile delivery across 8 sprints with structured documentation
- ✅ Risk identification and mitigation planning
- ✅ Positive and negative test case design across 8 business domains

---

## 🛠️ Tools & Technologies

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)
![Word](https://img.shields.io/badge/Microsoft_Word-2B579A?style=flat&logo=microsoft-word&logoColor=white)
![JIRA](https://img.shields.io/badge/JIRA-0052CC?style=flat&logo=jira&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat&logo=selenium&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)

---

## 👤 Author

**BA Lead — Enterprise Systems Project**
*QA Test Plan v1.0 | January–April 2024*

---

> *This case study was developed as a structured BA portfolio project demonstrating end-to-end requirements and test planning for a multi-module enterprise platform.*
