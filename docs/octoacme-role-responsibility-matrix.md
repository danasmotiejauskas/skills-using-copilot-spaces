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

## QA Lead / Test Engineer

### Role Summary
QA Leads or Test Engineers own test strategy, verification, and gating for quality. They ensure features meet acceptance criteria and that regressions are minimized.

### Responsibilities
- Define test strategy and acceptance verification approaches (unit, integration, E2E)
- Coordinate test execution and manage test environments
- Triage and prioritize defects, maintain test suites
- Collaborate on DoD and acceptance criteria with PdM and Developers

### Goals
- Reduce production defects and increase confidence in releases
- Maintain reliable, automated test coverage for critical flows
- Ensure clear acceptance criteria are testable

### Typical Communication / Interactions
- Work with Developers for testability improvements
- Sync with Product Manager on acceptance criteria
- Coordinate release testing with Operations/SRE and Project Manager

---

## UX Designer

### Role Summary
UX Designers own user experience, interaction design, and usability validation for features.

### Responsibilities
- Produce design specs, user flows, wireframes, and prototypes
- Run usability research and synthesize findings into actionable changes
- Provide design assets and acceptance criteria for implementation
- Advocate for accessibility and user-centric decisions

### Goals
- Improve user satisfaction, efficiency, and task success
- Reduce rework by clarifying experience early in planning
- Ensure consistent, accessible product UI patterns

### Typical Communication / Interactions
- Collaborate closely with Product Manager on acceptance and trade-offs
- Work with Developers to ensure implementable designs
- Provide artifacts to QA for design validation

---

## Business Analyst (BA)

### Role Summary
Business Analysts bridge domain knowledge and engineering. They clarify requirements, refine scope, and translate stakeholder needs into actionable backlog items.

### Responsibilities
- Elicit detailed requirements and model business processes
- Produce user stories, acceptance criteria, and data/edge-case clarifications
- Support stakeholder workshops and requirements sign-off
- Assist Product Manager with prioritization by quantifying value and effort

### Goals
- Reduce ambiguity in requirements
- Improve estimation accuracy and reduce rework
- Ensure traceability from business need to implementation

### Typical Communication / Interactions
- Works with Product Manager and Stakeholders to refine scope
- Hands off clear, testable stories to Developers and QA
- Coordinates cross-team requirements discussions

---

## Operations / SRE

### Role Summary
Operations/SRE ensures reliability, observability, and safe, automatable runbooks for production systems.

### Responsibilities
- Define operational requirements, SLOs, and monitoring needs
- Support release automation, runbooks, and incident response
- Participate in release planning and rollback strategy
- Run post-incident reviews and contribute reliability improvements

### Goals
- Maintain system availability and reduce incident impact
- Automate operational tasks to reduce manual risk
- Improve observability across services

### Typical Communication / Interactions
- Collaborate on deployment steps with Project Manager and Release Manager
- Provide monitoring and alerting requirements to Developers
- Coordinate on-call and incident handoffs

---

## Stakeholder (Sponsor / SME / External Partner)

### Role Summary
Stakeholders provide domain context, business priorities, and approvals. They are not part of day-to-day delivery but are critical for alignment and decisions.

### Responsibilities
- Provide domain inputs, constraints, and priorities
- Approve high-impact decisions and deliverables
- Review milestone outcomes and provide feedback
- Participate in key gating decisions (go/no-go)

### Goals
- Ensure project outcomes meet business needs
- Remove blockers that require senior decisions
- Communicate changes from their organization to the delivery team

### Typical Communication / Interactions
- Regularly review status reports and milestone demos
- Engage in stakeholder alignment and escalation paths
- Provide acceptance for major deliverables

---

## Release Manager (optional role)

### Role Summary
When projects are frequent or complex, a Release Manager coordinates releases across teams and ensures checklist compliance.

### Responsibilities
- Own the release calendar and dependencies
- Coordinate release readiness, runbooks, and communication
- Gate releases against the checklist and rollback plans

### Goals
- Minimize release collisions and reduce production risk
- Keep release processes predictable and auditable

### Typical Communication / Interactions
- Works with Project Manager, SRE, QA, and PdM during release windows
- Notifies Stakeholders and Support channels when releases occur

---

## How these personas interact (summary)

- Business Analyst & Product Manager: define, refine, and scope backlog items; BA provides detailed stories and edge cases.
- UX Designer & Developers: iterate on implementable designs and resolve implementation questions early.
- QA Lead & Developers: ensure testability; QA validates acceptance criteria and coordinates test runs.
- Operations/SRE & Developers: define deployment requirements, monitoring, and rollback processes.
- Project Manager & Release Manager: sync schedules, release readiness checklists, and stakeholder communication.
- Stakeholders & Project/Product leads: approve scope changes and provide constraints; escalate business-impacting decisions.

Clear hand-offs and documented collaboration points help reduce overlap, speed decision-making, and clarify ownership for each deliverable.

---

## How these personas are used in exercises and process docs

- Use personas to craft scenarios and define responsibility in examples.
- Include persona-specific checklists or acceptance criteria where relevant.
- Maintain a single “role / responsibility” reference (see role-responsibility-matrix) for quick onboarding and RACI decisions.