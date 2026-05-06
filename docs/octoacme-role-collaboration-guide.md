# OctoAcme Role Collaboration Guide

This guide clarifies how OctoAcme roles interact at key handoff points across the project lifecycle. Use it to reduce ambiguity about who owns what, who needs to be consulted, and how work flows between functions.

For full role definitions, see [Roles and Personas](octoacme-roles-and-personas.md).

---

## RACI Quick Reference

The table below summarizes accountability across the major project phases. **R** = Responsible, **A** = Accountable, **C** = Consulted, **I** = Informed.

| Activity | PM | PdM | Dev | QA | UX | BA | SME |
|---|---|---|---|---|---|---|---|
| Project charter / one-pager | A | C | I | I | I | C | C |
| Requirements elicitation | C | A | I | C | C | R | C |
| Backlog creation & prioritization | C | A | C | C | C | R | C |
| Design & prototyping | I | C | C | I | A | C | C |
| Acceptance criteria definition | C | A | C | R | C | R | C |
| Sprint planning | A | C | R | C | C | C | I |
| Feature implementation | I | I | A | C | C | I | I |
| Test execution | I | I | C | A | I | C | I |
| UAT coordination | C | A | I | C | I | R | C |
| Release readiness sign-off | A | C | C | R | I | I | I |
| Retrospective | A | C | R | R | C | C | I |

---

## Key Handoff Points

### 1. Discovery → Design
**From**: Business Analyst + Product Manager  
**To**: UX/UI Designer  

The BA and PdM hand off a refined set of user stories, process flows, and business rules. The designer uses these inputs to produce wireframes and prototypes. The handoff is complete when the designer has enough context to begin design work without needing to re-elicit requirements.

**Checklist:**
- [ ] User stories include acceptance criteria
- [ ] Process flows and user journey diagrams are documented
- [ ] Key business rules and constraints are noted
- [ ] SME review of requirements is complete

---

### 2. Design → Development
**From**: UX/UI Designer  
**To**: Developers  

Designers hand off annotated design specs, assets, and interaction notes. Developers should be able to implement without ambiguity about layout, behavior, or edge cases.

**Checklist:**
- [ ] Design specs are complete and annotated in the shared design tool
- [ ] Assets (icons, images, tokens) are exported and accessible
- [ ] Interaction states (hover, error, empty, loading) are documented
- [ ] Accessibility requirements are noted
- [ ] Designer is available during development for clarification questions

---

### 3. Development → QA
**From**: Developers  
**To**: QA / Test Engineers  

Developers hand off completed features for testing. The QA team validates against acceptance criteria and test plans prepared during planning.

**Checklist:**
- [ ] Feature branch is deployed to the test environment
- [ ] Developer has completed a self-review and basic smoke test
- [ ] Acceptance criteria are clearly documented on the ticket
- [ ] Known limitations or out-of-scope items are noted
- [ ] Unit and integration tests pass in CI

---

### 4. QA → Release
**From**: QA / Test Engineers  
**To**: Project Manager + Developers  

QA provides a test summary and release readiness sign-off. The PM coordinates the release based on this input.

**Checklist:**
- [ ] All planned test cases executed; results documented
- [ ] All blocking defects resolved or documented as accepted risks
- [ ] Regression suite passes
- [ ] Test summary shared with PM and PdM
- [ ] QA sign-off recorded on the release ticket

---

### 5. SME Consultation Points
Subject Matter Experts are typically engaged at the following moments rather than continuously:

| When | Why |
|---|---|
| Requirements elicitation (initiation/planning) | Validate that requirements accurately reflect domain needs |
| Design review | Confirm that UI/UX aligns with domain workflows and terminology |
| Test plan review | Identify domain-specific edge cases to include in test scenarios |
| UAT | Provide domain sign-off on whether the solution is fit for use |
| Post-release review | Advise on any operational or domain issues surfaced after go-live |

---

## Cross-Functional Collaboration Tips

- **Involve QA early**: QA/Test Engineers should review acceptance criteria during sprint planning, not after development is complete. Early involvement reduces late-breaking defects.
- **Design and development overlap**: Designers should be working on the next sprint's designs while the current sprint's designs are being built. This reduces idle time and allows design decisions to be validated before they block development.
- **BA-PdM partnership**: Business Analysts and Product Managers work most effectively when they operate as partners: PdM owns the *what* and *why*, BA owns the *how it works in detail*. Clear division prevents duplication and gaps.
- **SME scheduling**: Because SMEs are typically part-time contributors, schedule their review windows at the start of each phase so they can plan accordingly. Avoid last-minute SME dependencies.
- **Close the feedback loop**: After UAT or release, ensure that feedback from Business Analysts, SMEs, and QA is fed back into the retrospective. This supports continuous improvement across the whole team.
