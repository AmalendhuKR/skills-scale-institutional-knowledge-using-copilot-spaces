# OctoAcme Project Management Process Documentation

## Overview

OctoAcme uses a structured, customer-first project management approach to deliver features, services, and integrations. Our methodology emphasizes iterative delivery, clear ownership, data-informed decisions, and psychological safety.

OctoAcme follows a phase-gated approach to project delivery that emphasizes customer value, iterative execution, and data-driven decision-making. The organization defines clear role clarity across three primary personas: **Project Managers** coordinate delivery schedules, manage risks, and facilitate communication; **Product Managers** define customer value, prioritize the backlog, and measure outcomes; and **Developers** implement features, maintain tests, and identify technical risks. Quality and risk management are embedded throughout the project lifecycle rather than treated as afterthoughts, with teams maintaining a Risk Register reviewed weekly during execution syncs. Small pull requests (≤400 lines), mandatory code review, and automated testing gates ensure sustainable velocity and maintainable code, while retrospectives after each sprint or release systematize learning and drive continuous process improvement.

## Project Lifecycle

Every OctoAcme project follows this five-phase lifecycle:

1. **Initiation** - Define the problem, identify stakeholders, and establish initial success metrics
2. **Planning** - Break work into shippable increments, estimate scope, and plan releases
3. **Execution** - Build, test, review, and iterate with daily standups and weekly syncs
4. **Release** - Deploy to production with proper validation and rollback plans
5. **Close & Retrospective** - Capture learnings and drive continuous improvement

## Core Roles

- **Project Manager (PM)** - Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM)** - Defines outcomes, prioritizes backlog, and measures success
- **Developers** - Implement features, collaborate on design, and maintain quality standards
- **QA/Testing** - Validate quality and acceptance criteria
- **Stakeholders** - Provide inputs, approvals, and strategic direction

## Process Documentation

| Phase | Document | Purpose |
|-------|----------|---------|
| Overview | [OctoAcme Project Management Overview](octoacme-project-management-overview.md) | Introduction to roles, principles, and lifecycle |
| Initiation | [Project Initiation Guide](octoacme-project-initiation.md) | Define business need, align stakeholders, create one-pager |
| Planning | [Project Planning](octoacme-project-planning.md) | Break work into increments, estimate, identify dependencies |
| Execution | [Execution & Tracking](octoacme-execution-and-tracking.md) | Daily standups, sprint workflow, quality standards |
| Risk & Comms | [Risk Management & Communication](octoacme-risks-and-communication.md) | Risk registers, stakeholder updates, escalation paths |
| Release | [Release & Deployment Guide](octoacme-release-and-deployment.md) | Pre-release checklist, deployment process, rollback plans |
| Retrospective | [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings, track action items, measure improvements |
| Reference | [OctoAcme Personas](octoacme-roles-and-personas.md) | Detailed role definitions and communication patterns |

## Key Workflows & Practices

### Communication Cadence
- **Daily standups** - Focus on progress, blockers, and dependencies
- **Weekly PM-PdM sync** - Align strategy and delivery
- **Twice-weekly team standups** - Maintain momentum (or as agreed)
- **Monthly stakeholder updates** - Provide business visibility
- **Ad-hoc escalations** - For urgent issues and blockers

### Quality Assurance
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed
- Small pull requests (≤400 lines when possible)
- Require at least one approval before merging

### Risk Management
Teams maintain a **Risk Register** that captures:
- ID, Description, Impact (High/Med/Low), Likelihood (High/Med/Low)
- Owner and Mitigation plan
- Status (tracked weekly during execution syncs)

### Escalation Paths
- **Level 1**: Team-level triage in daily standup
- **Level 2**: PM escalates to Product Lead and dependent teams
- **Level 3**: Sponsor-level escalation for business-impacting issues

## Getting Started

- **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md)
- **Ready to kick off a project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md)
- **Leading delivery?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md)
- **Planning a release?** Review [Release & Deployment Guide](octoacme-release-and-deployment.md)
- **Understanding roles?** See [OctoAcme Personas](octoacme-roles-and-personas.md)

## Questions or Suggestions?

For clarification on any process or to propose improvements, open an issue using the [Add Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template.
