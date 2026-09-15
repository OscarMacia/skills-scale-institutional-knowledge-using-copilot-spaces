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

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality strategy and ensure solutions meet acceptance criteria and quality standards. They work closely with the development team and Product Managers to validate that deliverables are production-ready.

### Responsibilities
- Develop test strategies and test plans aligned with project scope
- Manage QA resources and capacity planning
- Validate acceptance criteria are met before release
- Identify quality gaps and recommend improvements
- Execute manual QA testing when automated coverage is insufficient
- Collaborate with Developers on test automation strategy

### Goals
- Ensure all deliverables meet quality standards
- Reduce defects shipped to production
- Provide confidence in release readiness
- Establish and maintain quality metrics and reporting

### Typical Communication
- Planning sessions to define testing approach and resource needs
- Definition of Done review and refinement
- Pre-release quality gates and smoke test coordination
- Test automation strategy discussions with Development team
- Quality metrics and defect reports in stakeholder updates

### Interaction with Other Roles
- **Works with Developers:** On test coverage, automation frameworks, and acceptance criteria validation
- **Works with Product Managers:** On defining acceptance criteria and testing priorities
- **Works with Project Managers:** On quality timelines and release readiness assessments
- **Works with Release Managers:** On smoke tests and post-deployment verification

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide architectural guidance and technical oversight to ensure solutions are scalable, maintainable, and aligned with technical standards. They mentor the development team and advocate for technical excellence.

### Responsibilities
- Review technical designs and architectures for scalability and maintainability
- Mentor developers on technical best practices and coding standards
- Identify technical risks and dependencies during planning
- Guide decisions on technology choices and trade-offs
- Advocate for reducing technical debt and modernizing legacy systems
- Participate in code reviews for complex or critical components
- Ensure alignment with organizational technical standards

### Goals
- Deliver solutions that are scalable and maintainable
- Minimize technical risk and debt accumulation
- Foster a culture of technical excellence and continuous learning
- Enable fast, reliable deployments

### Typical Communication
- Technical design reviews and architecture discussions
- Planning sessions for feasibility assessment and effort estimation
- Code reviews and technical mentoring of development team
- Risk register updates for technical concerns
- Architecture decision records (ADRs) and technical documentation

### Interaction with Other Roles
- **Works with Developers:** On design reviews, mentoring, and technical guidance
- **Works with Product Managers:** On feasibility assessment and technical trade-offs
- **Works with Project Managers:** On technical dependencies, risks, and timeline impacts
- **Works with QA/Testing Leads:** On test strategy and automation architecture

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, strategic alignment, and resource support to enable project success. They represent business interests and remove organizational blockers.

### Responsibilities
- Align on project vision, priorities, and success metrics
- Approve go/no-go decisions at key project gates
- Remove business and organizational blockers
- Provide executive visibility and support for project outcomes
- Give feedback on deliverables and ROI against original objectives
- Allocate and protect resources for the project

### Goals
- Ensure projects deliver business value and ROI
- Align projects with organizational strategy
- Enable fast, informed decision-making at escalation points
- Maintain stakeholder engagement and satisfaction

### Typical Communication
- Kickoff and planning gate reviews for alignment
- Monthly stakeholder status updates on progress and risks
- Ad-hoc escalations for business decisions and blocker removal
- Post-release outcome reviews and success measurement
- Executive briefings and board-level reporting (if needed)

### Interaction with Other Roles
- **Works with Project Managers:** On status updates, decision gates, and escalations
- **Works with Product Managers:** On strategic alignment and prioritization
- **Receives input from entire team:** On risks, dependencies, and delivery updates

---

## Security / Compliance Officer

### Role Summary
Security and Compliance Officers ensure projects meet security standards, regulatory requirements, and risk management policies. They provide security guidance throughout the project lifecycle.

### Responsibilities
- Review security designs and threat models during planning
- Conduct security assessments of implementations before release
- Manage compliance with regulatory requirements and organizational policies
- Advise on incident response procedures and escalation paths
- Maintain security documentation and audit trails
- Identify security risks and recommend mitigations
- Conduct security training and awareness activities

### Goals
- Minimize security risk and vulnerabilities in production
- Maintain regulatory compliance and pass external audits
- Enable secure-by-design practices across all projects
- Establish and maintain security standards

### Typical Communication
- Planning reviews for security considerations and requirements
- Code and architecture security reviews with development team
- Security incident response and communication protocols
- Compliance audit participation and reporting
- Security risk assessments in the project risk register

### Interaction with Other Roles
- **Works with Developers:** On security requirements, code reviews, and vulnerability remediation
- **Works with Technical Leads:** On architecture security and design decisions
- **Works with Project Managers:** On security risks and compliance timelines
- **Works with Release Managers:** On security scanning and pre-deployment verification

---

## Release Manager / DevOps Engineer

### Role Summary
Release Managers and DevOps Engineers manage deployment infrastructure, orchestrate releases, and ensure production stability. They enable fast, reliable, and safe deployments to production.

### Responsibilities
- Design and maintain CI/CD pipelines and infrastructure
- Execute and coordinate deployments across environments
- Manage rollback procedures and incident response
- Maintain release documentation, runbooks, and procedures
- Monitor deployment health and observability post-release
- Coordinate with teams on release scheduling and windows
- Automate repetitive deployment and infrastructure tasks

### Goals
- Enable fast, reliable, and safe deployments
- Minimize deployment risk and production downtime
- Maintain high availability and system performance
- Reduce manual effort and human error in releases

### Typical Communication
- Release planning and scheduling coordination with Project Managers
- Pre-release deployment walkthroughs with development teams
- Post-deploy verification and monitoring with QA teams
- Incident response coordination and root cause analysis
- Infrastructure and deployment process documentation
- CI/CD pipeline updates and automation improvements

### Interaction with Other Roles
- **Works with Developers:** On pipeline requirements, artifact management, and deployment procedures
- **Works with QA/Testing Leads:** On smoke tests and post-deployment verification
- **Works with Project Managers:** On release schedules and deployment coordination
- **Works with Security Officers:** On security scanning and compliance checks in pipelines

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Personas should be referenced in project charters and team compositions to clarify accountability and communication patterns.
