# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
  - Facilitated by Scrum Master (if available) or Project Manager
  - All roles participate to share updates and identify blockers
- Weekly delivery sync — show progress, updates, and flagged risks
  - Project Manager coordinates; Product Manager, Scrum Master, and key technical leads attend
- Demo/Review at the end of each sprint or milestone
  - UX Designer presents design validations; Developers demo features; QA shares test results

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
Clarified escalation paths ensure blockers are resolved quickly:
- **Level 1 (Team-level)**: Triage in daily standup
  - Scrum Master or Project Manager facilitates resolution
  - Technical blockers: Developer → Senior Developer or Tech Lead
  - Design blockers: UX Designer → Design Lead
  - Infrastructure blockers: DevOps Engineer handles or escalates
- **Level 2 (Cross-team/Management)**: PM escalates to Product Lead and dependent teams
  - Project Manager coordinates with other PMs for cross-team dependencies
  - Business Analyst may support requirement clarification
  - DevOps Engineer escalates infrastructure/platform issues to platform team
- **Level 3 (Executive/Sponsor)**: Sponsor-level escalation for business-impacting issues
  - Project Manager prepares impact summary
  - Product Manager provides business context and priority justification

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] Role handoffs validated and working smoothly
- [ ] Design review cadence established with UX Designer (if applicable)
- [ ] Documentation updates tracked with Technical Writer
- [ ] Deployment pipeline reviewed and tested with DevOps Engineer

---

**Note**: Team rhythm and escalation paths enhanced per [issue #5](https://github.com/krisur/skills-scale-institutional-knowledge-using-copilot-spaces/issues/5) to integrate extended team roles. For role details, see [Roles and Personas](octoacme-roles-and-personas.md).
