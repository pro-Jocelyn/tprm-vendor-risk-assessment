# Third-Party Risk Management Assessment: Cloud Lending Solutions

## Project Overview

This project is a Third Party Risk Management (TPRM) and Cloud Governance assessment for a fictional financial institution, Prairie State Community Bank, that is evaluating Cloud Lending Solutions as a new cloud based SaaS loan processing vendor.

The assessment focuses on identifying vendor risk, evaluating security controls, documenting findings, and making a risk based vendor approval recommendation.

## Scenario

Prairie State Community Bank is a regional financial institution seeking to modernize its consumer loan processing operations. The bank is considering Cloud Lending Solutions, a cloud based SaaS platform that allows customers to submit loan applications, upload documents, track application status, and communicate with loan officers.

Because the vendor processes and stores sensitive customer financial information, the bank must perform a vendor risk assessment before onboarding the vendor.

## Vendor Being Assessed

**Vendor Name:** Cloud Lending Solutions
**Service Provided:** Cloud based loan processing platform
**Cloud Service Model:** SaaS
**Industry:** Financial Technology
**Business Function Supported:** Consumer loan processing
**Data Handled:** Customer PII, Social Security Numbers, income information, credit history, bank account information, and loan application documents

## Frameworks and Concepts Used

This project incorporates concepts from:

* Third Party Risk Management
* Cloud Governance
* Shared Responsibility Model
* NIST SP 800-53
* NIST CSF 2.0
* CSA Cloud Controls Matrix
* GLBA and financial services regulatory considerations
* CIA Triad: Confidentiality, Integrity, and Availability

## Project Deliverables

The Excel workbook includes the following assessment tabs:

1. **Vendor Inventory Profile**
   Documents vendor details, business owner, service description, data classification, cloud service model, regulatory considerations, and initial risk rating.

2. **Inherent Risk Assessment**
   Scores the vendor’s risk before reviewing controls based on data sensitivity, business criticality, regulatory impact, system access, and vendor dependency.

3. **Security Questionnaire**
   Assesses vendor controls across access management, data protection, incident response, business continuity, vulnerability management, integrity controls, compliance assurance, and cloud governance.

4. **Risk Findings Register**
   Tracks identified findings, severity, risk impact, remediation recommendations, owner, target due date, and status.

5. **Final Recommendation**
   Provides the final vendor decision and conditional approval requirements.

## Inherent Risk Summary

Cloud Lending Solutions was rated as **High Inherent Risk** because the vendor:

* Processes sensitive customer financial information
* Stores and transmits confidential data
* Supports a critical banking function
* Operates in a regulated financial services environment
* Uses a vendor managed SaaS cloud environment
* Creates operational, regulatory, financial, and reputational risk if controls fail

## Key Findings

| Finding ID | Finding                                                                       | Severity |
| ---------- | ----------------------------------------------------------------------------- | -------- |
| F-001      | MFA is not enforced for all user accounts                                     | High     |
| F-002      | No current SOC 2 Type II report is available                                  | Medium   |
| F-003      | Security incident notification timeframe is 72 hours                          | Medium   |
| F-004      | Critical vulnerability remediation timeframe is 30 days                       | Medium   |
| F-005      | Cloud configuration reviews are not performed on a defined recurring schedule | Medium   |

## Final Recommendation

**Decision: Approve with Conditions**

Cloud Lending Solutions has several acceptable security controls in place, including encryption, access reviews, backups, logging, penetration testing, disaster recovery testing, and privileged access monitoring. However, the assessment identified control gaps that require remediation and evidence review.

The vendor may be approved with conditions, provided the following requirements are met:

* MFA must be implemented for all user accounts within 30 days of contract signing.
* The vendor must provide a SOC 2 Type II roadmap or alternative independent assessment evidence within 90 days of onboarding.
* The contract must require 24 hour notification for confirmed incidents involving customer data.
* Critical vulnerabilities must be remediated within 15 days or formally risk accepted and tracked.
* Recurring cloud configuration reviews must be implemented and documented within 60 days of onboarding.

## Skills Demonstrated

This project demonstrates the ability to:

* Perform vendor intake and risk classification
* Conduct inherent risk scoring
* Build a vendor security questionnaire
* Evaluate vendor control responses
* Identify control gaps and assign severity
* Document risk findings and remediation requirements
* Apply cloud governance concepts to a SaaS vendor
* Make a risk based vendor approval recommendation
* Communicate risk in a business-friendly format

## File Included

* `TPRM Vendor Risk Assessment - Cloud Lending Solutions.xlsx`

## Note

This project uses a fictional company, fictional vendor, and synthetic assessment responses for portfolio and learning purposes.
