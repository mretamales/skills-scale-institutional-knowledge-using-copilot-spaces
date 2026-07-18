# OctoAcme Project Management Processes

Welcome to OctoAcme's project management documentation! This README provides quick links to our process docs and a concise summary of how we run projects.

## Quick Links to Process Docs

- **[Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, roles, and key artifacts
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Initial steps to validate work, align stakeholders, and create a lightweight plan
- **[Project Planning](./octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog for delivery
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution and tracking progress toward milestones
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — How to identify, manage, and communicate risks and dependencies
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Standardize releases and reduce deployment risk
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Define typical roles and responsibilities (Developers, Product Managers, Project Managers)

## OctoAcme Project Management at a Glance

### Our Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

### Team Rhythm & Cadence
- **Daily standups** (15 min) — Focus on progress, blockers, and dependencies
- **Weekly delivery sync** — Show progress, updates, and flagged risks
- **Sprint/milestone demos** — Review and celebrate completed work
- **Monthly stakeholder updates** — Keep sponsors and stakeholders informed

### Core Roles
- **Project Manager (PM)** — Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM)** — Defines outcomes, prioritizes backlog, and measures success
- **Developers** — Implement features, collaborate on design and testability
- **QA/Testing** — Validate quality and acceptance criteria
- **Stakeholders** — Provide inputs and approvals

### Project Lifecycle

1. **Initiation** — Problem statement, stakeholders, high-level timeline
2. **Planning** — Scope, resources, milestones, dependencies, Definition of Done
3. **Execution** — Build, test, review, iterate with clear PR workflows and CI/CD
4. **Release** — Deploy, verify, and announce to stakeholders
5. **Close & Retrospective** — Capture learnings and feed improvements back into the process

### Key Artifacts

We maintain several key artifacts throughout the project lifecycle:

- **Project Charter / One-pager** — Problem, goal, success metrics, stakeholders, timeline, risks
- **Prioritized Backlog** — Clear acceptance criteria and Definition of Done
- **Release Plan** — Milestones, dependencies, integration points
- **Risk Register** — ID, description, impact, likelihood, owner, mitigation plan
- **Status & Communication** — Weekly updates, escalation paths, stakeholder alignment
- **Retrospective Notes** — Action items with owners and due dates

### Pull Request & Quality Standards

- **Small PRs** — ≤ 400 lines when possible for easier review
- **Acceptance criteria** — Clearly included in PR description with issue link
- **Automated testing** — CI must pass (tests, linting, security scans) before review request
- **Approval gates** — Require at least one approval before merging
- **Test coverage** — Unit tests for new logic, integration tests where applicable, E2E smoke tests for critical flows

## Where to Start

- **New to OctoAcme?** Start with the [Project Management Overview](./octoacme-project-management-overview.md)
- **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md)
- **In the middle of execution?** Check [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management & Communication](./octoacme-risks-and-communication.md)
- **Preparing a release?** Review the [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- **Completing a project?** Schedule a [Retrospective](./octoacme-retrospective-and-continuous-improvement.md)

## Communication & Escalation

### Standard Communication Cadence
- Weekly sync between PM and PdM
- Twice-weekly standups for delivery team
- Monthly stakeholder updates
- Ad-hoc escalations as needed

### Escalation Paths
1. **Level 1** — Team-level triage in daily standup
2. **Level 2** — PM escalates to Product Lead and dependent teams
3. **Level 3** — Sponsor-level escalation for business-impacting issues

---

For more details on any specific area, refer to the linked process documents above. Questions? Reach out to your Project Manager or Product Lead.
