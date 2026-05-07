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

## Technical Program Managers

### Role Summary
Technical Program Managers (TPMs) connect business planning with technical execution across multiple teams. They drive dependency management, technical milestone planning, and escalation paths for cross-functional delivery.

### Responsibilities
- Define and maintain cross-team delivery plans for technical initiatives
- Track cross-team dependencies, integration risks, and critical path items
- Coordinate technical decision deadlines and escalation workflows
- Ensure milestone readiness criteria are clear and measurable
- Partner with Project Managers to keep delivery reporting consistent

### Goals
- Reduce delivery delays caused by unmanaged dependencies
- Improve predictability for complex, multi-team programs
- Create faster, clearer escalation and decision cycles

### Typical Communication
- Weekly cross-team dependency reviews
- Technical milestone readiness updates
- Escalation briefs for senior stakeholders

### Interactions with Existing Roles
- Project Managers: Co-own integrated plans, risks, and status reporting for multi-team execution
- Product Managers: Align feature sequencing with technical dependency constraints
- Developers: Remove blockers related to cross-team handoffs, architecture dependencies, and environment readiness

---

## Engineering Managers

### Role Summary
Engineering Managers lead team delivery health by balancing execution, people management, and technical quality. They ensure realistic capacity planning, sustainable delivery pace, and strong engineering standards.

### Responsibilities
- Own engineering capacity planning and team workload balancing
- Support technical quality through review practices, standards, and coaching
- Manage delivery health indicators (throughput, defects, reliability trends)
- Escalate staffing or delivery risks early to Project and Program leaders
- Drive continuous improvement in engineering ways of working

### Goals
- Maintain a sustainable and predictable delivery cadence
- Improve engineering quality and reduce defect leakage
- Strengthen team performance and accountability

### Typical Communication
- Sprint and iteration planning with PM and project leads
- Team health check-ins and capacity updates
- Engineering quality and reliability reviews

### Interactions with Existing Roles
- Developers: Provide coaching, remove local execution blockers, and align expectations on quality
- Product Managers: Validate delivery feasibility against priority and scope changes
- Project Managers: Share capacity constraints, schedule risks, and mitigation plans

---

## Quality Assurance Leads

### Role Summary
Quality Assurance (QA) Leads define test strategy and quality gates across the delivery lifecycle. They ensure that release decisions are informed by risk and evidence, not only by schedule pressure.

### Responsibilities
- Define test plans and quality criteria for major deliverables
- Coordinate test execution coverage across functional and non-functional areas
- Track defect trends and prioritize remediation with engineering
- Recommend release go or no-go decisions based on quality evidence
- Maintain traceability between requirements, test cases, and outcomes

### Goals
- Reduce production defects and customer-facing incidents
- Increase confidence in release readiness
- Improve quality feedback speed during development

### Typical Communication
- Test strategy reviews during planning
- Defect triage sessions with engineering and PMs
- Release readiness summaries before deployment milestones

### Interactions with Existing Roles
- Developers: Provide fast defect feedback and collaborate on prevention patterns
- Product Managers: Confirm acceptance criteria are testable and complete
- Project Managers: Align testing milestones with schedule and release plans

---

## Release Managers

### Role Summary
Release Managers coordinate release readiness, cutover planning, and deployment governance. They ensure that release activities are sequenced, controlled, and communicated across teams.

### Responsibilities
- Build and maintain release calendars and cutover checklists
- Coordinate go-live dependencies, approvals, and rollback plans
- Ensure change management and release communications are complete
- Facilitate final readiness reviews and release sign-off workflows
- Capture post-release outcomes and improvement actions

### Goals
- Improve release reliability and reduce deployment risk
- Minimize service disruption during production changes
- Increase consistency of release governance across teams

### Typical Communication
- Release planning and cutover meetings
- Go-live decision updates to stakeholders
- Post-release reports and improvement follow-ups

### Interactions with Existing Roles
- Project Managers: Align release milestones with overall project timelines
- Developers: Confirm deployment readiness, runbooks, and rollback procedures
- Product Managers: Coordinate release scope decisions and stakeholder messaging

---

## Interaction Model for Accountability

To improve handoff quality and accountability, use this lightweight ownership model for key delivery moments:

- Scope and priority decisions: Product Managers lead, with input from Project Managers and Engineering Managers
- Delivery timeline and dependency health: Project Managers and Technical Program Managers co-own
- Team capacity and engineering quality standards: Engineering Managers lead with Developers
- Quality gates and release readiness: QA Leads and Release Managers co-own with Project Managers
- Escalations and cross-functional blockers: Technical Program Managers coordinate with relevant leads

This model complements existing role definitions and helps teams make faster decisions with clear ownership.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

