# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas (Proposed additions)

To reduce ambiguity and improve cross-team coordination, add the following role cards. Each entry includes a brief summary, responsibilities, and interactions with existing roles.

- Technical Program Manager (TPM)
  - Responsibilities:
    - Coordinate cross-team technical dependencies and integration points.
    - Own program-level schedules for multi-team features and releases.
    - Facilitate architectural trade-offs and run cross-team technical syncs.
    - Manage release orchestration and cross-team cutovers.
  - Interactions:
    - Works with PM/PdM on prioritization and milestone planning.
    - Coordinates with Engineering Managers and Developers to surface technical risks and capacity constraints.
    - Partners with QA/Support for release readiness and verification.

- Delivery Lead (Team-level)
  - Responsibilities:
    - Ensure sprint/iteration commitments are feasible and well-scoped.
    - Remove execution blockers and maintain the day-to-day delivery cadence.
    - Drive follow-through on retrospective action items and continuous improvements.
  - Interactions:
    - Partners with PM for scope decisions and schedule adjustments.
    - Works closely with Developers and QA to decompose work and ensure acceptance criteria are met.

- Engineering Manager (EM)
  - Responsibilities:
    - Lead people management: hiring, growth, performance, and mentorship.
    - Own technical health: code quality, architecture stewardship, and technical debt prioritization.
    - Capacity planning and team composition decisions.
  - Interactions:
    - Coordinates with PM/TPM on capacity and resourcing.
    - Guides Developers on technical direction and participates in architecture discussions.

- UX Researcher / Designer Liaison
  - Responsibilities:
    - Plan and run user research, usability testing, and design validation.
    - Maintain design consistency and accessibility standards.
    - Produce artifacts (wireframes, prototypes) and acceptance criteria for UX.
  - Interactions:
    - Works with PdM to shape feature direction and acceptance criteria.
    - Collaborates with Developers and QA to ensure implementation matches design and usability goals.

- Support / Customer Success Liaison
  - Responsibilities:
    - Surface production issues, customer-impacting bugs, and escalations.
    - Provide customer context and prioritization signals to the delivery team.
    - Help craft customer-facing communications post-release.
  - Interactions:
    - Feeds incidents and customer feedback to PM and Engineering for prioritization.
    - Works with Release owners on announcements and rollback communications.

- Security & Compliance Liaison
  - Responsibilities:
    - Identify security, privacy, and compliance requirements relevant to features.
    - Run pre-release security checks and coordinate formal reviews with the Security team.
    - Track remediation items and ensure gating requirements are closed.
  - Interactions:
    - Collaborates with Developers, PM, and Release owners to ensure compliance before deployment.
    - Escalates critical security findings to on-call/security team as needed.

- Data Analyst / Measurement Partner
  - Responsibilities:
    - Define success metrics and measurement plan for features.
    - Instrument telemetry, validate data quality, and build dashboards.
    - Analyze outcomes post-release and provide insights to the product team.
  - Interactions:
    - Partners with PdM to define success criteria and KPIs.
    - Works with Developers to implement instrumentation and with PM to interpret results.

Why these additions help:
- Reduces ambiguity in ownership for cross-cutting concerns (security, data, UX, support).
- Speeds cross-team coordination by clarifying who to contact for specific handoffs.
- Improves release readiness through designated liaisons for security, support, and measurement.
- Makes onboarding and role expectations clearer for new team members.

Proposed placement:
- Add an "Additional Personas" section (shown above) to docs/octoacme-roles-and-personas.md.
- Include short role cards with interaction notes and a one-line mapping to core roles for quick reference.
