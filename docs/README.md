# OctoAcme Project Management Docs

Welcome! This README is the entry point for all OctoAcme project management process documentation. It provides a summary of our overarching methodology and links to each detailed process guide.

---

## Project Management Approach

OctoAcme uses a lightweight, end-to-end project management process that moves work through a clear lifecycle: **initiation → planning → execution → release → retrospective improvement**. Projects begin with a one-pager that defines the problem, goal, success metrics, stakeholders, timeline, risks, and resource needs. Once approved, the team moves into planning by creating a prioritized backlog, defining acceptance criteria and a Definition of Done, identifying dependencies, estimating work, and mapping milestones. This approach emphasizes iterative delivery, clear ownership, and measurable outcomes so teams can break work into small, testable increments and make data-informed decisions.

### Key Principles
- **Customer-first and value-driven**: prioritize customer impact above all.
- **Iterative delivery**: work in small, testable increments.
- **Clear ownership**: every project has a named PM and Product Lead.
- **Data-informed decisions**: measure outcomes and iterate based on evidence.
- **Psychological safety**: encourage feedback, learning, and open communication.

---

## Personas & Roles

OctoAcme defines four core roles that collaborate throughout the project lifecycle:

| Role | Core Responsibility |
|---|---|
| **Project Manager (PM)** | Coordinates delivery, maintains schedules, manages risks and dependencies, facilitates planning and retrospectives, and drives stakeholder communication. |
| **Product Manager (PdM)** | Defines the problem, prioritizes the roadmap and backlog, aligns trade-offs with stakeholders and engineering, and measures whether outcomes are being achieved. |
| **Developers** | Design, implement, test, and document solutions while contributing to estimation, code review, and risk identification. |
| **QA / Testing** | Validate acceptance criteria and ensure quality and readiness for release. |

Stakeholders provide inputs, approvals, and ongoing feedback throughout the project.

---

## Communication Strategies

Communication is structured around recurring rhythms and a clear escalation path:

- **PM–Product alignment**: regular syncs to keep roadmap and delivery in step.
- **Team standups**: twice-weekly (or as agreed) for delivery team coordination.
- **Weekly status updates**: written reports covering progress, next steps, risks, and decisions needed.
- **Milestone demos**: demonstrate completed increments to stakeholders.
- **Monthly stakeholder updates**: keep sponsors and stakeholders informed of progress.
- **Escalation path**: blockers escalate from team-level triage → PM → Product Lead → sponsor as business impact increases.

Teams use a shared **project board** as the single source of truth, tracking work through stages: _Backlog → Ready → In Progress → In Review → QA → Done_.

---

## Quality Assurance Practices

Quality assurance is embedded throughout delivery rather than treated as a final gate:

- **Unit tests** for all new logic; integration tests where appropriate.
- **End-to-end smoke tests** for critical user flows.
- **Security scanning** in CI on every pull request.
- **Manual QA** for feature acceptance when needed.
- **Pull request standards**: keep PRs small, include issue links and acceptance criteria, pass CI and linting before review, and require approval before merging.
- **Pre-release checklist**: confirm acceptance criteria are met, CI and security scans pass, release notes and rollback plans are ready, and staging and production smoke tests pass.
- **Retrospectives**: after each sprint, release, or incident, capture lessons learned and convert them into tracked improvement actions with owners and timelines.

---

## Process Documents

Use the links below to navigate to detailed guidance for each phase or topic:

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to OctoAcme's approach, principles, roles, and lifecycle. |
| [Project Initiation Guide](octoacme-project-initiation.md) | How to define the problem, stakeholders, goals, and project charter. |
| [Project Planning](octoacme-project-planning.md) | Backlog creation, estimation, milestones, dependencies, and Definition of Done. |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Sprint management, project board usage, and daily team practices. |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk register, escalation paths, status reporting, and communication templates. |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Pre-release checklist, deployment steps, smoke tests, and post-deploy verification. |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Sprint retros, incident reviews, and tracking improvement actions. |
| [Roles and Personas](octoacme-roles-and-personas.md) | Detailed responsibilities and communication expectations for each role. |

---

> **Tip:** If you're using Copilot Spaces, add process docs to `.copilot/` so they are available as context when asking Copilot questions about OctoAcme's processes.
