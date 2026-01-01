# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- **Project Manager (PM):** coordinates delivery, schedules, risk, communications.
- **Product Manager (PdM):** defines outcomes, prioritizes backlog, and measures success.
- **Developers:** implement features, collaborate on design and testability.
- **QA Lead:** validates quality and acceptance criteria, manages test strategy.
- **Agile Coach:** facilitates agile ceremonies and coaches team on best practices.
- **Business Analyst:** elicits requirements and bridges stakeholder-development communication.
- **UX/UI Designer:** designs user experiences and interfaces aligned with user needs.
- **Stakeholders:** provide inputs and approvals.

For detailed role definitions and responsibilities, see [OctoAcme Roles and Personas](octoacme-roles-and-personas.md).

## Role Accountability Matrix

| Phase | Project Manager | Product Manager | Developer | QA Lead | Agile Coach | Business Analyst | UX/UI Designer |
|-------|----------------|-----------------|-----------|---------|-------------|------------------|----------------|
| **Initiation** | Accountable for project charter | Responsible for problem statement & metrics | Consulted on technical feasibility | Consulted on testability | Consulted on process setup | Responsible for requirements gathering | Consulted on UX research needs |
| **Planning** | Accountable for project plan & timeline | Accountable for backlog prioritization | Responsible for technical estimates | Responsible for test strategy | Accountable for sprint setup | Responsible for detailed requirements | Responsible for design mockups |
| **Execution** | Accountable for coordination & risk | Informed of progress & blockers | Accountable for implementation | Accountable for quality validation | Responsible for ceremony facilitation | Consulted on requirement clarifications | Responsible for design implementation support |
| **Release** | Accountable for deployment coordination | Accountable for go/no-go decision | Responsible for deployment execution | Accountable for release quality sign-off | Informed of release status | Responsible for UAT coordination | Responsible for UI validation |
| **Retrospective** | Responsible for action tracking | Informed of process improvements | Participates in retrospective | Participates in retrospective | Accountable for retrospective facilitation | Participates in retrospective | Participates in retrospective |

**RACI Legend:** 
- **R**esponsible: Does the work
- **A**ccountable: Ultimately answerable for completion
- **C**onsulted: Provides input and expertise
- **I**nformed: Kept up-to-date on progress

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.

## Related Documentation
- [OctoAcme Roles and Personas](octoacme-roles-and-personas.md) - Detailed role definitions and responsibilities
- [Project Initiation Guide](octoacme-project-initiation.md) - Starting new projects
- [Project Planning](octoacme-project-planning.md) - Creating actionable plans
- [Execution & Tracking](octoacme-execution-and-tracking.md) - Day-to-day execution
- [Risk Management & Communication](octoacme-risks-and-communication.md) - Managing risks and stakeholder communication
