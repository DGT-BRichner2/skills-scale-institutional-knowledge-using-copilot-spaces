# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

The roles below describe functions, not necessarily separate positions. Teams should explicitly assign each function; one person may hold more than one role, depending on the project's size and needs.

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

## Executive Sponsors

### Role Summary
Executive Sponsors champion the project's strategic purpose, secure organizational support, and make or escalate decisions that exceed the project team's authority.

### Responsibilities
- Confirm the project's alignment with organizational goals and expected outcomes
- Help secure funding, staffing, and cross-team support
- Resolve escalated priority, scope, or resource conflicts
- Review progress and decide on major changes or continuation when needed

### Goals
- Realize the intended business outcomes
- Ensure the project has appropriate authority and support
- Resolve organizational blockers promptly

### Typical Communication
- Project kickoff and major decision reviews
- Milestone and outcome updates from the Project Manager
- Escalations and strategic trade-offs with the Product Manager

### Interaction with Existing Roles
- Align with the Product Manager on expected customer and business outcomes; the Product Manager continues to own product vision and backlog prioritization.
- Partner with the Project Manager on organizational support and escalations; the Project Manager continues to coordinate day-to-day delivery, plans, risks, and reporting.
- Support Developers and other delivery contributors by resolving organizational blockers rather than directing implementation details.

---

## Business Analysts

### Role Summary
Business Analysts turn stakeholder needs and business processes into clear, traceable requirements that the project team can evaluate and deliver.

### Responsibilities
- Elicit, analyze, and document stakeholder needs and workflows
- Identify assumptions, constraints, and gaps in requirements
- Trace requirements to proposed solutions and acceptance criteria
- Facilitate clarification when requirements or scope are ambiguous

### Goals
- Build a shared understanding of the problem and intended outcomes
- Reduce avoidable rework caused by unclear or incomplete requirements
- Keep requirements and decisions traceable

### Typical Communication
- Requirements and process documentation
- Workshops and clarification sessions with stakeholders and the Product Manager
- Requirement and acceptance-criteria reviews with Developers

### Interaction with Existing Roles
- Work with the Product Manager to clarify user and business needs; the Product Manager retains ownership of product direction and priority decisions.
- Coordinate with the Project Manager to surface scope, dependency, and timing impacts; the Project Manager manages the plan and project-level decisions.
- Clarify requirements with Developers, who estimate and implement the work and identify technical constraints.

---

## Technical Leads / Architects

### Role Summary
Technical Leads / Architects guide the technical approach and help the team make consistent, maintainable decisions that meet project requirements.

### Responsibilities
- Guide architecture, design choices, and technical standards
- Identify technical dependencies, constraints, and non-functional requirements
- Support estimates and evaluate technical risks and trade-offs
- Record significant technical decisions and guide implementation quality

### Goals
- Deliver a secure, reliable, and maintainable technical solution
- Make technical trade-offs visible and understandable
- Reduce integration and architectural risk

### Typical Communication
- Technical designs and decision records
- Design reviews and implementation discussions with Developers
- Dependency, estimate, and risk updates with the Project Manager

### Interaction with Existing Roles
- Guide and coordinate Developers without replacing their responsibility to implement, test, and review components.
- Consult the Product Manager when technical trade-offs affect customer value, scope, or prioritization.
- Inform the Project Manager of technical estimates, dependencies, and risks so they can be reflected in the plan and status reporting.

---

## QA / Test Leads

### Role Summary
QA / Test Leads coordinate the approach to verification and provide evidence about product quality and release readiness.

### Responsibilities
- Define test strategy, coverage, and quality checks for the project
- Coordinate test execution, defect triage, and reporting
- Identify quality risks and gaps in testability or acceptance criteria
- Summarize verification results and unresolved issues for readiness decisions

### Goals
- Find defects and quality risks early
- Provide clear evidence against agreed acceptance criteria
- Make quality and release risks visible to decision-makers

### Typical Communication
- Test plans, results, and defect reports
- Verification and triage discussions with Developers
- Quality and readiness updates with the Product Manager and Project Manager

### Interaction with Existing Roles
- Work with Developers to plan and execute tests; Developers remain responsible for testing their work and addressing defects.
- Confirm expected outcomes and acceptance criteria with the Product Manager, who retains product acceptance and prioritization decisions.
- Report quality risks and readiness evidence to the Project Manager for project tracking and coordination.

---

## Security / Privacy Leads

### Role Summary
Security / Privacy Leads advise the project on security and privacy requirements, risks, and controls, and coordinate specialist review when needed.

### Responsibilities
- Identify applicable security and privacy requirements early
- Review designs and data handling for risks and required controls
- Recommend mitigations and coordinate reviews or approvals required by organizational policy
- Track unresolved security and privacy risks and communicate their impact

### Goals
- Protect users, data, and systems
- Address security and privacy risks before release
- Make required controls and approval paths clear to the team

### Typical Communication
- Security and privacy requirements and review findings
- Design and remediation discussions with the Technical Lead and Developers
- Risk and approval updates with the Project Manager and relevant decision-makers

### Interaction with Existing Roles
- Work with the Technical Lead and Developers to incorporate controls into the design and implementation.
- Advise the Product Manager when security or privacy constraints affect features, data use, or product trade-offs.
- Coordinate with the Project Manager to track risks, dependencies, and required reviews; approval authority follows applicable organizational policy.

---

## Operations / Release Leads

### Role Summary
Operations / Release Leads coordinate deployment and operational readiness so the delivered solution can be supported and monitored.

### Responsibilities
- Plan release steps, deployment dependencies, and rollback approaches
- Confirm monitoring, support, and operational documentation needs
- Coordinate readiness checks and release communications
- Identify operational risks and report incidents or release issues through agreed channels

### Goals
- Enable predictable, low-risk releases
- Ensure services can be monitored and supported after deployment
- Reduce disruption through clear readiness and rollback plans

### Typical Communication
- Release plans, runbooks, and readiness checklists
- Deployment and operational handoffs with Developers and the Technical Lead
- Milestone and readiness updates with the Project Manager

### Interaction with Existing Roles
- Coordinate with Developers and the Technical Lead on deployment requirements, monitoring, and rollback; Developers remain responsible for the software changes they deliver.
- Consult the Product Manager on customer impact and release timing where product priorities are affected.
- Work with the Project Manager to align release dependencies and milestones with the project plan and communicate readiness or risks.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

