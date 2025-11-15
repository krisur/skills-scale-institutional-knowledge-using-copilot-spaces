# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support, executive leadership)
- Assign communication owners by stakeholder type:
  - **Technical stakeholders**: Project Manager + Tech Lead
  - **Business stakeholders**: Product Manager + Business Analyst
  - **User/customer stakeholders**: Product Manager + UX Designer
  - **Executive stakeholders**: Project Manager + Product Manager
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- Technical Writer maintains and publishes customer-facing documentation

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

---

**Note**: Escalation paths and stakeholder communication clarified per [issue #5](https://github.com/krisur/skills-scale-institutional-knowledge-using-copilot-spaces/issues/5) to include all team roles. For role details, see [Roles and Personas](octoacme-roles-and-personas.md).

## Escalation Paths
Clear escalation paths ensure timely resolution of issues:

### Technical Issues
- Developer → Tech Lead → Engineering Manager
- DevOps Engineer → Platform Team Lead → Infrastructure Director
- UX Designer → Design Lead → Head of Design

### Product/Scope Issues
- Business Analyst → Product Manager → Product Lead → Sponsor
- Project Manager → Product Lead → Sponsor

### Process/Team Issues
- Scrum Master → Project Manager → Engineering Manager
- Any team member → Scrum Master (for impediments)

### Security/Compliance Issues
- Any team member → Security Team (via security incident runbook)
- DevOps Engineer → Security on-call (for infrastructure security)

### Cross-functional Coordination
- Project Manager coordinates escalations across teams
- Product Manager provides business context for prioritization decisions
