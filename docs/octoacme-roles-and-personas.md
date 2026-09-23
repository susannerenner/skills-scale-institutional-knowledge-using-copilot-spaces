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

## QA/Testing

### Role Summary
QA/Testing contributors validate that the solution meets acceptance criteria, quality expectations, and release readiness standards. They help teams prevent defects early and verify quality before launch.

### Responsibilities
- Define and execute test approaches for planned work
- Validate acceptance criteria, regression coverage, and defect fixes
- Partner with Developers on testability and automation opportunities
- Raise quality risks, release concerns, and unresolved defects
- Confirm readiness for releases, demos, and handoffs

### Goals
- Reduce escaped defects and rework
- Improve confidence in delivery quality and release readiness
- Ensure quality expectations are visible throughout the lifecycle

### Typical Communication
- Test plans, defect reports, and release-readiness reviews
- Daily coordination with Developers and Project Managers
- Acceptance feedback with Product Managers and stakeholders

---

## Stakeholders

### Role Summary
Stakeholders provide business, customer, operational, or leadership input that shapes scope, priorities, constraints, and approvals. They help ensure the work stays aligned to broader organizational needs.

### Responsibilities
- Provide context, constraints, and feedback for planning and execution
- Review milestones, demos, and major decisions
- Approve scope, timing, funding, or rollout decisions when required
- Escalate concerns when delivery outcomes no longer match expectations
- Support adoption, communication, and cross-team alignment

### Goals
- Ensure delivery outcomes align with business and customer needs
- Make timely decisions that unblock the team
- Reduce ambiguity around approvals and priority trade-offs

### Typical Communication
- Kickoff meetings, milestone reviews, and stakeholder updates
- Decision logs, approval requests, and escalation discussions
- Demo feedback and readiness sign-offs

---

## UX/Product Designer or Researcher

### Role Summary
UX/Product Designers or Researchers represent user needs, journeys, accessibility considerations, and usability validation. They turn product goals into experience definitions that delivery teams can build and test.

### Responsibilities
- Define user journeys, flows, wireframes, prototypes, or research plans
- Validate assumptions through discovery, testing, or design reviews
- Clarify usability, accessibility, and content requirements
- Identify experience risks, unmet user needs, and research findings early
- Prepare design assets and recommendations for build and release planning

### Goals
- Ensure the delivered solution is useful, usable, and accessible
- Reduce rework caused by unclear or unvalidated experience requirements
- Keep customer needs visible from discovery through release

### Typical Communication
- Discovery sessions, design reviews, and prototype walkthroughs
- Research readouts, design specifications, and acceptance clarifications
- Ongoing check-ins with product, engineering, and QA partners

### Interactions with Core Delivery Personas
- Developers: align on feasibility, implementation details, and handoffs from designs into build-ready work.
- Product Managers: refine outcomes, acceptance criteria, and research priorities before and during delivery.
- Project Managers: coordinate design milestones, dependencies, and escalation when design decisions threaten schedule or scope.
- QA/Testing: define usability and accessibility checks and review whether the delivered experience matches intent.
- Stakeholders: share research findings and design trade-offs to support approval and expectation-setting.

---

## Technical Lead or Architect

### Role Summary
Technical Leads or Architects guide solution design, technical standards, non-functional requirements, and engineering trade-offs. They help the team make sound implementation decisions while managing technical risk.

### Responsibilities
- Define and review architecture, interfaces, and implementation patterns
- Clarify non-functional requirements such as scalability, reliability, and maintainability
- Identify technical dependencies, constraints, and risks early
- Support estimation, sequencing, and technical decision-making during delivery
- Escalate architecture or capacity issues that could jeopardize outcomes

### Goals
- Keep the technical approach aligned with product goals and operational constraints
- Reduce technical risk, rework, and avoidable complexity
- Improve decision quality for design, delivery, and supportability

### Typical Communication
- Architecture reviews, technical design docs, and engineering syncs
- Trade-off discussions with product and delivery leads
- Risk reviews tied to milestones, dependencies, and release readiness

### Interactions with Core Delivery Personas
- Developers: guide implementation patterns, reviews, and technical handoffs from design into delivery.
- Product Managers: explain trade-offs, sequencing options, and technical implications of product priorities.
- Project Managers: surface dependency, estimation, and risk impacts that affect plans or escalations.
- QA/Testing: align on test strategy for non-functional requirements and defect triage priorities.
- Stakeholders: translate major technical risks or architecture decisions when approval or escalation is needed.

---

## Release/DevOps or Platform Engineer

### Role Summary
Release/DevOps or Platform Engineers enable build, deployment, environment, observability, and rollback readiness. They help the team deliver safely and consistently from development through production.

### Responsibilities
- Maintain CI/CD workflows, environments, and release automation
- Prepare deployment, monitoring, rollback, and operational readiness steps
- Identify environment constraints, release risks, and platform dependencies
- Support incident response, hotfixes, and production verification when needed
- Coordinate release windows, change controls, and operational handoffs

### Goals
- Improve deployment safety, speed, and repeatability
- Reduce release risk and environment-related delays
- Ensure production readiness and recovery options are clear

### Typical Communication
- Release plans, deployment checklists, and environment status updates
- Incident reviews, observability updates, and readiness checkpoints
- Coordination with delivery, support, and stakeholder groups before release

### Interactions with Core Delivery Personas
- Developers: align on build pipelines, environment needs, telemetry, and release handoffs.
- Product Managers: confirm release constraints, launch timing, and customer-impacting trade-offs.
- Project Managers: plan release milestones, dependencies, and escalations related to environment readiness.
- QA/Testing: coordinate test environments, smoke testing, and release validation before launch.
- Stakeholders: communicate release readiness, rollout risk, and incident status when business visibility is required.

---

## Security and Privacy Partner

### Role Summary
Security and Privacy Partners advise on threat modeling, security controls, privacy requirements, and incident readiness. They help teams address risk early enough to avoid late-stage surprises and non-compliance.

### Responsibilities
- Identify security and privacy requirements during planning and design
- Review solution changes for threats, data handling, and control gaps
- Recommend mitigations, validation steps, and incident escalation triggers
- Support compliance, approval, or exception workflows when required
- Reassess risk before release and after major changes or incidents

### Goals
- Reduce security and privacy risk in delivered solutions
- Ensure required controls and review points are not missed
- Make escalation paths clear when risk exceeds team authority

### Typical Communication
- Threat-model reviews, security sign-offs, and privacy checklists
- Risk discussions with product, engineering, and project leads
- Incident or exception escalations involving delivery and leadership

### Interactions with Core Delivery Personas
- Developers: review implementation approaches, controls, and remediation work for identified risks.
- Product Managers: clarify data use, compliance expectations, and acceptable risk trade-offs.
- Project Managers: plan required reviews, approvals, and escalations that affect scope or timeline.
- QA/Testing: define security or privacy validation needs and review unresolved defects before release.
- Stakeholders: escalate high-severity risks, required approvals, or incident impacts that need business decisions.

---

## Data/Analytics Partner

### Role Summary
Data/Analytics Partners define instrumentation, reporting, and measurement approaches that show whether project outcomes were achieved. They connect delivery work to evidence, adoption, and continuous improvement.

### Responsibilities
- Define success metrics, events, dashboards, and reporting needs
- Partner on telemetry requirements and data quality expectations
- Validate that measurement plans are feasible before delivery begins
- Analyze adoption, performance, or experiment outcomes after release
- Surface insights that influence prioritization, rollout, or follow-up work

### Goals
- Ensure teams can measure outcomes instead of relying on assumptions
- Improve visibility into adoption, quality, and business impact
- Reduce delays caused by missing or unreliable telemetry

### Typical Communication
- Metric definitions, instrumentation plans, and dashboard reviews
- Readouts on adoption, performance, or experiment results
- Ongoing coordination with product, engineering, and delivery leads

### Interactions with Core Delivery Personas
- Developers: define telemetry implementation details, data contracts, and validation handoffs.
- Product Managers: align on success metrics, hypotheses, and post-release learning goals.
- Project Managers: incorporate analytics milestones, dependencies, and reporting needs into the plan.
- QA/Testing: verify telemetry accuracy and data completeness before release decisions are made.
- Stakeholders: share measured outcomes and insights that inform approvals, funding, or next steps.

---

## Customer Support or Operations Representative

### Role Summary
Customer Support or Operations Representatives bring frontline knowledge about customer pain points, readiness needs, support impacts, and operational constraints. They help the team plan for adoption, continuity, and issue response.

### Responsibilities
- Share recurring customer issues, operational requirements, and support considerations
- Prepare support documentation, runbooks, training, or readiness materials
- Identify rollout, communication, or service-impact risks before release
- Coordinate issue triage, escalation, and feedback loops after launch
- Represent operational lessons learned in retrospectives and follow-up planning

### Goals
- Reduce customer disruption during rollout and change adoption
- Improve support readiness and incident response coordination
- Ensure operational realities influence project decisions early

### Typical Communication
- Readiness reviews, support enablement sessions, and incident handoffs
- Customer-feedback summaries and operational risk updates
- Coordination with release, delivery, and stakeholder groups around launch

### Interactions with Core Delivery Personas
- Developers: provide production feedback, support patterns, and issue details that affect fixes or enhancements.
- Product Managers: share customer needs, adoption barriers, and support insights that influence priorities.
- Project Managers: coordinate communications, readiness tasks, and escalations tied to rollout or service impact.
- QA/Testing: contribute real-world scenarios, defect symptoms, and validation needs seen in operations.
- Stakeholders: communicate adoption risks, support readiness, and incident impacts that may need business action.

---

## Business Sponsor or Executive Stakeholder

### Role Summary
Business Sponsors or Executive Stakeholders provide strategic direction, funding support, priority decisions, and senior-level escalation help. They ensure projects remain aligned to organizational goals and receive timely decisions at key checkpoints.

### Responsibilities
- Set strategic objectives, guardrails, and success expectations
- Approve major priority, funding, scope, or timeline changes when needed
- Remove organizational blockers that the delivery team cannot resolve alone
- Review major risks, milestone outcomes, and launch readiness at decision gates
- Sponsor adoption and organizational communication for high-visibility work

### Goals
- Keep work aligned to business strategy and investment priorities
- Speed up decisions on material trade-offs and escalations
- Improve accountability for business outcomes after delivery

### Typical Communication
- Steering reviews, milestone checkpoints, and escalation discussions
- Strategic updates from product and project leads
- Go/no-go decisions for business-critical releases or changes

### Interactions with Core Delivery Personas
- Developers: engage indirectly through major risk, feasibility, or capacity escalations that affect commitments.
- Product Managers: align on strategic outcomes, trade-offs, and value realization at decision points.
- Project Managers: review status, risks, dependencies, and escalations that require sponsor action.
- QA/Testing: rely on release-quality signals and unresolved defect risk when approving major milestones or launches.
- Stakeholders: align cross-functional leaders around priorities, approvals, and organizational communication.

---

## Working model across the lifecycle

### Participation by phase
- Initiation: Product Managers, Project Managers, Stakeholders, UX/Product Designers or Researchers, Technical Leads or Architects, and Business Sponsors align on the problem, desired outcomes, constraints, and early risks.
- Planning: Developers, QA/Testing, Release/DevOps or Platform Engineers, Security and Privacy Partners, and Data/Analytics Partners help turn scope into a workable plan with clear dependencies, review points, and success measures.
- Execution: Developers, QA/Testing, UX/Product Designers or Researchers, Technical Leads or Architects, and Product Managers refine, build, test, and adjust based on risk or learning.
- Release: Release/DevOps or Platform Engineers, QA/Testing, Customer Support or Operations Representatives, Security and Privacy Partners, Project Managers, and Stakeholders coordinate release readiness, approvals, communications, and rollback planning.
- Retrospective and follow-up: Project Managers, Product Managers, Developers, QA/Testing, Data/Analytics Partners, Customer Support or Operations Representatives, and Stakeholders review outcomes, issues, and next actions.

### Decision rights and escalation
- Product Managers own product priority, scope intent, and acceptance decisions.
- Project Managers own delivery coordination, status transparency, and escalation routing.
- Developers and Technical Leads or Architects own implementation choices within agreed product, security, and platform guardrails.
- QA/Testing, Security and Privacy Partners, and Release/DevOps or Platform Engineers can escalate release concerns when quality, control, or operational readiness is at risk.
- Stakeholders and Business Sponsors resolve trade-offs that affect budget, timeline, organizational priorities, or risk tolerance beyond the team's authority.

### Handoffs
- Product requirements, designs, and research findings should be handed to Developers and QA/Testing with clear acceptance criteria and unresolved assumptions documented.
- Technical design decisions, environment needs, security controls, and telemetry requirements should be handed across delivery roles before implementation is considered ready.
- Release plans, readiness checks, support documentation, and rollback steps should be handed to operations-facing roles before launch.
- Outcome reporting, customer feedback, and incident learnings should be handed back to Product Managers, Project Managers, and Stakeholders for follow-up decisions.

### Smaller-team guidance
- On smaller teams, one person may cover multiple roles such as Product Manager plus UX/Product Designer or Researcher, Developer plus Technical Lead or Architect, or Release/DevOps plus Customer Support or Operations.
- When roles are combined, teams should still make the responsibilities, review points, and escalation paths explicit so approvals, quality checks, and risk decisions do not disappear.
- If no dedicated Security and Privacy Partner, Data/Analytics Partner, or QA/Testing contributor is assigned, the team should name who is accountable for those decisions before execution begins.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
