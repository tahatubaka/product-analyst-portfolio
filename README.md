# Product Analyst Portfolio — Muhammad Taha Tubaka

Selected case studies from my work as a Product & Project Analyst in logistics technology: specifications, interactive prototypes, a PRD and QA testing.

> Client names and data in the screenshots are anonymized. Several projects were originally written in Indonesian; the screenshots show English versions.

| # | Case study | Role |
|---|---|---|
| 1 | [TMS Planning Order](#1-tms-planning-order-specification--interactive-prototype) | Specification, user flow, prototype |
| 2 | [Fleet Maintenance Module](#2-fleet-maintenance-module-prototype-with-in-app-guided-onboarding) | Module spec, prototype, onboarding guide |
| 3 | [Fleet Alarm & DO Risk Dashboard](#3-fleet-alarm-monitoring--do-risk-dashboard) | Meeting decisions → prototype |
| 4 | [HRIS Web & Mobile](#4-hris-web--mobile-mockup) | Approval flows, requirements, prototype |
| 5 | [PRD for an Operations Admin App](#5-product-requirements-document-prd-for-an-operations-admin-app) | PRD author |
| 6 | [Field & Driver Mobile Apps](#6-field-operations--driver-mobile-apps-interactive-prototype) | User flows, mobile prototype |
| 7 | [E-commerce QA Test Report](#7-qa-test-report-e-commerce-checkout--account-flows) | Test design, execution, reporting |

---

## 1. TMS Planning Order: Specification & Interactive Prototype

**Role:** Product Analyst — specification, user flow and HTML prototype
**Skills:** Product Requirements Document · Prototyping · Requirement Analysis · User Stories · Business Process Modeling

Planning screen for a Transportation Management System, where planners turn open delivery orders into truck manifests. I wrote the specification and built a clickable HTML prototype: order pool with overdue reasons, a fleet board by vehicle category (Reefer, Chiller, AC Dry), load clash detection and a 24-hour route timeline. I also modeled grouping orders by fleet category before route optimization to stop time-outs in the optimization engine.

![Planning Order fleet board](images/01-planning-order-fleet-board.png)
![Planning Order route timeline](images/01-planning-order-timeline.png)

## 2. Fleet Maintenance Module: Prototype with In-App Guided Onboarding

**Role:** Product Analyst — module specification, prototype and onboarding guide
**Skills:** Product Specification · Prototyping · Requirement Analysis · User Manual · Technical Documentation

Maintenance Control Advance (MCA) is the fleet maintenance module of a TMS: preventive schedules by KM milestone, field findings, work orders tracked by stage, and spare-part handover from warehouse to QC. I wrote the module specification and built the interactive prototype, including an in-app guide where a spotlight walks new users through the real screens with interactive quests, screen guides and a status glossary.

![MCA dashboard](images/02-mca-dashboard.png)
![MCA work orders](images/02-mca-work-orders.png)
![MCA in-app guide](images/02-mca-guide.png)

## 3. Fleet Alarm Monitoring & DO Risk Dashboard

**Role:** Product Analyst — turning UI/UX meeting decisions into a prototype
**Skills:** Prototyping · Requirement Analysis · Product Management · Business Process Modeling · User Stories

Realtime alarm monitoring for a fleet control tower team. Based on UI/UX meeting decisions, I restructured the dashboard into a per-alarm incident queue with SLA timers, acknowledge / assign / escalate actions and a live map, plus a DO risk view that scores deliveries on cargo security, route anomaly, driver safety and telematics signals. Delivered as an interactive HTML prototype for stakeholder review.

![Fleet incident queue](images/03-fleet-incident-queue.png)
![DO risk summary](images/03-fleet-do-risk-summary.png)

## 4. HRIS Web & Mobile Mockup

**Role:** Product Analyst — approval flows, requirements and prototype
**Skills:** Requirement Analysis · Business Process Modeling · Prototyping · User Stories · Product Documentation

HR information system with an employee mobile app and a web back office. Employees submit leave, overtime, cash advances, reimbursements and document requests in the app; managers and HR decide on the web. I mapped which requests stop at the manager and which continue to HR, designed the HR dashboard (queue ageing, advance and reimbursement funds, attendance, leave quota) and built the interactive prototype.

![HRIS employee app](images/04-hris-employee-app.png)
![HRIS HR dashboard](images/04-hris-hr-dashboard.png)

## 5. Product Requirements Document (PRD) for an Operations Admin App

**Role:** Product Analyst — PRD author
**Skills:** Product Requirements Document · Requirements Specification · Requirement Analysis · Requirement Management · Technical Documentation

PRD for the admin app that tracks GPS devices, accessories and GSM cards from purchasing to installation, replacing a legacy app of about 593 screens. Written from the approved BRD and stakeholder meetings: 173 functional and 12 non-functional requirements with MoSCoW priority, acceptance criteria per module, a BRD-to-PRD traceability matrix and an open-decision log with owners. The images show an English excerpt; the original document is in Indonesian.

![PRD module requirements](images/05-prd-module-requirements.png)
![PRD traceability matrix](images/05-prd-traceability.png)

## 6. Field Operations & Driver Mobile Apps: Interactive Prototype

**Role:** Product Analyst — user flows and mobile prototype
**Skills:** Prototyping · User Stories · Business Process Modeling · Requirement Analysis · Mobile App Testing

Two role-based mobile apps in one prototype: a field app for warehouse and yard staff (gate in, unloading with VIN scanning, put-away, offline queue) and a driver app (pre-trip check gate, assignment confirmation, digital delivery notes, e-POD per drop, trip allowance). The flows are built around real field constraints, such as weak signal and a mandatory pre-trip check before dispatch.

![Field and driver mobile apps](images/06-mobile-field-driver-apps.png)

## 7. QA Test Report: E-commerce Checkout & Account Flows

**Role:** QA Tester — test design, execution and reporting
**Skills:** Manual Testing · Software QA · Test Case Design · Bug Reports · Web Testing

End-to-end functional QA of a fashion e-commerce website (catalog, bag, checkout, customer account) on desktop and mobile. I designed 25 test cases with boundary values (stock and quantity caps) and negative inputs (whitespace-only fields, phone formats, invalid promo codes), checking browser storage after every step. Result: 18 passed, 7 failed, 9 findings, including orders accepted with blank names, cash on delivery allowed for worldwide shipping, and one customer's orders visible to the next. Each finding has steps, expected vs actual, evidence and a fix.

![QA summary matrix](images/07-qa-summary-matrix.png)
![QA critical findings](images/07-qa-critical-findings.png)
![QA medium and minor findings](images/07-qa-medium-minor.png)

---

**Contact:** [Upwork profile](https://www.upwork.com/freelancers/~0109d2c4a16710d7b3) · [GitHub](https://github.com/tahatubaka)
