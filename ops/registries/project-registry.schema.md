# Project Registry Schema

Every operational request becomes a project record before execution.

## Required Fields

| Field | Purpose |
|---|---|
| Project ID | Stable internal identifier |
| Project Name | Human-readable project name |
| Client | Client or account |
| Location | City, state, site, or remote |
| Status | Intake, Active, Paused, Closed, Blocked |
| Priority | Low, Normal, High, Critical |
| Owner | Primary responsible person or agent |
| Start Date | Expected or confirmed start date |
| Due Date | Deadline if applicable |
| Roles Needed | Position titles |
| Headcount Needed | Total requested |
| Headcount Filled | Confirmed candidates/workers |
| Pay Rate | Worker pay rate |
| Bill Rate | Client bill rate if known |
| Source Links | Forms, sheets, job posts, docs |
| Risks | Operational, legal, payroll, client, candidate risks |
| Approval Required | Yes/No |
| Notes | Working context |

## Status Values

- Intake
- Active
- Paused
- Blocked
- Closed

## Priority Values

- Low
- Normal
- High
- Critical

## Rule

A project cannot move from Intake to Active until required approvals and minimum data are present.
