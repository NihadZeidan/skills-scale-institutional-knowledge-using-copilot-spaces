# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

### Quality Handoff Process
**Developer → QA Lead:**
1. Developer marks PR as ready for review after CI passes
2. PR includes link to test plan or test coverage report
3. QA Lead reviews test strategy and coverage before feature testing
4. Developer provides demo or walkthrough if needed

**QA Lead → Product Manager:**
1. QA Lead validates acceptance criteria are met
2. Defects are triaged and resolved or deferred with PM approval
3. QA Lead provides sign-off in release checklist
4. PM confirms feature meets business requirements before release

**Business Analyst → Developer:**
1. BA documents requirements with clear acceptance criteria
2. BA available for clarification during implementation
3. Developer confirms understanding before starting work
4. BA validates implemented solution matches requirements

**UX/UI Designer → Developer:**
1. Designer provides finalized mockups and design specs
2. Design assets (icons, images, style tokens) are accessible
3. Developer implements UI according to specifications
4. Designer reviews implementation for design fidelity

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] Handoff responsibilities clear between roles (see Quality Handoff Process)
- [ ] Design assets and requirements accessible to team

## Phase Transition Gates

### Planning → Execution
- [ ] Backlog items have clear acceptance criteria (reviewed by BA and PM)
- [ ] Design mockups finalized and approved (UX/UI Designer sign-off)
- [ ] Test strategy documented (QA Lead approval)
- [ ] Team capacity confirmed (PM coordination)
- [ ] Sprint goals defined (Agile Coach facilitation)

### Execution → Release
- [ ] All acceptance criteria validated (QA Lead sign-off)
- [ ] No critical or high-priority defects remain (PM decision with QA input)
- [ ] Release notes drafted (PM responsible)
- [ ] Deployment runbook reviewed (DevOps/Developer ownership)
- [ ] Stakeholder approval obtained (PM coordination)

For detailed role responsibilities during each phase, see the Role Accountability Matrix in [Project Management Overview](octoacme-project-management-overview.md).
