# OctoAcme Personas

<!-- Updated 2025-10-20: Expanded roles to include UX Designer, Release Manager, DevOps Engineer, Business Analyst, and Support Lead to address gaps in role clarity and accountability (Issue #4) -->

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

## UX Designer

### Role Summary
UX Designers focus on understanding user needs and creating intuitive, accessible experiences. They collaborate with product managers and developers to design interfaces and workflows that meet usability and accessibility standards.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and prototypes
- Define user flows and interaction patterns
- Collaborate with developers on implementation feasibility
- Ensure designs meet accessibility standards (WCAG)
- Maintain design systems and component libraries

### Goals
- Deliver user-friendly and accessible experiences
- Reduce user friction and support requests
- Ensure design consistency across products
- Validate designs through user feedback and testing

### Typical Communication
- Design reviews and critique sessions
- User research findings and personas
- Collaboration with PM and engineering on feature feasibility
- Handoff documentation and design specs

---

## Release Manager

### Role Summary
Release Managers orchestrate the end-to-end release process, coordinating across teams to ensure smooth deployments. They own the release calendar, manage release readiness, and facilitate go/no-go decisions.

### Responsibilities
- Maintain release calendar and coordinate release windows
- Track release readiness across teams (code, docs, tests, approvals)
- Facilitate go/no-go meetings and release decision gates
- Coordinate communication to stakeholders about releases
- Ensure rollback plans and incident response readiness
- Track and report on release metrics (frequency, lead time, success rate)

### Goals
- Deliver reliable releases with minimal disruption
- Reduce release cycle time and increase deployment frequency
- Minimize failed deployments and rollbacks
- Ensure clear communication and coordination across teams

### Typical Communication
- Release calendar updates and planning meetings
- Release readiness reports and checklists
- Go/no-go decision meetings
- Post-release summaries and metrics

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain the infrastructure, automation, and tooling that enable reliable software delivery. They focus on CI/CD pipelines, observability, security, and operational excellence.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure and deployment automation
- Implement monitoring, logging, and alerting
- Ensure security scanning and compliance in pipelines
- Support incident response and on-call rotations
- Optimize build times and deployment reliability

### Goals
- Enable fast, safe, and automated deployments
- Maximize system reliability and uptime
- Reduce toil through automation
- Maintain security and compliance standards

### Typical Communication
- Infrastructure and deployment planning discussions
- Incident postmortems and runbook updates
- Security and compliance reviews
- Platform and tooling improvement proposals

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and delivery teams. They gather requirements, analyze business processes, and ensure solutions align with organizational goals and constraints.

### Responsibilities
- Elicit and document business requirements
- Analyze current processes and identify improvement opportunities
- Create functional specifications and use cases
- Facilitate requirements workshops with stakeholders
- Validate that delivered solutions meet business needs
- Support change management and user adoption

### Goals
- Ensure solutions deliver measurable business value
- Reduce ambiguity and misalignment in requirements
- Improve process efficiency and effectiveness
- Facilitate successful adoption of new capabilities

### Typical Communication
- Requirements documentation and specifications
- Stakeholder workshops and alignment meetings
- Business process diagrams and workflow maps
- User acceptance testing coordination

---

## Support Lead

### Role Summary
Support Leads represent the customer support organization in project work. They ensure that new features are supportable, documentation is complete, and the support team is prepared for launch.

### Responsibilities
- Review features for supportability and common user issues
- Provide input on error messages and user guidance
- Ensure support documentation and runbooks are complete
- Coordinate support team training on new features
- Represent customer voice based on support ticket trends
- Define escalation paths and SLA requirements

### Goals
- Reduce support ticket volume through better design
- Ensure support team readiness for new releases
- Minimize time to resolution for customer issues
- Improve customer satisfaction and retention

### Typical Communication
- Feature reviews for supportability
- Support readiness checklists and training materials
- Customer impact assessments
- Escalation and incident coordination

---

## Role Interactions

### How Core and Extended Roles Collaborate

**Project Initiation:**
- **Product Manager** defines the problem and success metrics, working with **Business Analyst** to gather requirements and validate business value
- **UX Designer** conducts user research to inform problem framing
- **Project Manager** identifies all stakeholders including **Support Lead** for supportability input

**Planning:**
- **Developers** and **DevOps Engineer** collaborate on technical design and infrastructure needs
- **UX Designer** creates designs and validates with PM and users
- **Business Analyst** documents detailed requirements and acceptance criteria
- **Release Manager** ensures release planning aligns with calendar and dependencies
- **Support Lead** reviews plans for support readiness requirements

**Execution:**
- **Developers** implement features following designs from **UX Designer**
- **DevOps Engineer** builds and maintains CI/CD pipelines for automated testing and deployment
- **Business Analyst** validates that implementation meets business requirements
- **Project Manager** coordinates across all roles and tracks progress

**Release:**
- **Release Manager** orchestrates the release process and go/no-go decisions
- **DevOps Engineer** executes deployments and monitors system health
- **Support Lead** ensures support team readiness and escalation paths
- **Project Manager** coordinates release communication

**Post-Release:**
- **Support Lead** monitors customer feedback and support tickets
- **Product Manager** tracks success metrics and impact
- **UX Designer** gathers user feedback for future improvements
- All roles participate in retrospectives facilitated by **Project Manager**

### Communication Flow
- **Strategic:** PM, PdM, Business Analyst align on roadmap and priorities
- **Tactical:** Project Manager coordinates daily execution with Developers, DevOps, UX Designer
- **Release:** Release Manager synchronizes with DevOps Engineer, PM, and Support Lead
- **Customer:** Support Lead feeds customer insights to PM, PdM, and UX Designer

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

