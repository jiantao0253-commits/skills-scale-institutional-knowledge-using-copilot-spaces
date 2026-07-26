# OctoAcme Project Management Docs

## Overview

OctoAcme follows a comprehensive, lifecycle-based approach to project management grounded in **customer-first principles** and **iterative delivery**. This documentation serves as the central hub for understanding and navigating our project management framework, enabling team members to execute consistently and transparently across all project phases.

## The OctoAcme Lifecycle

OctoAcme's project management process spans five distinct phases:

### 1. **Initiation**
Validate business needs and create lightweight project charters. The team establishes success metrics, identifies stakeholders, and creates a Project One-pager to serve as the decision gate. Only well-scoped initiatives with clear sponsor support move forward to planning.

### 2. **Planning**
Break approved work into shippable increments with clear acceptance criteria. Define the Definition of Done, identify dependencies and risks, create prioritized backlogs, and establish a release timeline. Planning is collaborative, involving stakeholders and the delivery team.

### 3. **Execution**
Build, test, and review work in daily standups and structured sprints. Maintain a project board with clear workflow stages (Backlog → Ready → In Progress → In Review → QA → Done). Use small PRs, automated testing, and continuous integration to keep quality high and cycle time low.

### 4. **Release**
Deploy features to production with confidence through pre-release checks, deployment checklists, smoke tests, and rollback plans. Ensure all acceptance criteria are met, CI passes, and release notes are prepared. Post-deployment verification confirms success.

### 5. **Close & Retrospective**
Capture learnings and convert them into actionable improvements. Retrospectives follow a structured format (what went well, what could improve, action items), with improvements feeding back into the backlog. This creates a culture of continuous, data-informed iteration.

## Key Principles

- **Customer-first**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Deliver small, testable increments regularly
- **Clear ownership**: Each project has named roles and clear accountability
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and blameless retrospectives

## Core Roles

- **Project Manager**: Coordinates delivery, manages schedules, risks, and communications
- **Product Manager**: Defines outcomes, prioritizes backlog, measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validates quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and strategic direction

See [Roles and Personas](./octoacme-roles-and-personas.md) for detailed responsibilities.

## Communication Cadence

- **Daily standups**: 15 minutes on progress, blockers, and dependencies
- **Weekly PM sync**: Product Manager and Project Manager alignment
- **Twice-weekly delivery standups**: Team execution updates (or as agreed)
- **Monthly stakeholder updates**: Progress, metrics, and risk summaries
- **Ad-hoc escalations**: Follow clear three-level escalation path (team → PM → Product Lead → Sponsor)

## Quality & Risk Management

Quality is embedded throughout execution:
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows
- Security scanning in CI
- Manual QA for feature acceptance
- Small PRs (≤ 400 lines when possible)
- Automated tests and linting before review approval

Risks are actively managed via a **Risk Register** with clear ownership and mitigation plans, continuously monitored during weekly syncs. Blockers follow a clear escalation protocol: Level 1 (team triage) → Level 2 (PM escalation) → Level 3 (Sponsor escalation).

## Process Documentation

Navigate to specific process documents using the links below:

| Document | Purpose |
|----------|---------|
| [Project Management Overview](./octoacme-project-management-overview.md) | Concise introduction to OctoAcme's approach, roles, and key artifacts |
| [Project Initiation](./octoacme-project-initiation.md) | Initial steps to validate work, align stakeholders, and create a lightweight plan |
| [Project Planning](./octoacme-project-planning.md) | Break approved initiatives into actionable plans and prioritized backlogs |
| [Execution and Tracking](./octoacme-execution-and-tracking.md) | Day-to-day execution, team rhythm, and progress tracking toward milestones |
| [Risks and Communication](./octoacme-risks-and-communication.md) | Identify, manage, and communicate risks, dependencies, and escalations |
| [Release and Deployment](./octoacme-release-and-deployment.md) | Standardize releases to production with reduced risk and improved observability |
| [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert them into actionable improvements |
| [Roles and Personas](./octoacme-roles-and-personas.md) | Detailed role definitions and responsibilities for all personas |

## Getting Started

**For new team members:**
1. Start with [Project Management Overview](./octoacme-project-management-overview.md) for a 5-minute orientation
2. Review [Roles and Personas](./octoacme-roles-and-personas.md) to understand your role and how it fits
3. Dive into the specific phase documentation as your project progresses

**For Project Managers:**
- Use [Project Initiation](./octoacme-project-initiation.md) and [Project Planning](./octoacme-project-planning.md) for new projects
- Reference [Execution and Tracking](./octoacme-execution-and-tracking.md) daily
- Maintain the Risk Register using [Risks and Communication](./octoacme-risks-and-communication.md) guidance

**For Product Managers:**
- Define success metrics and roadmaps in [Project Initiation](./octoacme-project-initiation.md)
- Prioritize backlogs and acceptance criteria in [Project Planning](./octoacme-project-planning.md)
- Track outcomes and iterations via [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

**For Developers:**
- Understand acceptance criteria and Definition of Done in [Project Planning](./octoacme-project-planning.md)
- Follow workflows in [Execution and Tracking](./octoacme-execution-and-tracking.md)
- Participate in retrospectives using [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

## Contributing to These Docs

Found a gap or want to propose an update? Use the issue template **[Add Content to Project Management Process Docs](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** to request changes.

---

**Last Updated:** July 2026  
**Owner:** OctoAcme Project Management Community
