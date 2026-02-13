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
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support, security, compliance)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- Tailor communication style and detail to audience needs

## Cross-Functional Communication Guidelines

### Design-to-Development Handoff
- UX Designer shares design specifications and user research insights
- Developers ask clarifying questions during design review
- QA participates in design review to understand acceptance criteria
- Document design decisions and rationale for future reference

### Security Review Process
- Security Specialist reviews design and code at key milestones
- Developers address security findings and document decisions
- DevOps Engineer implements security scanning in CI/CD pipeline
- Project Manager tracks security-related risks and timelines

### Release Coordination
- DevOps Engineer provides deployment plan and timeline
- QA confirms test completion and sign-off
- Product Manager validates feature completeness
- Project Manager coordinates stakeholder communication
- Security Specialist confirms security requirements are met

### Requirements Clarification
- Business Analyst documents requirements and business rules
- Product Manager validates alignment with product vision
- Developers estimate complexity and identify technical constraints
- UX Designer ensures requirements support user needs

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
- Team-level → PM → Product Lead → Sponsor
- For security incidents, follow the security incident runbook and notify Security Specialist and Security on-call
- For deployment issues, engage DevOps Engineer immediately
- For usability concerns, involve UX Designer in design review
- For requirements ambiguity, consult Business Analyst and Product Manager
