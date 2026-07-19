# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Recommended Personas (new)

Below are proposed additions to clarify responsibilities, improve handoffs, and close gaps identified in the process docs.

### Delivery Lead
- Responsibilities:
  - Coordinate day-to-day delivery across teams and sprints.
  - Track cross-team dependencies and unblock work.
  - Ensure sprint commitments are realistic and adjusted for risk.
- Interactions:
  - Works closely with Project Manager (scheduling, risk), Developers (capacity, blockers), and QA (acceptance readiness).
  - Escalates issues to PM or Product Lead when needed.

### Engineering Manager
- Responsibilities:
  - Provide technical leadership and coaching.
  - Plan team capacity and prioritize engineering work (including debt).
  - Own people-development and performance concerns related to delivery.
- Interactions:
  - Collaborates with Product Manager on trade-offs and technical feasibility.
  - Coordinates with Developers on implementation approach and estimates.

### UX Researcher / Designer
- Responsibilities:
  - Conduct user research and synthesize findings into requirements.
  - Produce user flows, mockups, and accessible designs.
  - Validate acceptance criteria from a user perspective.
- Interactions:
  - Partners with Product Manager on user outcomes and success metrics.
  - Works with Developers to ensure designs are implemented as intended.

### QA Lead / Test Owner
- Responsibilities:
  - Define the test strategy and own test plans and automation coverage.
  - Coordinate manual QA and exploratory testing for acceptance.
  - Track test coverage and release readiness criteria.
- Interactions:
  - Works with Developers to create testable acceptance criteria.
  - Coordinates with Release Manager and PM for pre-release sign-off.

### Release Manager
- Responsibilities:
  - Coordinate releases across services and teams.
  - Maintain the release checklist and rollback/mitigation plans.
  - Own post-deploy verification and release communications.
- Interactions:
  - Coordinates with PM, Delivery Lead, Engineering Manager, and Support/On-call teams.

### Security & Compliance Owner
- Responsibilities:
  - Ensure security requirements and compliance controls are captured and tracked.
  - Lead security reviews and risk mitigations for releases.
  - Coordinate with Security/Compliance teams on audits and findings.
- Interactions:
  - Engages with Developers, Engineering Manager, and PM during planning and before releases.

### Observability / SRE Owner
- Responsibilities:
  - Define monitoring and alerting requirements; maintain runbooks.
  - Own on-call readiness and production health for the project.
  - Coordinate performance and reliability improvements.
- Interactions:
  - Works with Developers and Release Manager to ensure production readiness and incident response plans.

### Stakeholder Representative (Business Owner)
- Responsibilities:
  - Serve as a named contact for prioritization and business decisions.
  - Accept feature outcomes and provide timely direction on scope changes.
- Interactions:
  - Works with PM and Product Manager; participates in milestone reviews and acceptance gating.

Notes:
- Each new role includes a short "Responsibilities" and "Interactions" subsection to show how they coordinate with existing roles.
- Keep descriptions concise (1–3 bullets) and use consistent formatting.
- Where relevant, link to related artifacts (release checklist, risk register, runbooks).
