# OctoAcme Project Management Docs

Welcome! This README is the central landing page for OctoAcme's project management documentation. It summarizes the key processes, workflows, roles, and practices and links to the full reference docs in this folder.

---

## OctoAcme Project Management Processes (Summary)

OctoAcme uses a customer-focused, iterative, and transparent project management methodology across the full project lifecycle:

- **Initiation**: Validate the business need, define measurable success metrics, align stakeholders, and produce a lightweight project charter (one-pager) covering the problem, goal, timeline, risks, and resourcing.
- **Planning**: Break down work into a prioritised backlog, define scope, dependencies, milestones, a Definition of Done, and risk mitigations before execution begins.
- **Execution & Tracking**: Deliver small, shippable increments; track progress on the project board; follow a disciplined PR workflow (small PRs linked to issues, at least one approval required, CI must be green).
- **Release & Deployment**: Verify acceptance criteria are met, confirm CI is green, document a rollback plan, and complete a structured release checklist before deploying to production.
- **Retrospective & Continuous Improvement**: After each delivery, capture lessons learned and action items; feed improvements back into the backlog so they are tracked and actioned.
- **Risk & Communication**: Maintain a risk register, review it regularly, escalate through defined paths (team → Product Lead → sponsor), and share template-driven status updates with all stakeholders.
- **Roles & Personas**: Clearly defined accountability for Project Managers, Product Managers, Developers, QA/Testing, and Stakeholders ensures ownership across all lifecycle stages.

---

## Project Lifecycle

| Stage | Purpose |
|---|---|
| Initiation | Define the problem, goals, and stakeholders; create the project charter |
| Planning | Scope, milestones, backlog, dependencies, and risk mitigations |
| Execution & Tracking | Build, test, review, and iterate in small increments |
| Release & Deployment | Deploy safely with checklists, CI gates, and a rollback plan |
| Retrospective & Improvement | Capture learnings and drive continuous improvement |

---

## Key Workflows

- **Project board / backlog tracking** – Maintain a prioritised backlog; update the board daily so status is always visible.
- **PR review** – Keep PRs small and linked to issues; require at least one approval and green CI before merging.
- **Release readiness** – Confirm acceptance criteria, green CI, smoke tests, and a documented rollback plan before release.
- **Issue / backlog follow-up** – Retrospective action items and risk mitigations are captured as issues and tracked to completion.

---

## Roles & Personas

| Role | Responsibilities |
|---|---|
| **Project Manager (PM)** | Coordinates delivery, schedules, risk management, and stakeholder communication |
| **Product Manager (PdM)** | Defines outcomes, prioritises the backlog, and measures success |
| **Developers** | Implement features, write tests, participate in code reviews, and estimate work |
| **QA / Testing** | Validate acceptance criteria, run smoke tests, and ensure overall quality |
| **Stakeholders** | Provide inputs, approvals, and strategic direction throughout the lifecycle |

---

## Communication Strategy

- **Daily / twice-weekly standups** – Progress, blockers, and dependencies for the delivery team.
- **Weekly PM + PdM sync** – Backlog prioritisation and alignment.
- **Periodic stakeholder updates** – Status reports using a standard template (progress, next steps, risks, decisions required).
- **Escalation path** – Team-level triage → Product Lead → project sponsor for unresolved blockers or high-impact risks.
- **Single source of truth** – The project charter, risk register, and status reports are kept in the project repo so everyone has one authoritative reference.

---

## Quality Assurance Practices

- Unit tests for all new logic; integration tests where applicable.
- Smoke tests for critical user flows before every release.
- Security scanning and linting run in CI on every pull request.
- Manual QA performed when automated coverage is insufficient or for high-risk changes.
- PRs must have green CI and at least one code-review approval before merging.
- Release checklist confirms all acceptance criteria are met and a rollback plan is documented.

---

## Key Documents

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, and lifecycle summary |
| [Project Initiation Guide](octoacme-project-initiation.md) | Charter template, stakeholder mapping, and initiation checklist |
| [Project Planning](octoacme-project-planning.md) | Scope definition, backlog setup, milestones, and dependencies |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Team rhythms, PR workflow, and project-board guidance |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, escalation paths, and status-update templates |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Release checklist, deployment steps, and incident playbook |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective format and action-item tracking |
| [Roles & Personas](octoacme-roles-and-personas.md) | Detailed responsibilities for each role |
