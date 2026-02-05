# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. It includes core delivery roles (Developers, Product Managers, Project Managers) as well as specialized roles (UX/UI Designer, QA Lead, DevOps/Platform Engineer) and key stakeholder personas to ensure clear accountability and smooth handoffs across the project lifecycle.

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

### Interactions
- **Product Managers**: Collaborate on requirements, acceptance criteria, and feature scope during planning and execution.
- **Project Managers**: Provide estimates, report progress, and escalate blockers during standups and status reviews.
- **UX/UI Designer**: Review design specs during planning; sync during implementation to ensure pixel-perfect delivery.
- **QA Lead**: Partner during development to define test scenarios; coordinate on bug fixes and regression testing.
- **DevOps/Platform Engineer**: Work together on CI/CD improvements, deployment automation, and infrastructure needs.
- **Stakeholders**: Participate in demos and answer technical questions during milestone reviews.

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

### Interactions
- **Developers**: Define feature requirements and acceptance criteria; validate delivered functionality in demos.
- **Project Managers**: Align on priorities, timelines, and scope; provide input on risk mitigation strategies.
- **UX/UI Designer**: Collaborate on user research insights; review and approve design deliverables before implementation.
- **QA Lead**: Review test plans and acceptance criteria; make go/no-go decisions based on quality metrics.
- **DevOps/Platform Engineer**: Discuss operational requirements, monitoring needs, and deployment strategies.
- **Stakeholders**: Gather input during initiation; provide updates at key milestones; seek approvals for scope changes.

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

### Interactions
- **Developers**: Facilitate planning, track progress, and remove blockers; coordinate cross-team dependencies.
- **Product Managers**: Align on roadmap priorities and timelines; escalate risks and resource constraints.
- **UX/UI Designer**: Ensure design deliverables are on schedule and integrated into the project plan.
- **QA Lead**: Track testing progress; coordinate release readiness reviews and sign-offs.
- **DevOps/Platform Engineer**: Coordinate deployment windows and release logistics; track infrastructure dependencies.
- **Stakeholders**: Provide regular status updates; facilitate decision-making and escalate issues requiring executive input.

---

---

## UX/UI Designer

### Role Summary
UX/UI Designers are responsible for the usability, accessibility, and visual design of user-facing features. They translate user needs and business requirements into intuitive, accessible experiences and work closely with Product Managers and Developers to ensure design fidelity from concept to delivery.

### Responsibilities
- Create user journeys, wireframes, and high-fidelity mockups
- Develop and maintain design systems and component libraries
- Conduct usability testing and incorporate feedback
- Review feature implementations for design consistency and accessibility compliance
- Provide design specifications and assets for development
- Collaborate on user research and A/B test design variations

### Goals
- Deliver user experiences that meet usability and accessibility standards
- Ensure visual consistency across all product touchpoints
- Reduce friction in user workflows and improve satisfaction scores
- Balance user needs with technical feasibility and business goals

### Typical Communication
- Design reviews with Product and Engineering during planning
- Handoff sessions with Developers for implementation details
- Usability testing reports and design iteration updates
- Design system documentation and guidelines

### Interactions
- **Product Managers**: Collaborate on user needs and feature requirements during **initiation**; validate designs align with business goals during **planning**.
- **Developers**: Provide design specs and assets during **planning**; review implementation for pixel-perfect delivery during **execution**.
- **QA Lead**: Coordinate on accessibility and usability testing scenarios during **execution** and before **release**.
- **Project Managers**: Align on design milestones and timelines; flag design dependencies during **planning**.
- **Stakeholders**: Present design concepts for feedback during **initiation** and **planning**; incorporate stakeholder input on branding and user experience.

---

## QA Lead

### Role Summary
The QA Lead owns the quality strategy and ensures test coverage across manual and automated testing efforts. They coordinate testing cycles, report on quality metrics, and work closely with Developers and Product Managers to validate that acceptance criteria are met before release.

### Responsibilities
- Define and execute manual and automated test plans
- Coordinate regression, integration, and end-to-end testing
- Record, triage, and report bugs and quality metrics
- Manage test environments and data
- Review acceptance criteria for testability during planning
- Provide release readiness assessments and sign-offs

### Goals
- Ensure high test coverage and minimize production defects
- Reduce cycle time for test execution through automation
- Provide clear visibility into quality metrics and release readiness
- Foster a culture of quality across the delivery team

### Typical Communication
- Daily sync with Developers on feature testing and bug fixes
- Weekly quality status reports to Product and Project Managers
- Test plan reviews during sprint planning
- Release sign-off communications

### Interactions
- **Developers**: Partner on defining test scenarios during **planning**; coordinate on bug fixes and regression testing during **execution**.
- **Product Managers**: Review acceptance criteria for testability during **planning**; provide quality metrics for go/no-go decisions before **release**.
- **Project Managers**: Report testing progress at status reviews; escalate quality risks that impact timelines during **execution**.
- **UX/UI Designer**: Collaborate on usability and accessibility testing scenarios during **execution**.
- **DevOps/Platform Engineer**: Coordinate test environment setup and test data management; validate deployment verification tests before **release**.
- **Stakeholders**: Provide release quality summaries at milestone reviews and **retrospectives**.

---

## DevOps/Platform Engineer

### Role Summary
DevOps/Platform Engineers manage CI/CD pipelines, infrastructure, deployment processes, and release automation. They ensure reliable delivery, rapid rollbacks, and operational excellence from development through production environments.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Manage infrastructure, environments, and cloud resources
- Ensure observability through monitoring, logging, and alerting
- Implement security and compliance controls in the pipeline
- Facilitate releases, hotfixes, and rollback procedures
- Provide environment parity across dev, staging, and production

### Goals
- Enable fast, reliable, and repeatable deployments
- Minimize deployment risk through automation and observability
- Reduce time to detect and recover from incidents
- Support developer productivity with efficient tooling and infrastructure

### Typical Communication
- Weekly deployment coordination with Project Managers
- Infrastructure updates and pipeline improvements
- Incident response and post-mortem participation
- Platform roadmap discussions with engineering leadership

### Interactions
- **Developers**: Collaborate on build automation, environment setup, and deployment troubleshooting during **execution**; improve CI/CD workflows.
- **QA Lead**: Provide and maintain test environments; coordinate on deployment verification tests before **release**.
- **Project Managers**: Coordinate release schedules and deployment windows during **planning** and **release**; report on infrastructure dependencies and deployment risks.
- **Product Managers**: Discuss operational requirements, monitoring dashboards, and rollout strategies during **planning**.
- **Stakeholders**: Communicate deployment status during **release**; participate in incident communications and provide recovery updates.

---

## Stakeholders (Expanded)

### Role Summary
Stakeholders represent the business, customer, and operational interests in the project. This group includes diverse perspectives such as Business Owners/Sponsors who provide funding and strategic direction, Customer Success Managers who advocate for customer needs, and Sales Engineers who provide market and competitive insights. Stakeholders provide input during initiation, approve key decisions, and ensure alignment with business objectives.

### Sub-Personas

#### Business Owner/Sponsor
- Provides project funding and strategic alignment
- Makes go/no-go decisions at key gates (initiation, major scope changes)
- Ensures project outcomes align with business goals and ROI expectations
- Escalation point for unresolved issues impacting budget or timeline

#### Customer Success Manager
- Represents customer voice and advocates for user needs
- Provides feedback on feature requests and usability concerns
- Coordinates beta testing and early access programs
- Helps plan customer communications for releases

#### Sales Engineer
- Provides market intelligence and competitive analysis
- Highlights feature gaps impacting sales cycles
- Validates that deliverables meet customer requirements and demos
- Participates in feature prioritization discussions

### Responsibilities
- Provide input and requirements during **initiation** and **planning**
- Review and approve key deliverables at defined checkpoints
- Participate in milestone demos and provide feedback
- Escalate business-critical issues and unblock decisions
- Validate that outcomes meet business and customer success criteria

### Goals
- Ensure project outcomes deliver measurable business value
- Maintain alignment between project scope and organizational strategy
- Minimize business risk through informed decision-making
- Support adoption and customer satisfaction post-release

### Typical Communication
- Participation in project kickoffs and milestone reviews
- Approval requests for scope changes or budget adjustments
- Status updates via email, dashboards, or stakeholder briefings
- Feedback on demos and release readiness

### Interactions
- **Product Managers**: Provide business requirements and success criteria during **initiation**; review roadmap priorities and validate feature scope during **planning**.
- **Project Managers**: Receive regular status updates; participate in decision gates and approve resource or timeline changes during **execution** and **release**.
- **Developers**: Attend demos during milestone reviews; provide clarification on business requirements as needed.
- **QA Lead**: Review release readiness reports; approve go-live based on quality metrics during **release**.
- **DevOps/Platform Engineer**: Receive deployment and incident communications; approve production changes requiring business sign-off.
- **UX/UI Designer**: Provide feedback on design concepts and usability during **planning**; validate that user experience meets business goals.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The expanded set of personas (including Designer, QA Lead, DevOps, and Stakeholder sub-roles) ensures clarity on who is responsible for key activities across the project lifecycle: initiation, planning, execution, release, and retrospective.
- Refer to `octoacme-role-interactions-and-ownership.md` for a detailed matrix showing how these roles interact with specific artifacts and ceremonies.

