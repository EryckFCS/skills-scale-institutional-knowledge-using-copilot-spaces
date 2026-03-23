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

## QA / Testing Engineer

### Role Summary
QA/Testing Engineers validate that features meet acceptance criteria and quality standards before release. They design and execute test plans, report defects, and advocate for quality throughout the development lifecycle.

### Responsibilities
- Design, write, and execute manual and automated test cases
- Validate acceptance criteria and regression coverage
- Report, triage, and track defects to resolution
- Participate in backlog refinement to clarify testability
- Maintain test documentation and coverage metrics

### Goals
- Ensure releases meet quality and reliability standards
- Reduce defect escape rate to production
- Shorten feedback loops through early and continuous testing

### Typical Communication
- Sprint ceremonies (planning, standups, retrospectives)
- Defect reports and test summary reports
- Coordination with Developers and Release Manager on release readiness

### Interactions with Existing Roles
- **Developers**: collaborates closely to reproduce defects and confirm fixes; pairs during feature work to define testability early.
- **Product Managers**: reviews acceptance criteria and flags ambiguities before development begins.
- **Project Managers**: provides test status and quality metrics for reporting; flags blocking issues for escalation.
- **Release Manager**: confirms release readiness by signing off on test completion and open-defect triage.
- **Business Analyst**: works together to ensure test cases trace back to documented requirements.

---

## UX / UI Designer

### Role Summary
UX/UI Designers create intuitive, accessible, and visually consistent user experiences. They translate product requirements into wireframes, prototypes, and design specifications that guide development.

### Responsibilities
- Develop and iterate wireframes, mockups, and high-fidelity prototypes
- Conduct user research, interviews, and usability testing
- Define interaction patterns and design system contributions
- Ensure designs meet accessibility (a11y) and brand standards
- Document design decisions and hand-off specifications for Developers

### Goals
- Deliver experiences users find valuable and easy to use
- Reduce design-implementation mismatches through clear specifications
- Advocate for accessibility and inclusive design

### Typical Communication
- Design reviews and critique sessions with Product Managers and Developers
- Usability testing readouts
- Annotated design files and hand-off notes (e.g., Figma, Storybook)

### Interactions with Existing Roles
- **Product Managers**: translates business requirements and user needs into design concepts; aligns on priorities and success metrics.
- **Developers**: provides detailed design specifications; reviews implemented UI to ensure fidelity and identifies gaps.
- **Project Managers**: surfaces design dependencies and timeline impacts early; flags when scope changes require design rework.
- **QA/Testing Engineers**: supports usability testing and defines visual/interaction acceptance criteria.
- **Stakeholders**: presents design prototypes for feedback and approval before implementation begins.

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business objectives and technical implementation. They elicit, document, and validate requirements, ensuring the team builds the right thing.

### Responsibilities
- Gather, document, and validate business and functional requirements
- Analyze current workflows and identify process improvement opportunities
- Author user stories and acceptance criteria for the backlog
- Facilitate requirements workshops and stakeholder alignment sessions
- Support UAT (User Acceptance Testing) coordination

### Goals
- Ensure requirements are clear, complete, and testable before development begins
- Reduce rework caused by misunderstood or missing requirements
- Maintain traceability between business needs and delivered features

### Typical Communication
- Requirements workshops and stakeholder interviews
- User stories, process flow diagrams, and BRD/FRD documents
- Backlog refinement sessions with Product Managers and Developers

### Interactions with Existing Roles
- **Product Managers**: partners to translate high-level product vision into detailed, actionable requirements; supports roadmap prioritization with impact analysis.
- **Project Managers**: provides scope documentation and flags requirement changes that affect timeline or resources.
- **Developers**: clarifies requirements and acceptance criteria during refinement and development; reviews implementations against documented requirements.
- **QA/Testing Engineers**: provides traceability documentation to support test case design; co-facilitates UAT.
- **Stakeholders**: primary liaison for capturing needs, resolving ambiguities, and obtaining sign-off on requirements.

---

## Release Manager

### Role Summary
Release Managers own the end-to-end coordination of software releases—from planning and scheduling to deployment and post-release review—ensuring controlled, low-risk launches.

### Responsibilities
- Maintain the release calendar and communicate timelines to stakeholders
- Own deployment checklists and release readiness gates
- Coordinate go/no-go decisions with QA, DevOps, and Product stakeholders
- Manage release branches, change windows, and rollback plans
- Lead post-release reviews and document lessons learned

### Goals
- Deliver releases on schedule with minimal disruption to users
- Ensure all release prerequisites (tests, documentation, sign-offs) are met
- Continuously improve release processes to reduce risk and cycle time

### Typical Communication
- Release readiness meetings and go/no-go calls
- Release notes and deployment announcements
- Post-release incident/review summaries

### Interactions with Existing Roles
- **DevOps Engineers**: coordinates deployment execution, environment readiness, and infrastructure changes required for the release.
- **QA/Testing Engineers**: confirms test completion and acceptable defect status as a release readiness gate.
- **Product Managers**: aligns on release scope, feature flags, and stakeholder messaging.
- **Project Managers**: synchronizes release milestones with project timelines and escalates blockers.
- **Developers**: reviews release branch contents and confirms code freeze compliance.
- **Stakeholders**: communicates release dates, changes, and post-release status.

---

## DevOps Engineer

### Role Summary
DevOps Engineers design, build, and operate the CI/CD pipelines and infrastructure that enable fast, reliable software delivery. They bridge development and operations to improve deployment frequency and system observability.

### Responsibilities
- Design and maintain CI/CD pipelines (build, test, deploy)
- Manage cloud infrastructure, environments, and configuration as code
- Implement monitoring, alerting, and logging for production observability
- Respond to and resolve infrastructure incidents
- Promote security, compliance, and operational best practices in the pipeline

### Goals
- Reduce deployment lead time and increase deployment frequency
- Maintain high system availability and fast mean time to recovery (MTTR)
- Eliminate manual, error-prone deployment steps through automation

### Typical Communication
- Infrastructure change requests and runbooks
- On-call rotation and incident postmortems
- Pipeline status updates during release windows

### Interactions with Existing Roles
- **Developers**: collaborates on pipeline configuration, environment parity, and deployment automation; supports local developer tooling and build reproducibility.
- **Release Manager**: provisions environments and executes deployments during release windows; provides rollback capability and post-deploy health checks.
- **QA/Testing Engineers**: maintains test environments and ensures pipeline gates include required automated tests.
- **Project Managers**: surfaces infrastructure risks and capacity constraints that affect project timelines.
- **Security/Compliance**: implements security scanning, secrets management, and compliance controls in the pipeline.

---

## Tech Lead / Engineering Lead

### Role Summary
The Tech Lead provides technical direction for the development team, making key architectural decisions and ensuring code quality, consistency, and long-term maintainability.

### Responsibilities
- Define and communicate technical architecture and design standards
- Lead design reviews and provide guidance on complex technical challenges
- Review and approve significant code changes (PRs) for architectural alignment
- Mentor Developers and promote engineering best practices
- Identify and manage technical debt and risks

### Goals
- Maintain a coherent, scalable technical architecture
- Elevate team engineering quality and capability
- Balance feature velocity with technical sustainability

### Typical Communication
- Architecture decision records (ADRs) and design review sessions
- Code review feedback and engineering standards documentation
- Regular 1:1s or team syncs with Developers

### Interactions with Existing Roles
- **Developers**: primary day-to-day technical partner; provides design guidance, code review, and mentorship.
- **Product Managers**: negotiates technical feasibility and effort estimates; advocates for technical investments alongside feature work.
- **Project Managers**: surfaces technical risks, dependencies, and blockers; provides realistic effort estimates for planning.
- **DevOps Engineers**: collaborates on infrastructure architecture and deployment strategies.
- **QA/Testing Engineers**: aligns on test strategy, coverage expectations, and tooling selection.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [Roles & Personas Interaction Matrix](./octoacme-roles-and-personas-interaction-matrix.md) for a RACI-lite view of who is Responsible, Accountable, Consulted, and Informed for key artifacts and ceremonies.
- See [Project Kickoff Checklist](./octoacme-project-kickoff-checklist.md) for guidance on engaging all relevant roles at project start.

