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

## Release Manager

### Role Summary
Release Managers coordinate release activities, enforce deployment checklists, and communicate release status with all stakeholders. They ensure that releases meet quality standards and are executed with minimal risk to production systems.

### Responsibilities
- Schedule and coordinate release activities across teams
- Ensure all pre-release requirements are met (testing, documentation, approvals)
- Own rollback/escalation communications and post-release documentation
- Monitor release execution and manage go/no-go decisions
- Maintain release notes and deployment logs
- Coordinate with deployment infrastructure teams on deployment windows

### Goals
- Execute reliable, predictable releases with minimal risk
- Reduce mean time to recovery (MTTR) through effective rollback planning
- Maintain clear communication across technical and non-technical stakeholders
- Build confidence in release processes through documentation and repeatability

### Typical Communication
- Pre-release checklist reviews with Developers, QA, and Product teams
- Release readiness meetings with technical stakeholders
- Post-deployment status communications to Support, Sales, and Product teams
- Incident response coordination if issues arise during or after deployment

---

## UX Designer

### Role Summary
UX Designers ensure that solutions are usable, accessible, and continuously improved through user feedback. They advocate for the end user throughout the product development lifecycle and collaborate closely with Product and Development teams.

### Responsibilities
- Develop wireframes, prototypes, and design specifications for new features
- Conduct usability reviews and accessibility assessments
- Provide UX acceptance criteria to guide Developer and QA implementation
- Collaborate with Product Managers on feature scope and user requirements
- Conduct user research and incorporate feedback into design iterations
- Review developed features for adherence to design specifications and usability standards

### Goals
- Deliver intuitive, accessible user experiences that delight customers
- Reduce support tickets related to usability issues
- Advocate for user needs in trade-off discussions
- Ensure consistency in design patterns and interactions across the product

### Typical Communication
- Early design reviews with Product Managers and key stakeholders
- Collaboration sessions with Developers during sprint planning and implementation
- Feedback and review cycles with QA before feature acceptance
- User testing sessions and findings documentation

---

## QA Lead

### Role Summary
QA Leads own test strategy, test automation, and quality gates for releases. They ensure that features and releases meet acceptance criteria and quality standards before reaching customers.

### Responsibilities
- Define test plans and test strategies for features and releases
- Oversee manual and automated testing efforts
- Manage quality gates and establish clear acceptance criteria
- Coordinate with Developers on test coverage and edge cases
- Maintain and improve test automation infrastructure
- Gate releases based on quality metrics and test results
- Conduct smoke tests and post-deployment verification

### Goals
- Prevent critical bugs from reaching production
- Build customer confidence through reliable, high-quality releases
- Reduce regression and improve test coverage over time
- Enable fast, confident iteration through automated testing

### Typical Communication
- Test planning sessions with Developers and Product teams
- Daily coordination on test status and blockers
- Quality reviews and gate decisions with Release Manager and Product Lead
- Retrospectives to improve testing practices and processes

---

## DevOps / SRE

### Role Summary
DevOps and Site Reliability Engineers support infrastructure, CI/CD pipelines, and service reliability. They ensure that systems are reliable, scalable, and maintainable in production environments.

### Responsibilities
- Maintain and improve deployment systems, CI/CD pipelines, and infrastructure
- Monitor system health, performance, and alerts
- Troubleshoot production issues and support incident response
- Document runbooks and operational procedures
- Collaborate with Developers on deployability and observability
- Implement security scanning and compliance checks in CI/CD
- Manage infrastructure as code and automate routine operations

### Goals
- Maximize system uptime and reliability
- Enable rapid, safe deployment of features through automation
- Reduce mean time to detection (MTTD) and mean time to recovery (MTTR)
- Improve operational efficiency and reduce manual toil

### Typical Communication
- Infrastructure and deployment planning with Release Manager and Developers
- On-call rotations and incident response coordination
- Operational reviews and capacity planning discussions
- Post-incident retrospectives and action item tracking

---

## Cross-Functional Collaboration

These personas work together in the following key interactions:

- **Developers** collaborate daily with QA Leads and UX Designers during implementation, and with DevOps during deployment planning
- **Product Managers** align with Release Managers on release timing and communicate feature status to stakeholders
- **Project Managers** coordinate across all roles to manage timelines, risks, and dependencies
- **UX Designers** partner with Developers and QA to ensure usability requirements are met
- **QA Leads** work with Release Managers to gate releases and with DevOps on post-deployment verification
- **Release Managers** orchestrate coordination between Developers, QA, DevOps, and stakeholders
- **DevOps/SRE** enable all teams by providing reliable infrastructure and rapid deployment capabilities

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
