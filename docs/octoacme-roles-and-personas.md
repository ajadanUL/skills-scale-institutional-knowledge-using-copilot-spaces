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

## Engineering Managers

### Role Summary
Engineering Managers are accountable for team capacity, delivery health, and technical execution readiness. They support developers through coaching and staffing decisions while partnering with product and project leads on scope, sequencing, and risk.

### Responsibilities
- Plan engineering capacity and staffing for active and upcoming work
- Coach developers and support sustainable delivery practices
- Surface technical delivery risks, dependencies, and execution constraints
- Align implementation plans with architecture, quality, and maintainability expectations
- Support escalation and resolution when delivery issues affect commitments

### Goals
- Keep engineering work achievable, sustainable, and aligned with commitments
- Improve team effectiveness, execution predictability, and code quality
- Reduce delivery risk caused by staffing gaps, unclear ownership, or overloaded teams

### Typical Communication
- Capacity and staffing discussions with Project Managers and Product Managers
- Delivery risk reviews with developers and project leads
- Regular coaching conversations, planning sessions, and escalation check-ins

### Role Interactions
- Works with **Project Managers** to confirm schedule feasibility, identify staffing constraints, and assign accountable engineering owners for delivery risks.
- Partners with **Product Managers** on trade-offs when team capacity or technical complexity affects scope, sequencing, or release timing.
- Supports **Developers** with technical direction, workload balancing, and escalation paths, while leaving day-to-day implementation ownership with the assigned engineers.
- Provides **Stakeholders** with transparent updates on engineering capacity and delivery risk through the Project Manager rather than owning business prioritization directly.
- Coordinates with **QA/Testing** contributors when resourcing, test coverage, or release-readiness risks require additional engineering support.

---

## UX/UI Designers

### Role Summary
UX/UI Designers are accountable for user experience quality, interaction design, and design clarity before implementation begins. They translate user needs into flows, wireframes, and interface decisions while collaborating closely with product and engineering.

### Responsibilities
- Define user flows, wireframes, and interface behaviors for planned work
- Document usability expectations and design acceptance criteria
- Validate that proposed solutions solve the right user problem with minimal friction
- Partner with engineering to resolve design constraints during implementation
- Help identify UX risks, accessibility concerns, and adoption blockers early

### Goals
- Deliver intuitive, accessible, and consistent user experiences
- Reduce ambiguity in feature requirements and acceptance expectations
- Catch usability issues before release through early collaboration and validation

### Typical Communication
- Design reviews and requirement clarification sessions
- Annotated mocks, prototypes, and acceptance notes
- Feedback loops with product, engineering, QA, and stakeholder groups

### Role Interactions
- Collaborates with **Product Managers** to refine requirements, confirm user outcomes, and separate design decisions from broader product-priority decisions.
- Works with **Project Managers** to sequence design dependencies early enough to avoid blocking development and to communicate UX-related risks to timelines.
- Partners with **Developers** on implementation details, edge cases, and feasibility while keeping design intent and interaction quality explicit.
- Supports **Stakeholders** by translating user-facing changes into clear visuals and rationale, but does not replace product ownership of final prioritization.
- Coordinates with **QA/Testing** contributors on usability checks, accessibility validation, and interpretation of design acceptance criteria during test execution.

---

## DevOps / Platform Engineers

### Role Summary
DevOps / Platform Engineers are accountable for the reliability of delivery pipelines, deployment guardrails, and operational readiness. They enable safe, repeatable releases and provide the infrastructure patterns that teams depend on during execution and launch.

### Responsibilities
- Maintain CI/CD workflows, deployment automation, and environment reliability
- Define observability baselines, rollback expectations, and release guardrails
- Partner with development teams on build, release, and runtime requirements
- Surface infrastructure risks, operational dependencies, and platform constraints
- Support incident response readiness and post-release stabilization needs

### Goals
- Keep deployments safe, predictable, and easy to recover
- Reduce operational friction for developers and release teams
- Improve visibility into system health before and after releases

### Typical Communication
- Release-readiness reviews and deployment planning sessions
- CI/CD updates, runbook notes, and incident follow-up communication
- Cross-functional coordination on environments, access, and operational dependencies

### Role Interactions
- Works with **Project Managers** to align release windows, environment readiness, and rollback planning with milestone commitments.
- Partners with **Product Managers** when platform constraints or release guardrails affect launch timing, but does not own feature prioritization decisions.
- Supports **Developers** with pipeline reliability, deployment patterns, and operational tooling while developers retain ownership of application changes.
- Helps **Stakeholders** understand operational readiness, incident status, and deployment constraints through structured release communications.
- Collaborates with **QA/Testing** contributors to ensure test environments, smoke checks, and release validation steps are available and reliable.

---

## Security Leads

### Role Summary
Security Leads are accountable for identifying security risks, defining security requirements, and guiding remediation priorities for the project. They help teams make informed risk decisions without taking over day-to-day feature delivery ownership.

### Responsibilities
- Review features and releases for security risks and threat scenarios
- Define security requirements, controls, and escalation expectations
- Coordinate security testing guidance and remediation follow-up
- Advise on compliance, data protection, and incident-response considerations
- Track high-impact risks that require explicit business or technical decisions

### Goals
- Reduce the likelihood and impact of security incidents
- Build security expectations into planning and delivery instead of adding them late
- Ensure risks are visible, prioritized, and assigned to clear owners

### Typical Communication
- Risk reviews, security requirement notes, and remediation guidance
- Escalation paths for vulnerabilities, incidents, and exceptions
- Coordination with engineering, QA, and project leadership on security readiness

### Role Interactions
- Works with **Project Managers** to log security risks, escalation paths, and mitigation timelines within the overall project plan.
- Partners with **Product Managers** when security requirements affect scope, compliance priorities, or customer commitments, while keeping product ownership of value trade-offs intact.
- Guides **Developers** on secure implementation expectations, vulnerability remediation, and risk acceptance boundaries without replacing engineering ownership of the code changes.
- Provides **Stakeholders** with risk visibility and incident context appropriate for business decisions and escalation.
- Coordinates with **QA/Testing** contributors on security test coverage, validation evidence, and release-blocking findings when vulnerabilities are identified.

---

## Data Analysts

### Role Summary
Data Analysts are accountable for defining how project outcomes will be measured and for turning usage data into decision-ready insights. They support teams with instrumentation guidance, KPI reporting, and analysis of whether shipped work achieved the intended results.

### Responsibilities
- Define measurement plans, KPI definitions, and reporting expectations
- Partner on instrumentation requirements before development begins
- Analyze feature usage, experiments, and outcome trends after release
- Highlight data quality gaps and recommend follow-up actions
- Translate metrics into insights for planning, prioritization, and retrospectives

### Goals
- Ensure project decisions are informed by trustworthy and relevant data
- Make outcome measurement part of delivery rather than an afterthought
- Improve learning speed by connecting released work to observed impact

### Typical Communication
- KPI reviews, dashboards, and experiment readouts
- Instrumentation planning discussions with product and engineering
- Retrospective input on outcome trends, adoption, and follow-up questions

### Role Interactions
- Partners with **Product Managers** to define success metrics, experiment criteria, and how evidence will inform backlog decisions.
- Works with **Project Managers** to include measurement milestones, reporting expectations, and analysis checkpoints in project tracking.
- Supports **Developers** with telemetry requirements, event definitions, and data-quality follow-up while developers retain implementation ownership.
- Helps **Stakeholders** interpret outcome trends and adoption signals without owning final business decisions on roadmap direction.
- Coordinates with **QA/Testing** contributors when instrumentation or reporting needs verification as part of release readiness.

---

## Customer Support / Success Liaisons

### Role Summary
Customer Support / Success Liaisons are accountable for bringing customer impact, support trends, and rollout readiness into project decisions. They represent operational customer feedback and help the team prepare communications and adoption support before and after release.

### Responsibilities
- Collect and summarize customer pain points, adoption concerns, and support trends
- Provide rollout-readiness input for release communications and enablement
- Flag customer-impact risks, incident patterns, and follow-up needs
- Help close the loop between shipped work and customer feedback after release
- Coordinate internal readiness materials for support and success teams

### Goals
- Ensure customer-facing impacts are visible during planning and release decisions
- Reduce avoidable support friction during rollout and change management
- Improve customer trust through better expectation-setting and follow-through

### Typical Communication
- Customer feedback summaries and support trend reviews
- Release communication planning and enablement updates
- Post-release follow-up on incidents, adoption questions, and recurring issues

### Role Interactions
- Works with **Product Managers** to convert customer themes into backlog input while leaving product prioritization decisions with the Product Manager.
- Partners with **Project Managers** on release communications, rollout dependencies, and escalation of customer-impact risks that may affect timelines or readiness.
- Shares recurring pain points and incident context with **Developers** so implementation teams understand operational impact and can prioritize the right fixes.
- Collaborates directly with **Stakeholders** on adoption concerns, readiness messaging, and escalation themes from customers or internal users.
- Coordinates with **QA/Testing** contributors when customer-reported scenarios, regression risks, or release-readiness checks should be reflected in validation plans.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
