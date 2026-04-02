# OctoAcme — Personas & Roles Project Checklist

Use this checklist at project initiation and planning to identify which personas are needed and how they participate across the project lifecycle.

---

## Step 1: Confirm Core Roles

These roles are required on every project.

- [ ] **Project Manager** — named and confirmed
- [ ] **Product Manager** — named and confirmed
- [ ] **Developers** — team identified and available
- [ ] **QA/Testing** — coverage confirmed (may be embedded in dev team or a dedicated QA Lead)
- [ ] **Stakeholders** — primary contacts identified and communication plan agreed

---

## Step 2: Assess Additional Personas

Review each additional role and check the box if your project needs it.

| Role | Check if Applicable | Named Owner |
|---|---|---|
| Technical Lead / Engineering Lead | [ ] | |
| QA Lead / Test Lead | [ ] | |
| Delivery Manager / Scrum Master | [ ] | |
| Release Manager | [ ] | |
| Support / Operations Representative | [ ] | |
| Security / Compliance Representative | [ ] | |

**Prompts to help you decide:**
- Is the technical complexity high enough to need a dedicated technical owner? → Add **Technical Lead**
- Do you need structured test planning and quality gates beyond basic developer testing? → Add **QA Lead**
- Is delivery cadence a concern, or does the team need facilitation support? → Add **Delivery Manager**
- Does this project involve coordinated releases or high-risk deployments? → Add **Release Manager**
- Will the release require an operational handoff or support readiness review? → Add **Support / Operations Representative**
- Does the work touch regulated data, user privacy, or security controls? → Add **Security / Compliance Representative**

---

## Step 3: Map Personas to Lifecycle Activities

For each confirmed persona, check which lifecycle phases they are active in.

| Persona | Initiation | Planning | Execution | Release | Retrospective |
|---|---|---|---|---|---|
| Project Manager | ✓ | ✓ | ✓ | ✓ | ✓ |
| Product Manager | ✓ | ✓ | ✓ | ✓ | ✓ |
| Developers | — | ✓ | ✓ | ✓ | ✓ |
| QA/Testing | — | ✓ | ✓ | ✓ | ✓ |
| Stakeholders | ✓ | ✓ | — | ✓ | — |
| Technical Lead | ✓ | ✓ | ✓ | ✓ | ✓ |
| QA Lead | — | ✓ | ✓ | ✓ | ✓ |
| Delivery Manager / Scrum Master | — | ✓ | ✓ | — | ✓ |
| Release Manager | — | ✓ | — | ✓ | — |
| Support / Ops Representative | — | — | ✓ | ✓ | ✓ |
| Security / Compliance Representative | ✓ | ✓ | ✓ | ✓ | — |

> Adjust this table for your project's needs. Not every role participates in every phase.

---

## Step 4: Confirm Escalation and Handoff Paths

Before execution begins, confirm:

- [ ] Who owns the technical escalation path? (Technical Lead or Project Manager?)
- [ ] Who is the go/no-go decision maker for releases? (Release Manager or Project Manager?)
- [ ] Who handles security or compliance blockers? (Security / Compliance Representative)
- [ ] Who coordinates the support handoff after release? (Support / Ops Representative)
- [ ] Who facilitates retrospectives and action item tracking? (Delivery Manager or Project Manager?)

---

## References

- [OctoAcme Roles and Personas](./octoacme-roles-and-personas.md)
- [OctoAcme Project Initiation Guide](./octoacme-project-initiation.md)
- [OctoAcme Project Planning Guide](./octoacme-project-planning.md)
- [OctoAcme Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [OctoAcme Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
