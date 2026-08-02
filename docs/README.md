# OctoAcme Project Management Docs

Overview
OctoAcme follows a lightweight, outcome-focused approach to project management that emphasizes clear ownership, iterative delivery, and continuous improvement. Each initiative starts with a concise Project One-pager to define the problem, success metrics, stakeholders, and a high-level timeline. Planning breaks approved work into shippable increments, identifies dependencies and risks, and establishes a Definition of Done so the team can reliably deliver value in short cycles.

Key workflows
During Execution the team uses a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and small, reviewable pull requests that include acceptance criteria and run automated CI checks. Testing responsibilities include unit and integration tests, end-to-end smoke tests for critical flows, and manual QA for feature acceptance when necessary. Releases follow a checklist with pre-release verification, rollback plans, and post-deploy verification.

Personas & communication
Roles are explicit: Product Managers (PdM) set outcomes and priorities, Project Managers (PM) coordinate delivery and communications, Developers implement and test features, and QA validates acceptance criteria. Communication cadence includes daily standups, weekly delivery syncs, scheduled demos/reviews at the end of sprints or milestones, and monthly stakeholder updates. Blockers escalate through a defined path (team → PM → Product Lead → Sponsor), and security incidents follow a separate incident runbook.

How to use and update these docs
This folder contains the canonical process documents for OctoAcme. Keep the Project One-pager and decision artifacts in the project repo. To propose edits or add content to any process document, use the "Add Content to Project Management Process Docs" issue template: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml.

Docs index
- docs/octoacme-project-management-overview.md — concise intro to roles, principles, and lifecycle.
- docs/octoacme-project-initiation.md — one-pager template, kickoff, and decision gate.
- docs/octoacme-project-planning.md — backlog, estimation, Definition of Done, and release planning.
- docs/octoacme-execution-and-tracking.md — team rhythm, workflows, QA, and blocker escalation.
- docs/octoacme-risks-and-communication.md — risk register guidance, stakeholder templates, and escalation paths.
- docs/octoacme-release-and-deployment.md — release types, pre-release checklist, rollback playbook.
- docs/octoacme-retrospective-and-continuous-improvement.md — running retrospectives and tracking action items.
- docs/octoacme-roles-and-personas.md — role summaries and responsibilities.
