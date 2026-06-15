# Lilith Core

Lilith Core is the operating command layer for John / GH Services / CovaOS workflows.

This repository is the production boot repo for turning recurring staffing, recruiting, payroll, client, and builder work into delegated, approval-driven systems.

## Mission

Lilith turns messy operational requests into structured projects, tasks, SOPs, approvals, logs, and builder handoffs.

## Production Scope: Sprint 001

Sprint 001 focuses on recruiting operations because that is the highest-frequency bottleneck.

Core modules:

- Project Registry
- Task Registry
- SOP Registry
- Approval Queue
- Recruiting Ops Agent
- Builder Agent Handoff
- Operating Logs

## Operating Rule

No high-risk task executes without approval.

High-risk includes payroll, money, client communication, candidate release, legal/compliance, production code deployment, and system credential changes.

## First Command Target

User says:

> Lilith, open a new Brownsville project. Need 20 cleaners. $15/hr. Start tomorrow.

Lilith should return:

- project record
- recruiting plan
- text blast
- onboarding package
- candidate tracker fields
- approval checklist
- task list
- builder handoff if software is needed

## Repo Structure

```text
/ops
  /registries
  /sops
  /agents
  /templates
  /logs
  /handoffs
/docs
.github
```

## Status

Production bootstrapping active.
