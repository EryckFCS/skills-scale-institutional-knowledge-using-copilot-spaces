# OctoAcme Roles & Personas — Interaction Matrix

This document provides a RACI-lite map showing which roles are **Responsible**, **Accountable**, **Consulted**, or **Informed** for key project artifacts and ceremonies.

**Legend**
| Symbol | Meaning |
|--------|---------|
| **R** | Responsible — does the work |
| **A** | Accountable — owns the outcome (one per row) |
| **C** | Consulted — provides input before/during |
| **I** | Informed — kept up to date |

---

## Artifact & Ceremony Matrix

| Artifact / Ceremony | Project Manager | Product Manager | Tech Lead | Developers | QA/Testing | UX/UI Designer | Business Analyst | Release Manager | DevOps Engineer | Stakeholders |
|---|---|---|---|---|---|---|---|---|---|---|
| **Project Charter / One-pager** | A/R | C | C | I | I | I | C | I | I | C |
| **Stakeholder List** | A/R | C | I | I | I | I | C | I | I | I |
| **Product Roadmap** | C | A/R | C | C | I | C | C | I | I | C |
| **Sprint/Iteration Backlog** | C | A | C | R | C | C | R | I | I | I |
| **User Stories & Acceptance Criteria** | I | A | C | C | C | C | R | I | I | C |
| **Wireframes & Design Specs** | I | C | C | C | C | A/R | C | I | I | C |
| **Architecture Decision Records (ADRs)** | I | I | A/R | C | I | I | I | I | C | I |
| **Definition of Done (DoD)** | C | C | A/R | R | R | C | C | I | I | I |
| **Risk Register** | A/R | C | C | C | C | I | C | C | C | I |
| **Test Plan & Test Cases** | I | I | C | C | A/R | C | C | I | C | I |
| **Release Notes** | I | C | C | C | C | I | C | A/R | C | I |
| **Deployment Checklist** | I | I | C | C | C | I | I | A | R | I |
| **Retrospective Action Items** | A/R | C | C | C | C | C | C | C | C | I |
| **Sprint Planning** | A | A | C | R | C | C | C | I | I | I |
| **Daily Standup** | A | I | C | R | R | R | R | I | I | I |
| **Sprint Review / Demo** | A | A | C | R | C | C | C | I | I | C |
| **Retrospective** | A/R | C | C | C | C | C | C | C | C | I |
| **Release Go/No-Go** | C | C | C | C | C | I | I | A/R | C | I |
| **Post-Release Review** | C | C | C | C | C | I | I | A/R | C | I |
| **Incident / Escalation** | A | C | C | C | C | I | I | C | R | I |

---

## Key Cross-Role Touchpoints

### Design → Development Handoff
- **UX/UI Designer** (R) produces annotated design specifications.
- **Tech Lead** and **Developers** (C) review for feasibility before development starts.
- **QA/Testing** (C) reviews to define visual/interaction acceptance criteria.

### Requirements → Backlog
- **Business Analyst** (R) authors user stories and acceptance criteria.
- **Product Manager** (A) prioritizes and owns the backlog.
- **Project Manager** (C) flags capacity or timeline impacts.
- **Developers** and **QA/Testing** (C) refine for technical feasibility and testability.

### Release Pipeline
- **Release Manager** (A) coordinates go/no-go and owns the deployment checklist.
- **DevOps Engineer** (R) executes deployments and manages infrastructure readiness.
- **QA/Testing** (R) signs off on test completion and defect triage.
- **Product Manager** (C) confirms scope and stakeholder messaging.

### Risk & Escalation
- **Project Manager** (A) owns the risk register and escalation process.
- **Tech Lead** (C) identifies and sizes technical risks.
- **Release Manager** (C) flags deployment and environment risks.
- **Business Analyst** (C) surfaces requirements and scope risks.

---

*Reference this matrix during sprint planning, project kickoff, and retrospectives to confirm role clarity and prevent gaps in ownership.*
