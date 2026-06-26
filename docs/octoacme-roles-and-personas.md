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

## Additional Personas (proposed additions)

To close documented gaps and improve cross-functional clarity, add the following personas. Each persona includes a short responsibilities list and an interactions subsection mapping handoffs with PM, PdM, Developers, QA, and Project Managers.

### UX Researcher / Designer
- Responsibilities:
  - Conducts user research (interviews, usability tests), synthesizes findings, defines user needs and journeys.
  - Produces wireframes, mockups, and interactive prototypes aligned to acceptance criteria.
  - Supports usability validation during QA and pre-release checks.
- Interactions:
  - Works with Product Managers to validate problem hypotheses and shape acceptance criteria.
  - Partners with Developers on implementation feasibility and with QA on usability test cases.
  - Contributes to release notes where user-facing behavior changes.

### Tech Lead / Engineering Manager
- Responsibilities:
  - Provides technical leadership and architecture guidance.
  - Owns technical trade-offs, design reviews, and mentoring.
  - Ensures code quality, performance, and maintainability standards.
- Interactions:
  - Collaborates with PMs on scope, estimates, and risk assessment.
  - Coordinates with Developers on designs and with Release/Platform Engineers on deployment readiness.
  - Engages in post-incident technical root cause analysis.

### Release / Platform Engineer (DevOps / SRE)
- Responsibilities:
  - Maintains CI/CD pipelines, deployment automation, and production runbooks.
  - Owns release safety checks, feature flags, and rollback procedures.
  - Monitors production health and supports incident response.
- Interactions:
  - Works with Developers and Tech Lead to implement CI/CD and observability requirements.
  - Coordinates with PM/Project Manager on release windows and deployment plans.
  - Supports Support/Customer Success during major incidents.

### Data Analyst / ML Ops
- Responsibilities:
  - Defines measurement plans, builds dashboards, and validates success metrics.
  - Produces regular analyses to inform prioritization and product decisions.
  - Ensures data quality and instrumentation for experiments.
- Interactions:
  - Works with Product Managers to define and track success metrics.
  - Provides data for sprint retrospectives and decision-making.
  - Partners with QA to prepare test datasets where relevant.

### Security & Compliance Lead
- Responsibilities:
  - Evaluates security and compliance risks for features and releases.
  - Conducts security reviews, approves controls, and ensures regulatory alignment.
  - Owns sensitive-data handling and compliance-related documentation.
- Interactions:
  - Engages during planning and design with Product Managers and Tech Leads.
  - Sets acceptance criteria for security and approves gating conditions for production releases.
  - Coordinates with Release/Platform Engineers for secure deployment.

### Customer Success / Support Lead
- Responsibilities:
  - Owns post-release customer communications and onboarding material.
  - Triages user-reported issues and tracks severity/impact.
  - Collects customer feedback and ensures high-impact issues reach the backlog.
- Interactions:
  - Works with PMs to prioritize production fixes and feature improvements.
  - Notifies Project Managers and stakeholders of major customer-impact incidents.
  - Feeds insights into product discovery and backlog refinement.

### Business Analyst / Requirements Analyst
- Responsibilities:
  - Translates stakeholder inputs into clear requirements, workflows, and acceptance criteria.
  - Produces process flows, data requirements, and non-functional specs where needed.
- Interactions:
  - Collaborates with Product Managers and Stakeholders to reduce ambiguity in scope.
  - Works with Developers to ensure requirements are implementable and testable.
  - Supports QA with edge-case scenarios and test data requirements.

---

## Examples: Where these personas contribute (short workflows)

- Release Handoff:
  - Product Manager confirms acceptance criteria and feature scope.
  - Developers and Tech Lead finalize code and tests.
  - Release Engineer runs pre-release checks and schedules deployment.
  - Customer Success drafts communications; Support prepares playbooks.
  - Security Lead signs off on any compliance gating checks.

- Incident Escalation:
  - Support/Customer Success triages and escalates to Project Manager and Release Engineer.
  - Release Engineer and Tech Lead drive mitigation and rollback as needed.
  - Product Manager coordinates stakeholder updates; Data Analyst assesses impact.
  - Post-incident, owners produce RCA and action items, tracked via backlog.

(End of proposed additions)
