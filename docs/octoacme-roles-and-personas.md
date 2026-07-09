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

## QA/Test Lead

### Role Summary
QA/Test Leads own quality strategy, acceptance criteria validation, and test coverage. They collaborate with Product and Engineering to define testability requirements and ensure features meet quality standards before release.

### Responsibilities
- Define test strategy and approach for features and releases
- Develop and maintain test cases aligned to acceptance criteria
- Coordinate testing across unit, integration, and end-to-end levels
- Validate that features meet Definition of Done before merge
- Identify and report quality risks and defects
- Facilitate root-cause analysis for production incidents

### Goals
- Prevent defects from reaching production
- Maintain high test coverage and observability
- Enable rapid, confident releases
- Balance speed with quality standards

### Interaction with Other Roles
- **Developers**: Review test plans, collaborate on testability and CI automation
- **Product Manager**: Align test strategy with feature priority and acceptance criteria
- **Project Manager**: Report quality metrics and blockers; escalate release-readiness risks
- **DevOps/Infrastructure Engineer**: Coordinate smoke test and post-deploy verification execution

### Typical Communication
- Test strategy docs and test case specifications
- Quality metrics and defect reports
- Participation in planning and retrospectives

---

## Security/Compliance Officer

### Role Summary
Security/Compliance Officers ensure projects meet organizational security policies, regulatory requirements, and data protection standards. They provide guidance on threat modeling, data handling, and secure development practices.

### Responsibilities
- Review features for security and compliance implications
- Conduct or coordinate threat modeling and risk assessments
- Define security requirements and acceptance criteria
- Ensure secure code practices and dependencies are vetted
- Coordinate security scanning in CI/CD pipeline
- Manage incident response and security escalations
- Track and audit compliance controls

### Goals
- Reduce security vulnerabilities and compliance violations
- Enable secure, compliant feature delivery
- Maintain customer trust and regulatory standing
- Make security decisions early, not late

### Interaction with Other Roles
- **Developers**: Review designs and code; guide secure implementation practices
- **Product Manager**: Define privacy and security requirements in features
- **Project Manager**: Flag security risks in planning; escalate incidents
- **DevOps/Infrastructure Engineer**: Integrate security scanning and monitoring into deployment pipeline

### Typical Communication
- Threat modeling and security review findings
- Security requirements and acceptance criteria
- Incident escalations and post-incident reviews

---

## DevOps/Infrastructure Engineer

### Role Summary
DevOps/Infrastructure Engineers design, build, and maintain the systems that support development, testing, and production environments. They enable reliable, scalable deployment and observability.

### Responsibilities
- Design infrastructure and deployment architecture
- Automate CI/CD pipelines and testing environments
- Manage production environments, monitoring, and observability
- Plan and execute deployments; manage rollback procedures
- Identify infrastructure risks and capacity constraints
- Support incident response and root-cause analysis
- Document deployment runbooks and operational playbooks

### Goals
- Enable fast, safe deployments with minimal manual work
- Maintain high availability and performance
- Provide rapid observability and incident response
- Reduce deployment risk and mean-time-to-recovery

### Interaction with Other Roles
- **Developers**: Support CI setup, environment provisioning, and local development tools
- **QA/Test Lead**: Provision test environments; automate smoke tests
- **Project Manager**: Provide deployment windows, capacity constraints, and risk input
- **Technical Architect**: Collaborate on infrastructure design and scalability planning

### Typical Communication
- Deployment plans and infrastructure architecture docs
- Capacity and availability metrics
- Runbooks and incident response coordination

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders/Sponsors represent business and customer interests, provide resources and decision authority, and ensure projects align with organizational strategy.

### Responsibilities
- Approve project charter and resource allocation
- Make trade-off decisions (scope, schedule, budget)
- Escalate blockers and risks that impact business outcomes
- Provide regular feedback and validation
- Champion project internally and remove organizational barriers
- Review and approve releases and go-to-market plans

### Goals
- Ensure projects deliver business value and strategic alignment
- Reduce delays from organizational or policy barriers
- Make timely, informed decisions
- Achieve successful project outcomes and adoption

### Interaction with Other Roles
- **Project Manager**: Receive weekly status updates and escalations; make trade-off decisions
- **Product Manager**: Validate success metrics and prioritization; align with business goals
- **Technical Architect**: Understand technical risks and dependencies impacting delivery

### Typical Communication
- Weekly status updates and escalations
- Go/no-go decision requests
- Stakeholder briefings and reviews

---

## Technical Architect

### Role Summary
Technical Architects design system architecture, evaluate technical trade-offs, and mitigate complex technical risks. They ensure solutions are scalable, maintainable, and aligned with organizational standards.

### Responsibilities
- Lead technical design and architecture decisions
- Evaluate technical trade-offs (performance, scalability, maintainability)
- Identify technical risks and propose mitigations
- Review system designs and code for architectural alignment
- Plan technical migration and integration strategies
- Mentor developers on architectural patterns and best practices
- Coordinate cross-system dependencies

### Goals
- Deliver systems that are scalable, maintainable, and performant
- Reduce technical debt and rework
- Enable rapid feature delivery without architectural bottlenecks
- Share architectural knowledge across the team

### Interaction with Other Roles
- **Developers**: Collaborate on design; mentor on architectural patterns
- **Project Manager**: Identify technical risks, dependencies, and schedule impacts
- **DevOps/Infrastructure Engineer**: Collaborate on infrastructure and deployment architecture
- **Product Manager**: Understand architectural constraints on features

### Typical Communication
- Architecture design documents and technical RFCs
- Design review participation
- Technical risk assessments and mitigation plans

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
