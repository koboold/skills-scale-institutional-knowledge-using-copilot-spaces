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
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support, customers)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

### Role-Based Communication Responsibilities
- **Project Manager**: Overall status updates, risk communication, stakeholder coordination
- **Product Manager**: Feature rationale, success metrics, roadmap updates
- **Change Manager**: Change notifications, impact assessments, approval tracking
- **Support Engineer**: Customer-facing communications, known issues, workarounds
- **UX Designer**: Design decisions, usability findings, accessibility compliance
- **SME**: Technical advisories, domain-specific guidance, expert recommendations

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

## Escalation Paths
- **Standard escalation**: Team-level → PM → Product Lead → Sponsor
- **Security incidents**: Follow the security incident runbook and notify Security on-call immediately
- **Customer-impacting issues**: PM → Support Engineer → Customer Success → Product Lead
- **Design/UX concerns**: Developer → UX Designer → Product Manager → Design Lead
- **Technical complexity**: Developer → SME → Tech Lead → Engineering Manager
- **Scope changes**: Any team member → PM → Change Manager → Sponsor (for approval)
