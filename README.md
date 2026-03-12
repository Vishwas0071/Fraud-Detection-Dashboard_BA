# Project 04 — Fraud Detection Dashboard
### Domain: Risk & Compliance / Banking | Role: Business Analyst

---

## Overview
A private sector bank's fraud team was detecting fraud manually 
through Excel, resulting in a 4-hour average response time and a 
22% year-on-year increase in fraud losses. This project covers BA 
documentation for a real-time ML-powered fraud detection and case 
management dashboard targeting sub-45-minute detection response.

---

## Business Objective
- Reduce fraud detection response time from 4 hours to 45 minutes
- Achieve false positive rate below 5%
- Ensure 100% audit trail coverage for all analyst actions
- Achieve full RBI fraud reporting compliance

---

## Scope
- Real-time transaction monitoring with ML fraud risk scoring (0-100)
- Automated color-coded alert generation and escalation
- Fraud analyst case management workflow with mandatory documentation
- Customer card block notification and OTP re-verification
- Immutable audit trail for every analyst action
- Daily fraud summary and monthly trend reporting

---

## Epics Covered
| Epic | User Stories |
|------|-------------|
| Real-Time Monitoring | FD-001 |
| Alert System | FD-002 |
| Case Management | FD-003 |
| Customer Communication | FD-004 |

---

## Key Business Rules
- Score 80-89: Yellow flag — analyst alert
- Score 90-94: Orange flag — high priority alert to team lead
- Score 95+: Red flag — auto-block + customer SMS within 60 seconds
- All high-risk alerts reviewed within 2 hours
- Mandatory note required before any case action
- Cases breaching SLA auto-escalated to senior officer
- Fraud data retained 7 years per RBI mandate

---

## Fraud Risk Triggers
- Transaction from unrecognized device or location
- Multiple transactions within 60-second window
- Amount 3x higher than 30-day customer average
- International transaction with no travel history
- Transaction within 10 minutes of a password reset

---

## UAT Coverage
8 test cases covering risk score flagging, auto-block, mandatory 
note enforcement, SLA escalation, card block SMS, and audit trail.

---

## Compliance
RBI Fraud Reporting Guidelines | RBAC Security Requirements

---

## Tools Used
Jira | Figma | Lucidchart | Agile Scrum

---

## Document
[View Full BA Document (PDF)](./Project04_Fraud_Detection_Dashboard.pdf)
