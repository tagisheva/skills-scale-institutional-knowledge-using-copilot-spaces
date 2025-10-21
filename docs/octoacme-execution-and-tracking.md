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

## Role Handoff Template
When transitioning work between team members or roles:

### Handoff Information
- From: [Name, Role]
- To: [Name, Role]
- Date:
- Project/Component:

### Context Transfer
- [ ] Current status and recent progress summarized
- [ ] Outstanding tasks and priorities documented
- [ ] Known issues, blockers, and risks identified
- [ ] Dependencies and stakeholder contacts listed
- [ ] Relevant documentation links provided (design docs, PRs, issues)
- [ ] Access and credentials transferred (if applicable)
- [ ] Handoff meeting scheduled and completed
- [ ] Transition period agreed upon (if needed)
- [ ] First task completed by new assignee and reviewed

### Critical Information
- What's working well:
- What needs immediate attention:
- Key stakeholders to engage:
- Next milestones:
