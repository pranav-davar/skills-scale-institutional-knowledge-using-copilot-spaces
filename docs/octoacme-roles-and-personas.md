# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.
The personas below describe areas of accountability, not a required staffing model: projects should use the roles that fit their needs, and one person may cover multiple roles when ownership remains clear.

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
- Weekly alignment with the Project Manager and engineering leads
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

## Technical Lead / Architect

### Role Summary
The Technical Lead / Architect guides technical direction and makes or coordinates architecture decisions. The role is accountable for making technical trade-offs and risks visible, while implementation remains a shared responsibility of the development team.

### Responsibilities
- Establish and communicate architecture, technical standards, and design constraints
- Facilitate technical design and review decisions, involving Developers and affected teams
- Identify technical risks, dependencies, and trade-offs; propose mitigations
- Support Developers with complex implementation decisions and keep technical documentation current

### Goals
- Keep the solution secure, maintainable, and fit for its intended scale
- Make technical decisions timely, understood, and traceable
- Balance near-term delivery with long-term sustainability

### Typical Communication
- Architecture notes, design reviews, and decision records
- Technical risk and dependency updates in planning
- Pairing and implementation discussions with Developers

### Interactions and Boundaries
- **Developers:** Establishes direction and constraints with them; Developers contribute design options, own implementation details, and surface feasibility concerns. The lead does not replace code review or shared engineering responsibility.
- **Product Managers:** Explains technical options, costs, and consequences so product priorities and scope can be decided with informed trade-offs; the Product Manager owns product outcomes and prioritization.
- **Project Managers:** Shares technical risks, estimates, dependencies, and decision timing for plans and status; the Project Manager coordinates the plan and escalations rather than making technical design decisions.

---

## Quality Engineer / Test Lead

### Role Summary
The Quality Engineer / Test Lead helps the team build confidence that the product meets its requirements and is ready to release. Quality is a team responsibility; this role provides quality strategy and evidence rather than serving as the sole owner of product quality.

### Responsibilities
- Define a risk-based test strategy, including appropriate automated and exploratory testing
- Work with the team to make acceptance criteria measurable and testable
- Identify coverage gaps, quality risks, and defects; coordinate their visibility and follow-up
- Summarize test results and outstanding risks to inform release-readiness decisions

### Goals
- Detect important problems early and reduce preventable regressions
- Make quality status and release risks clear
- Ensure validation reflects user needs and acceptance criteria

### Typical Communication
- Test plans, coverage reports, and defect tracking
- Testability discussions during refinement and design
- Release-readiness summaries and quality-risk updates

### Interactions and Boundaries
- **Developers:** Collaborates on test design, automation, and investigation; Developers remain responsible for testing their changes and addressing defects.
- **Product Managers:** Aligns validation with user outcomes and acceptance criteria; the Product Manager decides product scope and acceptable trade-offs, informed by quality risks.
- **Project Managers:** Communicates test progress, blockers, and readiness evidence for delivery coordination; the Project Manager tracks schedule and escalations. Any release gate or acceptance authority follows the project's agreed governance, not this role by default.

---

## UX / Accessibility Designer

### Role Summary
The UX / Accessibility Designer shapes user flows and interaction patterns so the product is understandable, usable, and accessible. The role brings user-centered design expertise into product and engineering decisions.

### Responsibilities
- Research user needs and design clear, inclusive user journeys and interactions
- Create and maintain design artifacts, prototypes, and accessibility requirements
- Review designs and implementations for usability and accessibility concerns
- Identify design dependencies and collaborate on validation with users or the team

### Goals
- Help users complete their tasks effectively
- Make accessibility part of design and delivery, not a late-stage check
- Keep shipped experiences aligned with user needs and product intent

### Typical Communication
- User research findings, journey maps, and prototypes
- Design reviews and accessibility guidance
- Usability findings and design handoff notes

### Interactions and Boundaries
- **Developers:** Provides interaction guidance and accessibility considerations, and reviews implementation with them; Developers own implementation choices and raise technical constraints or alternatives.
- **Product Managers:** Connects user research and design options to product outcomes; the Product Manager owns product strategy, prioritization, and scope.
- **Project Managers:** Shares design milestones, research needs, and dependencies for planning; the Project Manager coordinates schedules and cross-team handoffs, not design decisions.

---

## DevOps / Site Reliability Engineer

### Role Summary
The DevOps / Site Reliability Engineer helps teams deliver and operate software reliably. The role focuses on deployment practices and operational readiness, collaborating with product and engineering rather than acting as a final handoff point after development.

### Responsibilities
- Improve delivery pipelines, deployment practices, and infrastructure automation
- Define or apply observability, reliability, and incident-response practices
- Identify operational risks, capacity needs, and production dependencies
- Support release planning and operational readiness, including rollback and support considerations

### Goals
- Make releases repeatable and safe
- Ensure services can be observed, supported, and recovered
- Balance service reliability with delivery needs using visible operational risks

### Typical Communication
- Deployment and operational-readiness checklists
- Reliability, incident, and service-health reporting
- Infrastructure and production-readiness reviews

### Interactions and Boundaries
- **Developers:** Partners on build pipelines, deployment, observability, and production issues; Developers remain responsible for designing operable software and supporting the services they change.
- **Product Managers:** Explains reliability and operational trade-offs that affect user outcomes; the Product Manager prioritizes product value with those risks made explicit.
- **Project Managers:** Shares environment, release, and operational dependencies for the plan; the Project Manager coordinates dates and stakeholders, while operational decisions remain with the accountable technical owners.

---

## Scrum Master / Delivery Facilitator (where applicable)

### Role Summary
The Scrum Master / Delivery Facilitator helps a team improve its delivery process by facilitating agreed ways of working and helping remove workflow impediments. This role is applicable when the team benefits from dedicated facilitation; it does not automatically replace the Project Manager.

### Responsibilities
- Facilitate team ceremonies and support effective participation
- Help the team identify and address workflow impediments
- Encourage continuous improvement and make process changes visible
- Surface delivery-process concerns to the appropriate owners

### Goals
- Help the team collaborate effectively and improve its flow of work
- Make impediments actionable and prevent recurring process friction
- Support sustainable team practices without obscuring delivery accountability

### Typical Communication
- Ceremony facilitation and team working agreements
- Impediment tracking and process-improvement discussions
- Coordination with the Project Manager on delivery friction

### Interactions and Boundaries
- **Developers:** Facilitates team collaboration and helps resolve process impediments; Developers remain accountable for their work and technical decisions.
- **Product Managers:** Helps the team engage in backlog refinement and planning; the Product Manager owns product priorities and acceptance of product outcomes.
- **Project Managers:** Coordinates on delivery impediments, dependencies, and team-facing communication. The Project Manager retains ownership of project scope, schedule, risks, resources, and stakeholder status; facilitation responsibilities can be shared by agreement without transferring those accountabilities.

---

## Selecting and combining personas

These personas are options, not mandatory positions for every project. Choose explicit owners for the responsibilities that matter to the project's risk, scale, and delivery model. On a smaller team, one person may cover multiple personas—for example, a Developer may lead technical direction, or a Project Manager may facilitate team ceremonies—provided the team knows which decisions that person owns and where they need input or approval.

Combining roles does not remove the underlying accountability. Make ownership, decision boundaries, handoffs, and escalation paths clear in the project plan or working agreements. This helps teams avoid gaps and duplicated work, surface risks earlier, coordinate product, design, engineering, quality, and operations, and assess release readiness with the right evidence. Explicit ownership supports clearer communication, fewer delivery surprises, and better project outcomes.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
