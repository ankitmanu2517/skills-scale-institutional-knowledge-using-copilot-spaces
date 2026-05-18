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

## QA/Test Engineers

### Role Summary
QA/Test Engineers ensure product quality by designing test strategies, validating acceptance criteria, and maintaining automated test suites. They collaborate closely with Developers and Product Managers to catch defects early and verify that features meet user expectations.

### Responsibilities
- Design and execute test plans (manual and automated)
- Validate features against acceptance criteria and Definition of Done
- Maintain and expand automated regression test suites
- Report and triage bugs, ensuring clear reproduction steps
- Participate in sprint planning to assess testability of stories

### Goals
- Ensure features ship with high quality and minimal regressions
- Increase automated test coverage to reduce manual QA cycles
- Provide fast, reliable feedback on build quality

### Typical Communication
- Sprint planning and refinement sessions (testability input)
- Bug reports and test result summaries
- QA sign-off notes on PRs and release candidates

### Interaction with Existing Roles
- Works with **Developers** on testability during design and code review
- Validates acceptance criteria defined by **Product Managers**
- Reports quality metrics and test coverage to **Project Managers**

---

## UX/Design Lead

### Role Summary
UX/Design Leads ensure that product features are intuitive, accessible, and aligned with user needs. They translate user research into design specifications that guide development.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Define interaction patterns and design system standards
- Collaborate on acceptance criteria to include usability requirements
- Review implemented features for design fidelity

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support task completion
- Maintain design consistency across the product

### Typical Communication
- Design reviews and critique sessions
- Handoff documentation (specs, assets, annotations)
- Usability test findings and recommendations

### Interaction with Existing Roles
- Partners with **Product Managers** on user problems and feature scoping
- Provides design specs and assets to **Developers**
- Informs **Project Managers** of design dependencies and review timelines

---

## DevOps/Site Reliability Engineers (SRE)

### Role Summary
DevOps/SRE Engineers own the reliability, performance, and deployment infrastructure. They ensure CI/CD pipelines run smoothly, monitor production health, and respond to incidents.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Monitor production systems (uptime, latency, error rates)
- Manage infrastructure-as-code and environment provisioning
- Lead incident response and post-incident reviews
- Define SLOs/SLIs and reliability targets

### Goals
- Maintain high availability and meet SLO targets
- Reduce deployment risk through automation and guardrails
- Minimize mean time to recovery (MTTR) during incidents

### Typical Communication
- Incident channels and post-incident review meetings
- Deployment status updates and release coordination
- Infrastructure change proposals and review

### Interaction with Existing Roles
- Collaborates with **Developers** on deployment readiness and observability
- Provides release infrastructure support to **Project Managers**
- Escalates production risks and incidents per the communication plan

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide architectural guidance, ensure technical consistency across the codebase, and mentor developers. They bridge the gap between product vision and technical implementation.

### Responsibilities
- Define system architecture and technical standards
- Review technical designs and ensure scalability/maintainability
- Mentor developers and conduct design reviews
- Identify technical debt and propose remediation plans
- Collaborate on feasibility assessments during planning

### Goals
- Ensure architectural decisions support long-term scalability
- Reduce technical debt and improve code quality over time
- Enable developers to make consistent, informed technical choices

### Typical Communication
- Architecture decision records (ADRs)
- Technical design review meetings
- Mentorship and pairing sessions

### Interaction with Existing Roles
- Advises **Product Managers** on technical feasibility and trade-offs
- Guides **Developers** on implementation patterns and best practices
- Informs **Project Managers** of architectural risks and dependencies

---

## Stakeholder/Executive Sponsor

### Role Summary
Executive Sponsors provide strategic direction, approve resources, and remove organizational blockers. They ensure projects stay aligned with business objectives and have the support needed to succeed.

### Responsibilities
- Approve project charters and resource allocation
- Remove escalated organizational blockers
- Provide strategic guidance on scope and priority shifts
- Represent project outcomes to leadership and the broader organization

### Goals
- Ensure projects deliver measurable business value
- Maintain alignment between project goals and organizational strategy
- Enable teams by clearing escalated blockers quickly

### Typical Communication
- Monthly stakeholder updates and executive summaries
- Escalation discussions with Project Managers
- Strategic alignment meetings with Product Managers

### Interaction with Existing Roles
- Receives status updates and escalations from **Project Managers**
- Aligns with **Product Managers** on business priorities and trade-offs
- Acts as final escalation point in the risk escalation path (Team → PM → Product Lead → Sponsor)

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

