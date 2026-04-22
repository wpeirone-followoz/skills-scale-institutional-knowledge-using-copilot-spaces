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

### Key Interactions
- Partners with **QA Lead** to ensure features are testable and acceptance criteria are well-defined
- Coordinates with **DevOps Engineer** on CI/CD pipelines, deployment automation, and infrastructure needs
- Collaborates with **UX Designer** to implement designs accurately and raise feasibility concerns early
- Works with **Business Analyst** to clarify requirements and acceptance criteria

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

### Key Interactions
- Partners with **UX Designer** on user research, usability testing, and feature requirements
- Works with **Business Analyst** to validate that features align with business goals
- Coordinates with **QA Lead** on user acceptance testing and quality sign-off
- Engages **Sponsor/Stakeholder** for milestone approvals and strategic feedback

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

### Key Interactions
- Escalates blockers and risks to **Sponsor/Stakeholder** as needed
- Coordinates release readiness with **DevOps Engineer** and **QA Lead**
- Works with **Business Analyst** to ensure requirements and scope are well-defined
- Facilitates retrospectives with input from all roles

---

## UX Designer

### Role Summary
UX Designers create user experiences that are intuitive, accessible, and aligned with customer needs. They translate business requirements and user research into flows, wireframes, and interactive prototypes.

### Responsibilities
- Develop user flows, wireframes, and prototypes for new features
- Conduct or coordinate user research and usability testing
- Advocate for user needs throughout planning, design, and review cycles
- Maintain a consistent design system and visual standards
- Participate in sprint planning and feature reviews to provide design context

### Goals
- Ensure features meet usability and accessibility standards
- Reduce friction and rework by involving design early in the process
- Deliver a consistent, high-quality user experience across all product areas

### Typical Communication
- Design review sessions with Developers and Product Manager
- Usability testing summaries shared with the full team
- Design files and specs linked in backlog items and PRs

### Key Interactions
- Partners closely with **Product Manager** to translate requirements into user-centered designs
- Supports **Developers** during implementation; reviews built features against design specs
- Participates in sprint demos and retrospectives to gather usability feedback
- Engages **Business Analyst** to ensure business rules are reflected accurately in UI flows

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business goals and technical delivery. They gather and refine requirements, map processes, and validate that features align with organizational objectives.

### Responsibilities
- Elicit and document business requirements from stakeholders
- Create process maps, user stories, and detailed acceptance criteria
- Validate that completed features satisfy business objectives
- Identify and escalate scope gaps or conflicting requirements
- Support the Product Manager in backlog refinement and prioritization

### Goals
- Ensure requirements are clear, complete, and actionable before work begins
- Reduce rework by catching ambiguous or missing requirements early
- Maintain alignment between business strategy and delivery outcomes

### Typical Communication
- Requirement workshops and walkthroughs with stakeholders
- Acceptance criteria and process documentation shared in project backlog
- Regular check-ins with Project and Product Managers

### Key Interactions
- Works closely with **Project and Product Managers** for requirement gathering and backlog refinement
- Clarifies acceptance criteria for **Developers** and **QA Lead** to reduce ambiguity
- Engages **Sponsor/Stakeholder** to validate business requirements and priorities
- Supports **UX Designer** with business rule context needed for UI flows

---

## QA Lead

### Role Summary
QA Leads define and oversee the quality assurance strategy. They ensure that features meet defined quality standards before release, and that testing practices are embedded throughout the development lifecycle.

### Responsibilities
- Define and maintain the overall testing strategy (unit, integration, end-to-end, regression)
- Oversee test case creation, execution, and coverage tracking
- Coordinate user acceptance testing (UAT) with the Product Manager and stakeholders
- Report quality metrics and testing status to the Project Manager
- Coach Developers on writing testable code and defining clear acceptance criteria

### Goals
- Prevent defects from reaching production through structured test processes
- Maintain high test coverage and reliable regression suites
- Ensure release quality gates are consistently met

### Typical Communication
- Test summary reports after each sprint or release candidate
- Bug reports and quality metrics on the project board
- UAT sessions coordinated with the Product Manager

### Key Interactions
- Coaches **Developers** on testable features and coverage expectations
- Coordinates UAT with **Product Manager** to validate business and user acceptance criteria
- Reports quality metrics and release readiness to **Project Manager**
- Works with **DevOps Engineer** to integrate automated testing into CI/CD pipelines

---

## DevOps Engineer

### Role Summary
DevOps Engineers own the infrastructure and delivery automation that enables the team to ship reliably and safely. They build and maintain CI/CD pipelines, monitor system health, and manage deployment and rollback procedures.

### Responsibilities
- Design, build, and maintain CI/CD pipelines and deployment automation
- Monitor infrastructure, system health, and application observability
- Define and maintain rollback and disaster recovery plans
- Ensure environments (dev, staging, production) are consistent and reproducible
- Identify and mitigate release risks related to infrastructure and deployment

### Goals
- Enable fast, reliable, and low-risk deployments
- Maximize system uptime and observability
- Reduce toil through automation and repeatable processes

### Typical Communication
- Release readiness reports shared with Project Manager before deployments
- Infrastructure change notifications in team channels
- Incident updates and post-mortems following production issues

### Key Interactions
- Works with **Developers** on delivery automation, environment configuration, and infrastructure needs
- Informs **Project Manager** of release risks and deployment windows
- Partners with **QA Lead** to integrate automated tests into CI/CD pipelines
- Coordinates post-release monitoring and rollback decisions with the full team

---

## Sponsor / Stakeholder

### Role Summary
Sponsors and Stakeholders provide strategic direction, funding, and approvals for projects. They represent the business interests that a project must serve and are the primary escalation point for decisions beyond the team's authority.

### Responsibilities
- Define and communicate business goals and strategic priorities
- Approve project initiation, key milestones, and scope changes
- Allocate funding and resources required for project delivery
- Provide timely feedback and decisions to unblock the team
- Participate in retrospectives for significant releases or milestones when required

### Goals
- Ensure projects deliver measurable business value
- Maintain visibility into project status, risks, and decisions
- Enable the team by removing organizational blockers

### Typical Communication
- Monthly (or milestone-based) status reviews with the Project Manager
- Decision requests and escalations from the Project Manager or Product Manager
- Retrospective summaries after major milestones or incidents

### Key Interactions
- Engages with **Project and Product Managers** for status reviews, approvals, and escalations
- Works with **Business Analyst** to validate business requirements and priorities
- Participates in retrospectives and planning sessions when strategic input is needed

---

## Role Interaction Matrix

The table below summarizes primary interaction touchpoints between roles:

| | Developer | Product Manager | Project Manager | UX Designer | Business Analyst | QA Lead | DevOps Engineer | Sponsor/Stakeholder |
|---|---|---|---|---|---|---|---|---|
| **Developer** | — | Requirements & demos | Status & blockers | Design implementation | Acceptance criteria | Testability & coverage | CI/CD & environments | — |
| **Product Manager** | Feature specs & demos | — | Roadmap & risks | User research & design | Backlog refinement | UAT sign-off | Release readiness | Strategic approvals |
| **Project Manager** | Sprint planning | Roadmap alignment | — | Design timelines | Scope & requirements | Release quality | Deployment windows | Escalations & status |
| **UX Designer** | Design review | Feature requirements | Design timelines | — | Business rules in UI | Usability of test flows | — | — |
| **Business Analyst** | Acceptance criteria | Backlog refinement | Scope & requirements | Business rules in UI | — | Test criteria clarity | — | Business validation |
| **QA Lead** | Testability coaching | UAT coordination | Quality reports | Usability test flows | Test criteria | — | CI/CD test integration | — |
| **DevOps Engineer** | Environment support | Release readiness | Deployment windows | — | — | CI/CD test integration | — | — |
| **Sponsor/Stakeholder** | — | Strategic direction | Status & decisions | — | Business validation | — | — | — |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

