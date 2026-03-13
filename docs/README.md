# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation. This collection describes the standardized lifecycle, roles, communication, and review processes OctoAcme uses for cross-functional projects.

## Overview

OctoAcme's project management process is built around lightweight, repeatable phases that keep delivery iterative and customer-focused. Work moves through a clear lifecycle—**initiation, planning, execution/tracking, release/deployment, and retrospective/continuous improvement**—with an emphasis on small, testable increments, explicit ownership, and data-informed decisions. Core artifacts such as a project charter/one-pager, roadmap and release plan, sprint backlog, Definition of Done, risk register, and retrospective action items serve as the backbone for alignment and tracking across all cross-functional initiatives.

The model relies on well-defined personas and responsibilities. A **Project Manager (PM)** coordinates delivery mechanics—timelines, dependencies, risks, and stakeholder communications—while the **Product Manager (PdM)** owns outcomes: clarifying the problem statement, success metrics, and backlog prioritization. **Developers** design, build, and test features; contribute to estimation and reviews; and surface technical risks early. **QA/Testing** validates acceptance criteria and overall quality, and **stakeholders/sponsors** provide inputs and approvals at key decision points. Initiation formalizes the "why" and "who" (business need, metrics, stakeholders, initial risks) and includes a go/no-go gate before moving into detailed planning.

Communication is managed through a consistent cadence and clear escalation paths. Teams maintain a **single source of truth** for project status (project README or release doc) and use structured weekly status templates (progress, next steps, risks/blockers, asks/decisions). Delivery teams run daily standups, a weekly delivery sync to surface risks and dependencies, and demos/reviews at the end of each sprint or milestone. When blockers arise, escalation flows from team triage → PM → product lead → sponsor, with security incidents handled via a dedicated incident runbook and security on-call notification.

Quality assurance is integrated throughout execution and reinforced at release time. OctoAcme uses a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined PR process favoring small PRs, explicit acceptance criteria, CI-based automated tests/linting, and at least one approval before merge. Testing expectations include **unit tests**, **integration tests** where appropriate, and **end-to-end smoke tests** for critical flows, plus **security scanning in CI** and manual QA for feature acceptance. Releases follow a checklist-driven approach covering staging and smoke tests, production deployment, post-deploy verification, and stakeholder announcements, paired with rollback/incident practices and blameless retrospectives whose improvement actions are tracked back into the backlog.

## Docs in this folder

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution and Tracking](octoacme-execution-and-tracking.md)
- [Release and Deployment](octoacme-release-and-deployment.md)
- [Risk Management and Communications](octoacme-risks-and-communication.md)
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

> **Tip:** These docs can be added to `.copilot/` so that Copilot Spaces can use them as context—consistent with the approach described in the [Project Management Overview](octoacme-project-management-overview.md).
