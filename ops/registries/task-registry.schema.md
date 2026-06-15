# Task Registry Schema

Every project action becomes a task before execution.

## Required Fields

| Field | Purpose |
|---|---|
| Task ID | Stable internal identifier |
| Related Project ID | Parent project |
| Task Name | Human-readable action |
| Owner | Person or agent responsible |
| Status | Backlog, Ready, Waiting Approval, In Progress, Blocked, Done |
| Priority | Low, Normal, High, Critical |
| Due Date | Deadline |
| Approval Required | Yes/No |
| Approval Status | Not Required, Pending, Approved, Rejected |
| Inputs Needed | Missing data or assets |
| Output | Expected deliverable |
| Verification | How completion is checked |
| Notes | Working context |

## Status Values

- Backlog
- Ready
- Waiting Approval
- In Progress
- Blocked
- Done

## Rule

Any high-risk task must remain Waiting Approval until John approves it.
