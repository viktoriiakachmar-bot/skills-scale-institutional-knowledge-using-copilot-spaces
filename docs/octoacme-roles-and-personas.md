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

## Technical Leads / Engineering Leads

### Role Summary
Technical Leads guide engineering design and implementation across a project. They help the team make sound technical decisions while Developers retain responsibility for building, testing, and maintaining their work.

### Responsibilities
- Facilitate technical design and document significant decisions
- Coordinate implementation across components and identify technical dependencies
- Advise on estimates, sequencing, and technical feasibility
- Surface technical risks and recommend mitigations
- Support engineering quality through design and code reviews

### Goals
- Enable a coherent, maintainable technical solution
- Resolve technical questions early and reduce integration risk
- Help the team make informed implementation trade-offs

### Typical Communication
- Technical design discussions and decision records
- Engineering planning and dependency reviews
- Design/code review feedback and risk updates

### Interaction with Existing Roles
- **Developers:** Provide technical direction and context, coordinate interfaces, and invite implementation feedback; Developers own the code and raise concerns or alternatives.
- **Product Managers:** Explain feasibility, effort, and technical trade-offs so the Product Manager can make priority and scope decisions.
- **Project Managers:** Share estimates, dependencies, and risks to support sequencing and delivery planning; the Project Manager remains responsible for the integrated plan and status reporting.

---

## Quality Engineers / QA Leads

### Role Summary
Quality Engineers or QA Leads coordinate the project's quality approach and provide evidence about whether a change meets agreed expectations. They partner with the team on quality rather than replacing Developers' responsibility to test their work.

### Responsibilities
- Define test strategy and identify appropriate functional, integration, and regression coverage
- Coordinate test planning, execution, and defect triage
- Make quality risks and release-readiness evidence visible
- Recommend improvements to prevent recurring defects

### Goals
- Detect important issues early and reduce escaped defects
- Ensure quality criteria are understood and verifiable
- Give stakeholders clear evidence for release-readiness decisions

### Typical Communication
- Test plans, quality dashboards, and defect reports
- Test and acceptance discussions with the delivery team
- Readiness updates and escalations for unresolved quality risks

### Interaction with Existing Roles
- **Developers:** Agree on test coverage, share reproducible defects, and coordinate fixes and retesting; Developers maintain tests and address defects in their components.
- **Product Managers:** Clarify acceptance criteria and expected user behavior, and raise quality findings that may affect scope or customer value.
- **Project Managers:** Provide quality status, blockers, and readiness evidence for delivery tracking; the Project Manager coordinates schedule impacts and stakeholder communications, not the quality judgment itself.

---

## UX Designers / User Researchers

### Role Summary
UX Designers and User Researchers investigate user needs and shape usable, accessible experiences. They inform product decisions with research and design, while the Product Manager remains accountable for product priorities.

### Responsibilities
- Plan and conduct user research or usability evaluation
- Create and validate user flows, interaction designs, and prototypes
- Identify accessibility and usability considerations
- Communicate research findings and design rationale

### Goals
- Ensure solutions address real user needs
- Improve usability and accessibility
- Reduce uncertainty through timely research and validation

### Typical Communication
- Research plans, findings, and design walkthroughs
- Prototypes and design specifications
- Usability feedback shared with product and engineering teams

### Interaction with Existing Roles
- **Developers:** Explain design intent and constraints, review implementation, and work through feasible alternatives with engineering.
- **Product Managers:** Connect research findings to problem statements, priorities, and success measures; the Product Manager decides roadmap and backlog priorities.
- **Project Managers:** Share research and design dependencies, review dates, and risks so they can be reflected in the plan and communicated to stakeholders.

---

## Business Sponsors / Key Stakeholders

### Role Summary
A Business Sponsor represents the business outcomes and organizational commitment behind a project. Key Stakeholders contribute domain knowledge, constraints, or affected-user perspectives. These participants provide input and timely decisions within their authority; they do not replace the Product Manager's ownership of product priorities or the Project Manager's ownership of delivery coordination.

### Responsibilities
- Clarify desired business outcomes, constraints, and measures of success
- Identify decision-makers and provide timely decisions on business trade-offs within their authority
- Help secure organizational support and surface cross-team concerns
- Review progress and escalate unresolved decisions or material changes in business context

### Goals
- Achieve the intended business outcomes
- Keep decisions aligned with organizational priorities and constraints
- Ensure relevant stakeholder perspectives are heard without delaying delivery

### Typical Communication
- Project kickoff and milestone or status reviews
- Decision requests, escalations, and business outcome updates
- Stakeholder feedback and approval discussions where required

### Interaction with Existing Roles
- **Developers:** Provide business context when needed; rely on the Product Manager and team to translate needs into prioritized, actionable requirements rather than directing implementation details.
- **Product Managers:** Align on customer and business value, constraints, and outcome measures; the Product Manager retains responsibility for product vision and backlog prioritization.
- **Project Managers:** Agree on governance, decision paths, and escalation expectations; respond to decision requests and receive coordinated status updates, while the Project Manager maintains the delivery plan and communications.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
