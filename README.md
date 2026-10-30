# Retail Privacy Operations & GDPR Compliance Framework

A practical simulation of GDPR privacy operations within an Irish retail organisation.

---

## 1. Project Overview

This project simulates the day-to-day operations of a Data Privacy function within a fictional Irish retail organisation, **Harbour & Lane Retail**.

The organisation operates physical retail stores and an ecommerce platform, collecting and processing customer and employee information through sales transactions, customer loyalty programmes, online accounts, marketing activities, and customer service interactions.

The objective is to design a practical GDPR privacy operations framework that supports the administration, tracking, documentation, and oversight of data protection activities in accordance with the EU General Data Protection Regulation (GDPR) and Ireland's Data Protection Act 2018.

The project focuses on the operational responsibilities of a Junior Privacy Analyst, including:
* Managing data subject rights requests
* Maintaining privacy registers
* Coordinating internal queries
* Supporting privacy assessments
* Preparing management reports

*Note: All scenarios, records, and datasets are fictional and created exclusively for demonstration purposes.*

---

## 2. Business Scenario

Harbour & Lane Retail receives privacy-related requests through multiple channels, including email, customer service, and its ecommerce platform.

The Data Privacy team needs a consistent approach to:
* **Record and acknowledge** incoming privacy requests.
* **Identify and categorise** data subject rights requests.
* **Coordinate information gathering** across relevant departments.
* **Monitor statutory response deadlines**.
* **Document privacy incidents** and escalate potential risks.
* **Maintain DPIA records** and track mitigation actions.
* **Provide management visibility** into privacy operations.

This project establishes a simulated operational framework to address these requirements.

---

## 3. Project Objectives

* **Data Subject Rights Management:** Develop a centralised register for tracking access, rectification, erasure, restriction, portability, and objection requests.
* **Privacy Mailbox Management:** Establish a structured process for receiving, acknowledging, categorising, and routing privacy-related queries.
* **Privacy Record Management:** Maintain structured registers for requests, incidents, and Data Protection Impact Assessments.
* **Privacy Risk Assessment:** Simulate a DPIA for a retail customer loyalty programme, identifying processing activities, potential risks, and mitigation measures.
* **Operational Reporting:** Develop a dashboard to monitor request volumes, outstanding actions, response timelines, and privacy incidents.
* **Privacy Awareness:** Develop supporting documentation to promote GDPR awareness and consistent handling procedures.

---

## 4. Project Deliverables

### 4.1 Data Subject Rights Request (DSAR) Management
Design a centralised DSAR register to manage customer privacy requests throughout their lifecycle.

**Register Data Fields Captured:**
* Unique request reference
* Request received date and channel
* Request category and description
* Identity verification status, where appropriate
* Assigned department and responsible contact
* Statutory response deadline
* Request status and outstanding actions
* Escalation and extension records
* Completion date and closure notes

> The workflow incorporates GDPR Article 12 requirements, including the general one-month response period and applicable extension provisions.

### 4.2 Privacy Mailbox Management
Design a standard operating procedure (SOP) for handling incoming privacy-related communications.

**Workflow Coverage:**
1. Receipt and acknowledgement of requests
2. Initial categorisation and prioritisation
3. Identification of the relevant data subject right
4. Routing requests to appropriate internal departments
5. Assignment of ownership and follow-up actions
6. Deadline monitoring and escalation
7. Documentation and closure

### 4.3 Privacy Incident Management
Develop a privacy incident register to document and monitor suspected personal data breaches.

**Register Data Fields Captured:**
* Incident reference and discovery date
* Incident description and source
* Categories of personal data potentially affected
* Estimated number of affected individuals
* Initial containment actions
* Risk assessment status
* Escalation and management review
* Notification decision and supporting rationale
* Corrective and preventive actions

> The framework reflects GDPR Articles 33 and 34, including applicable supervisory authority notification and data subject communication requirements.

### 4.4 Data Protection Impact Assessment (DPIA)
Conduct a simulated DPIA for the introduction of a customer loyalty programme.

**Assessment Scope:**
* Personal data collected and processed
* Processing purposes and scope
* Categories of data subjects
* Data collection and sharing arrangements
* Data retention and access arrangements
* Potential privacy risks to individuals
* Risk likelihood and impact
* Proposed technical and organisational safeguards
* Residual risk and outstanding actions

> The assessment follows the Irish Data Protection Commission's (DPC) DPIA guidance and GDPR Article 35.

### 4.5 Privacy Operations Dashboard
Develop a Power BI dashboard to provide an overview of the organisation's privacy activities.

**Reporting Metrics:**
* Total privacy requests received
* Request volumes by category
* Open, completed, and overdue requests
* Average request resolution time
* Requests approaching their response deadlines
* Privacy incidents by category and severity
* DPIA assessment and mitigation action status

---

## 5. Technology Stack

| Technology | Application |
| :--- | :--- |
| **Microsoft Excel** | Privacy registers, request tracking, and structured records |
| **Power BI** | Privacy operations dashboard and reporting |
| **Microsoft Word / Markdown** | DPIA documentation, procedures, and awareness materials |
| **GDPR / Data Protection Act 2018** | Regulatory framework |
| **Git / GitHub** | Version control and project documentation |

---

## 6. Repository Structure

```text
retail-privacy-operations-gdpr/
│
├── README.md
│
├── data/
│   ├── dsar_requests.csv
│   ├── privacy_incidents.csv
│   ├── dpia_risk_register.csv
│   └── departments.csv
│
├── registers/
│   ├── dsar_management_register.xlsx
│   ├── privacy_incident_register.xlsx
│   └── dpia_action_register.xlsx
│
├── workflows/
│   ├── privacy_mailbox_sop.md
│   ├── dsar_handling_procedure.md
│   └── incident_escalation_procedure.md
│
├── assessments/
│   └── customer_loyalty_programme_dpia.md
│
├── dashboard/
│   └── privacy_operations_dashboard.pbix
│
├── awareness/
│   └── gdpr_awareness_guide.md
│
└── references/
    └── regulatory_resources.md
