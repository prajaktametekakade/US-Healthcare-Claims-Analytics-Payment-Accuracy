# US Healthcare Claims Analytics & Payment Accuracy

## Project Overview

This project analyses a synthetic US healthcare claims dataset using Power BI to evaluate claims performance, payment accuracy, denial trends, and follow-up requirements.

The objective is to identify payment gaps, understand denial patterns, monitor outstanding claims, and provide actionable business insights that can support healthcare revenue cycle management (RCM).

## Business Objectives

- Analyse overall healthcare claims volume and financial performance.
- Compare billed, allowed, and paid amounts.
- Identify payment gaps and potential payment exceptions for investigation.
- Monitor claim outcomes and denial rates.
- Analyse denial trends across insurance types and denial reasons.
- Evaluate follow-up requirements and accounts receivable (AR) status.
- Support data-driven decisions through interactive dashboards.

## Tools & Technologies

- **Power BI Desktop** – Data modelling, DAX measures, visualisation and dashboard development.
- **Microsoft Excel** – Dataset review and preparation.
- **Power Query** – Data cleaning and transformation.
- **DAX** – KPI calculations and analytical measures.
- **Draw.io** – Healthcare claims lifecycle process flow.
- **JIRA concepts** – Business analysis and requirement tracking.
- **Microsoft Word** – BRD, FRD, data dictionary, business rules and UAT documentation.

## Dataset Overview

- Dataset: Synthetic US healthcare claims data
- Total records: 1,000 claims
- Period covered: January–December 2024
- Includes claim, provider, patient, financial, insurance, status, outcome and follow-up information.
- No real patient information or protected health information (PHI) is used.

## Dashboard Pages

### 1. Executive Overview
- Total claims and financial KPIs
- Billed, allowed and paid amounts
- Overall payment rate
- Denial and follow-up rates
- Monthly claims trend
- Claims and financial comparison by insurance type

### 2. Denial & Payment Analysis
- Claims by outcome
- Denial rate by insurance type
- Follow-up claims by AR status
- Top reasons for denied claims
- Payment gap by insurance type

### 3. Claim Investigation & Payment Exceptions
- Claim-level investigation using Claim ID filters
- Payment exception flags
- Financial validation
- Claim status and outcome review
- Detailed claim-level financial information

## Key Business Findings

| KPI | Result |
|---|---:|
| Total Claims | 1,000 |
| Total Billed Amount | $297,191 |
| Total Allowed Amount | $223,112 |
| Total Paid Amount | $200,754 |
| Payment Gap | $22,358 |
| Overall Payment Rate | 90.0% |
| Denial Rate | 33.1% |
| Follow-up Rate | 52.2% |

### Key Observations

- The overall payment rate is 90.0%, based on total paid amount divided by total allowed amount.
- The dataset shows a payment gap of $22,358 between allowed and paid amounts.
- A total of 331 claims have a Denied outcome.
- Follow-up is required for 52.2% of claims.
- Self-Pay has the highest denial rate among the four insurance categories.
- Incorrect billing information is the most frequent recorded denial reason.
- Some denied-outcome records also contain positive paid amounts and require further investigation.

## Business Recommendations

1. Review claims with outstanding payment gaps.
2. Investigate denied claims and prioritise recurring denial reasons.
3. Strengthen billing information validation before claim submission.
4. Monitor follow-up requirements and AR status regularly.
5. Review claim status and outcome inconsistencies using agreed business definitions.
6. Use payment exception flags to prioritise claims for manual investigation.

## Business Analysis Deliverables

This project includes:

- Business Requirements Document (BRD)
- Functional Requirements Document (FRD)
- Data Dictionary
- Business Rules Register
- Healthcare Claims Lifecycle Process Flow
- Power BI Dashboard
- User Acceptance Testing (UAT) Test Results
- Project Summary and Business Insights

## Important Data Limitation

This project uses synthetic data for learning and portfolio demonstration. The payment gap represents the difference between allowed and paid amounts; it does not automatically indicate an underpayment or recoverable revenue.

Payment exception flags identify records for investigation and do not establish confirmed payment errors. The findings do not represent actual payer policies or real-world healthcare claims performance.

## Project Outcome

The project demonstrates the application of healthcare domain knowledge, business analysis practices, data validation, KPI development, dashboard reporting and UAT in a healthcare revenue cycle management use case.
