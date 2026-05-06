# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. It covers both core delivery roles and supporting roles that contribute to project quality, usability, and alignment.

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

## QA / Test Engineers

### Role Summary
QA/Test Engineers define and execute test strategies to validate that features meet acceptance criteria and quality standards. They are embedded throughout delivery—not just at the end—to catch issues early and support a culture of quality ownership across the team.

### Responsibilities
- Define and maintain test plans, test cases, and regression suites
- Execute manual and automated tests across feature branches and releases
- Log, track, and verify resolution of defects and quality issues
- Participate in sprint planning to assess testability of acceptance criteria
- Contribute to pre-release readiness reviews and sign-off
- Collaborate with Developers to improve test coverage and CI reliability
- Identify systemic quality risks and propose improvements to the Definition of Done

### Goals
- Ensure software meets agreed acceptance criteria before release
- Reduce defect escape rate to production
- Shift quality left by integrating testing earlier in the development cycle
- Maintain comprehensive regression coverage for critical workflows

### Typical Communication
- Daily standups and sprint ceremonies alongside the delivery team
- Bug reports and defect tracking in the project board
- Test summary reports shared with PM and PdM ahead of release
- Release readiness sign-off in coordination with the PM

### Interaction with Other Roles
- **Developers**: collaborate on unit and integration test coverage, pair on defect triage and root cause analysis
- **Product Managers**: clarify acceptance criteria and edge cases; validate that delivered features match intended outcomes
- **Project Managers**: provide release readiness status and flag quality risks that may affect timelines
- **UX/UI Designers**: validate that implemented UI matches design specifications and usability expectations

---

## UX / UI Designers

### Role Summary
UX/UI Designers ensure that OctoAcme solutions are user-centered, accessible, and visually coherent. They translate product requirements into wireframes, prototypes, and design assets that guide development, and they validate that built features align with user needs and design intent.

### Responsibilities
- Conduct user research and synthesize insights into design requirements
- Create wireframes, mockups, and interactive prototypes
- Define and maintain the design system and component library
- Work with Product Managers to refine feature requirements from a usability perspective
- Collaborate with Developers to ensure designs are implemented accurately
- Participate in usability testing and iterate based on findings
- Document interaction patterns and accessibility requirements

### Goals
- Deliver intuitive, consistent, and accessible user experiences
- Reduce rework by aligning on design intent early in the sprint cycle
- Build shared understanding of user needs across the delivery team
- Maintain design-to-implementation fidelity

### Typical Communication
- Design reviews and critiques with PdM and Developers
- Prototype walkthroughs and usability test readouts
- Design asset handoffs and annotation in shared design tools
- Sprint planning participation to flag design dependencies and lead times

### Interaction with Other Roles
- **Product Managers**: translate problem statements and user goals into design direction; validate designs against product vision
- **Developers**: provide annotated design specs and assets; answer implementation questions during development
- **QA/Test Engineers**: share design intent so testers can validate UI fidelity and accessibility
- **Business Analysts**: incorporate workflow requirements and business rules into design decisions
- **Subject Matter Experts**: leverage domain knowledge to create accurate, context-appropriate interfaces

---

## Business Analysts

### Role Summary
Business Analysts bridge the gap between business needs and technical solutions. They elicit, document, and validate requirements so the delivery team has a clear, shared understanding of what needs to be built and why. They help ensure that solutions deliver intended business outcomes.

### Responsibilities
- Elicit and document business requirements through stakeholder interviews and workshops
- Translate business needs into user stories, process flows, and acceptance criteria
- Identify and document business rules, constraints, and edge cases
- Facilitate scope clarification and manage requirements traceability
- Analyze current-state processes and identify improvement opportunities
- Support User Acceptance Testing (UAT) by coordinating with business stakeholders
- Review and validate that delivered solutions meet documented requirements

### Goals
- Produce clear, complete, and testable requirements that reduce ambiguity
- Reduce rework caused by misunderstood or late-breaking requirements
- Ensure business stakeholders and delivery teams are aligned on scope and priorities
- Support smooth handoffs between discovery, design, and development phases

### Typical Communication
- Requirements workshops and stakeholder interviews during initiation and planning
- User story refinement sessions with Product Managers and Developers
- Requirements documentation and process flow diagrams shared with the full team
- UAT coordination reports and sign-off documentation

### Interaction with Other Roles
- **Product Managers**: collaborate on translating business objectives into a prioritized backlog; surface requirements that affect roadmap decisions
- **Developers**: provide detailed acceptance criteria, business rules, and workflow context to inform implementation
- **UX/UI Designers**: share process flows and user journeys to inform design decisions
- **QA/Test Engineers**: provide requirements traceability to support test plan creation and UAT coordination
- **Project Managers**: flag scope changes, requirement conflicts, or dependencies that affect project timelines
- **Subject Matter Experts**: rely on SME expertise to validate requirements accuracy and domain-specific edge cases

---

## Subject Matter Experts (SMEs)

### Role Summary
Subject Matter Experts provide authoritative knowledge of a specific business domain, technology, or process area. They are consulted throughout the project lifecycle to validate requirements, review designs and solutions, and ensure that deliverables accurately reflect domain realities. SMEs are typically part-time contributors who engage at key milestones rather than as standing team members.

### Responsibilities
- Provide domain expertise to inform requirements gathering and solution design
- Review and validate requirements, designs, test cases, and deliverables for accuracy
- Help define and refine acceptance criteria from a domain perspective
- Participate in User Acceptance Testing and sign off on domain-specific scenarios
- Identify domain-specific risks, constraints, and regulatory considerations
- Transfer knowledge to team members to build ongoing domain understanding

### Goals
- Ensure that solutions accurately reflect domain requirements and constraints
- Reduce the risk of building technically correct but operationally incorrect solutions
- Accelerate team learning and reduce reliance on re-consulting the same expert repeatedly

### Typical Communication
- Scheduled review sessions at key project milestones (requirements review, design review, UAT)
- Asynchronous feedback on requirements docs, design artifacts, and test cases
- Knowledge-sharing sessions or documentation contributions as needed

### Interaction with Other Roles
- **Business Analysts**: primary point of contact for eliciting and validating domain requirements
- **Product Managers**: provide domain context that informs prioritization and success criteria
- **Developers**: clarify complex domain rules or edge cases during implementation
- **QA/Test Engineers**: review and validate domain-specific test scenarios and UAT scripts
- **UX/UI Designers**: advise on domain-specific terminology, workflows, and user expectations

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When modeling cross-functional scenarios, reference the **Interaction with Other Roles** sections to understand how handoffs and collaboration points flow between personas.

