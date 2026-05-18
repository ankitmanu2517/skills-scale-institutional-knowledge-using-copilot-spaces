# OctoAcme Project Management Docs

## Overview

OctoAcme manages projects through a structured five-phase lifecycle: **Initiation, Planning, Execution, Release, and Retrospective**. During initiation, teams validate ideas via a lightweight one-pager that captures the problem statement, stakeholders, success metrics, and high-level timeline. Planning turns approved initiatives into executable backlogs broken into small, shippable increments with clear acceptance criteria and a Definition of Done. Execution follows an iterative cadence of daily standups, weekly delivery syncs, and end-of-sprint demos, all tracked on a GitHub Projects board with columns from Backlog through Done.

Three core personas drive delivery. **Project Managers** coordinate schedules, risks, dependencies, and cross-team communication. **Product Managers** own outcomes—defining what to build, prioritizing the backlog, and measuring impact with data. **Developers** implement features, write tests, participate in design and code reviews, and help identify technical risks. QA validates quality against acceptance criteria, and stakeholders provide inputs and approvals at defined checkpoints.

Communication is frequent and layered. PMs and Product Managers align weekly; the delivery team syncs twice weekly (or daily via standups); stakeholders receive monthly updates plus ad-hoc escalations. A standardized weekly status template (progress, next steps, risks, decisions needed) keeps everyone informed. Risks are tracked in a register with impact/likelihood ratings and named owners, reviewed at every weekly sync, and escalated along a clear path: Team → PM → Product Lead → Sponsor.

Quality assurance is embedded throughout execution. The PR workflow mandates small pull requests (≤400 lines), linked issues, automated tests and linting in CI, and at least one approval before merge. Testing spans unit, integration, and end-to-end smoke tests for critical flows, supplemented by security scanning in CI and manual QA for feature acceptance. Teams monitor velocity, burndown, and key observability signals (errors, latency, usage) via dashboards, and hold blameless retrospectives after every sprint and incident to capture learnings and drive continuous improvement.

## Documentation

| Document | Description |
|----------|-------------|
| [Project Management Overview](octoacme-project-management-overview.md) | Introduces OctoAcme's customer-first, iterative, and data-informed PM approach with core artifacts, lifecycle stages, and communication cadence. |
| [Project Initiation](octoacme-project-initiation.md) | Covers how OctoAcme validates a new idea before planning, including business need, success metrics, stakeholders, and initial risks. |
| [Project Planning](octoacme-project-planning.md) | Describes turning an approved initiative into an executable plan and backlog with shippable increments and scope estimates. |
| [Execution and Tracking](octoacme-execution-and-tracking.md) | Explains day-to-day delivery management: standups, delivery syncs, sprint reviews, metrics tracking, and blocker escalation. |
| [Risks and Communication](octoacme-risks-and-communication.md) | Defines how risks are logged, assessed, and mitigated, plus standardized stakeholder updates and escalation paths. |
| [Release and Deployment](octoacme-release-and-deployment.md) | Standardizes release and deployment steps including pre-release checks, deployment verification, and rollback playbooks. |
| [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Focuses on capturing learnings and turning them into prioritized action items tracked in the backlog. |
| [Roles and Personas](octoacme-roles-and-personas.md) | Defines responsibilities, goals, and communication patterns for Developers, Product Managers, and Project Managers. |
