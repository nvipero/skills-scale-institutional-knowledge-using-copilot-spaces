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

## Additional Roles and Personas

The following roles extend the core team to cover areas that are critical for larger, more complex, or regulated projects. Include these personas when the project scope warrants it.

---

## Technical Lead / Engineering Lead

### Role Summary
The Technical Lead guides the engineering team's technical direction, ensures architectural quality, and helps translate product requirements into feasible technical solutions.

### Responsibilities
- Own technical direction, architecture decisions, and design reviews
- Identify and mitigate technical risks during planning and execution
- Coordinate engineering estimates and assess delivery feasibility
- Mentor developers and help resolve technical blockers
- Review and approve significant implementation approaches

### Goals
- Maintain a high-quality, maintainable, and scalable codebase
- Reduce technical debt and unplanned rework
- Align engineering execution with product and business goals

### Typical Communication
- Technical design docs and architecture decision records (ADRs)
- Code review feedback and PR approvals
- Sprint planning and estimation sessions
- Escalation paths for technical blockers

### Interaction with Existing Roles
- Works with the **Product Manager** to validate feasibility and negotiate scope trade-offs
- Partners with the **Project Manager** on sequencing, dependencies, and delivery risk
- Collaborates with **Developers** on implementation details and code quality
- Supports **QA/Testing** by clarifying technical behavior and expected system outcomes

---

## QA Lead / Test Lead

### Role Summary
The QA Lead defines the test strategy, coordinates test coverage, and ensures quality gates are met before release. They are the primary voice of quality across the delivery lifecycle.

### Responsibilities
- Define and maintain the overall test strategy and quality gates
- Coordinate functional, integration, and regression test coverage
- Validate acceptance criteria and confirm release readiness
- Track defects and ensure fixes are verified before release
- Report quality status and release risk to the team

### Goals
- Deliver high-confidence releases with minimal post-release defects
- Ensure every release meets the agreed Definition of Done
- Support continuous improvement of testing practices

### Typical Communication
- Test plans, test reports, and defect logs
- Participation in sprint planning and acceptance criteria reviews
- Go/no-go input ahead of releases
- Escalation of quality blockers to the Project Manager

### Interaction with Existing Roles
- Works with **Developers** to ensure testable requirements and sufficient test coverage
- Collaborates with the **Project Manager** on QA milestones and defect triage timelines
- Aligns with the **Product Manager** on acceptance criteria and release confidence
- Supports **Stakeholders** by communicating quality status and surfacing release risk

---

## Delivery Manager / Scrum Master

### Role Summary
The Delivery Manager (or Scrum Master) facilitates delivery ceremonies, removes process impediments, and helps the team maintain cadence and continuous improvement.

### Responsibilities
- Facilitate standups, sprint planning, reviews, and retrospectives
- Identify and remove process blockers and team impediments
- Track delivery health, flow, and team throughput
- Reinforce delivery discipline and accountability
- Surface execution risks to the Project Manager

### Goals
- Keep the team focused, unblocked, and delivering at a sustainable pace
- Foster a culture of continuous improvement
- Improve team transparency and predictability

### Typical Communication
- Daily standups and sprint cadence facilitation
- Impediment logs and action items
- Velocity and flow metrics shared with the Project Manager
- Retrospective summaries and improvement actions

### Interaction with Existing Roles
- Supports the **Project Manager** in delivery coordination and team cadence
- Helps **Developers** and **QA/Testing** stay unblocked and focused
- Provides visibility into execution risks and team throughput
- Partners with the **Product Manager** to keep backlog refinement and planning on track

---

## Release Manager

### Role Summary
The Release Manager coordinates release planning, deployment readiness, and release communications. They own the go/no-go process and ensure every release meets readiness criteria.

### Responsibilities
- Coordinate release planning and communicate deployment windows
- Ensure release notes, approvals, and rollback plans are prepared
- Manage go/no-go execution and release readiness reviews
- Track post-release verification and follow-up actions
- Maintain the deployment checklist and release calendar

### Goals
- Execute low-risk, predictable releases
- Minimize production incidents caused by releases
- Ensure all stakeholders are informed before, during, and after releases

### Typical Communication
- Release calendar and deployment schedule
- Go/no-go meeting facilitation
- Release notes and stakeholder announcements
- Post-release incident or status updates

### Interaction with Existing Roles
- Works closely with the **Project Manager** on timing, coordination, and scope
- Partners with **Developers** and **QA/Testing** to confirm release readiness
- Collaborates with **Stakeholders** on release communication and timing expectations
- Aligns with the **Product Manager** on what is included in the release scope

---

## Support / Operations Representative

### Role Summary
The Support / Operations Representative provides operational context, validates support readiness, and ensures a smooth handoff from delivery to production support.

### Responsibilities
- Provide input on operational impact and support readiness for new releases
- Validate that support documentation and runbooks are prepared
- Surface recurring operational issues and customer-facing pain points
- Ensure smooth handoff from the delivery team to the support organization
- Participate in incident response and root cause analysis

### Goals
- Minimize operational disruption from new releases
- Ensure the support team is prepared for every launch
- Improve the feedback loop between support and engineering

### Typical Communication
- Support readiness reviews ahead of releases
- Runbook contributions and operational notes
- Incident and escalation reports
- Post-release feedback to the engineering team

### Interaction with Existing Roles
- Works with **Developers** to understand operational constraints and known issues
- Collaborates with the **Project Manager** on readiness timelines and incident escalation paths
- Supports the **Product Manager** and **Stakeholders** by sharing customer impact insights
- Partners with the **Release Manager** during cutover and post-release monitoring

---

## Security / Compliance Representative

### Role Summary
The Security / Compliance Representative reviews project work for security, privacy, and compliance concerns. They define required controls, support risk management, and confirm that regulatory obligations are met.

### Responsibilities
- Review features and architecture for security and privacy risks
- Define required security checks, approvals, or controls for regulated work
- Ensure security-related documentation and follow-up actions are completed
- Support risk management and incident escalation procedures
- Validate that compliance requirements are met before release

### Goals
- Reduce security and compliance risk across project deliverables
- Ensure teams are aware of and accountable for security obligations
- Enable secure, compliant releases without blocking delivery unnecessarily

### Typical Communication
- Security review outcomes and risk assessments
- Compliance checklists and approval records
- Escalation of unresolved security concerns to the Project Manager
- Engagement with Release Manager when security checks gate release

### Interaction with Existing Roles
- Advises the **Project Manager** on risks and required escalation paths
- Works with **Developers** and **QA/Testing** on control requirements and validation
- Partners with the **Product Manager** and **Stakeholders** when decisions affect policy or risk
- Engages with the **Release Manager** when security checks are part of release readiness

---

## When to Introduce a New Persona

Not every project requires all personas. Use the following guidance to decide when to add a role to a project:

| Scenario | Consider Adding |
|---|---|
| Technical complexity is high or architecture decisions need ownership | Technical Lead |
| Dedicated test planning and release quality tracking is needed | QA Lead |
| Delivery cadence needs facilitation or team flow is inconsistent | Delivery Manager / Scrum Master |
| Releases are frequent, high-risk, or involve multiple teams | Release Manager |
| New capabilities require operational readiness and support handoff | Support / Operations Representative |
| Work touches regulated data, user privacy, or security controls | Security / Compliance Representative |

**General rule:** Add a persona when the absence of a named owner creates ambiguity about who is responsible for a key area of work, decision, or handoff.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See `docs/octoacme-personas-checklist.md` for a lightweight template to select and map personas to project activities.

