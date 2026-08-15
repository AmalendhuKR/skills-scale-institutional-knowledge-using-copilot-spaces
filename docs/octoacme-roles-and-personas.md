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

### Interactions
- Work with Technical Lead on architecture and design decisions
- Collaborate with QA/Testing Lead on test coverage and acceptance criteria
- Receive guidance from Project Manager on priorities and scheduling

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
- Report to Product Lead for strategic alignment and roadmap prioritization
- Collaborate with Project Manager on delivery planning and risk management
- Work with QA/Testing Lead and Developers on acceptance criteria
- Receive business guidance from Stakeholder/Sponsor

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
- Escalate risks and blockers to Product Lead and Stakeholder/Sponsor as needed
- Coordinate with Technical Lead on technical dependencies and timeline impacts
- Work with QA/Testing Lead on release readiness and quality gates
- Align Developers and Product Manager on delivery schedules

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy, test planning, and release readiness validation. They ensure products meet quality standards before reaching customers and identify gaps early in the delivery cycle.

### Responsibilities
- Develop quality assurance and test strategy aligned with project goals
- Create and maintain comprehensive test plans for features and releases
- Validate acceptance criteria and definition of done compliance
- Assess release readiness and identify blockers
- Conduct manual QA for feature acceptance when needed
- Coordinate security and performance testing activities

### Goals
- Ensure product meets quality standards before release
- Identify quality issues early to reduce production defects
- Minimize rework and post-release incidents
- Build confidence in product quality through rigorous testing

### Typical Communication
- Test plan reviews with Developers and Product Manager
- Quality metrics and test coverage reports in weekly syncs
- Release readiness assessments and sign-offs
- Defect tracking and escalation

### Interactions
- Partner with Developers on test coverage, test automation, and acceptance criteria validation
- Align with Product Manager on acceptance criteria and feature validation approach
- Gate releases with Technical Lead and Project Manager before deployment
- Support Developers in understanding quality requirements and test-driven development practices

---

## Technical Lead/Architect

### Role Summary
Technical Leads guide architectural decisions, design reviews, and technology selection. They ensure solutions are scalable, maintainable, and aligned with long-term technical strategy while identifying and mitigating technical risks.

### Responsibilities
- Conduct architectural and design reviews for significant features and components
- Guide technology selection and technical direction decisions
- Identify technical risks and dependencies during planning
- Mentor Developers on technical best practices and design patterns
- Advocate for refactoring and technical debt management
- Ensure alignment with system-wide architectural principles

### Goals
- Ensure scalable, maintainable solutions that withstand future growth
- Identify technical dependencies and risks early
- Reduce technical debt while delivering features
- Foster a culture of technical excellence

### Typical Communication
- Technical design review meetings and architecture decision records (ADRs)
- Participation in sprint planning to assess feasibility and technical constraints
- Technical risk identification in project planning and weekly syncs
- Code review and pair programming sessions

### Interactions
- Guide Developers on architectural decisions and technical implementations
- Provide input to Project Manager and Product Manager on technical feasibility and timeline impact
- Escalate technical risks and complex dependencies to Project Manager for mitigation planning
- Collaborate with QA/Testing Lead on non-functional testing requirements (performance, security, scalability)
- Work with Security & Compliance Officer on architectural security requirements

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide business oversight, validate the business case, allocate resources, and serve as executive decision-makers. They ensure projects deliver business value and remove organizational blockers.

### Responsibilities
- Validate business case and ensure alignment with organizational strategy
- Approve resource allocation and budget for projects
- Arbitrate priority conflicts between competing projects or teams
- Provide executive escalation path for project-level blockers
- Monitor project outcomes against success metrics
- Remove organizational and cross-functional dependencies

### Goals
- Ensure projects deliver measurable business value
- Manage resource constraints and organizational alignment
- Reduce time-to-value through swift decision-making
- Maintain strategic focus across the portfolio of projects

### Typical Communication
- Monthly executive status updates and outcome reviews
- Ad-hoc escalation meetings for critical blockers
- Approval decisions on project charter and major scope changes
- Stakeholder alignment meetings and priority arbitration

### Interactions
- Set overall project vision and success metrics with Product Lead and Product Manager
- Approve major decisions and scope changes proposed by Project Manager
- Receive escalations from Project Manager on critical blockers or resource issues
- Collaborate with Product Lead on strategic roadmap prioritization
- Provide final authority on go/no-go decisions and project pivots

---

## Product Lead

### Role Summary
Product Leads own product strategy, cross-project alignment, and roadmap prioritization. They ensure features align with the overall product vision and maximize customer value across all initiatives.

### Responsibilities
- Define product strategy and vision aligned with business goals
- Review and approve project charters and one-pagers
- Prioritize the overall roadmap across multiple projects and initiatives
- Identify cross-project dependencies and alignment opportunities
- Provide strategic guidance to Product Managers on priorities and trade-offs
- Measure and report on product outcomes and market impact

### Goals
- Ensure all projects align with product vision and strategy
- Maximize cumulative customer value across initiatives
- Reduce duplicated work and leverage synergies between teams
- Make clear, strategic prioritization decisions

### Typical Communication
- Weekly alignment with Project Managers and Product Managers
- Roadmap reviews and strategic planning sessions
- Approval of project charters before moving to planning phase
- Cross-project dependency identification and resolution meetings

### Interactions
- Review and approve project one-pagers from Product Managers before stakeholder alignment
- Provide strategic guidance to Product Managers on priorities and market focus
- Escalate to Stakeholder/Sponsor for resource or priority conflicts
- Mentor Product Managers on product strategy and outcomes thinking
- Monitor Product Manager performance against product strategy and outcomes

---

## Security & Compliance Officer

### Role Summary
Security & Compliance Officers ensure all projects meet security and compliance standards throughout the delivery lifecycle. They review architecture and code, gate deployments, coordinate incident response, and maintain security policies.

### Responsibilities
- Review project security requirements during planning phase
- Conduct architectural and code security reviews before deployment
- Validate compliance with security policies and regulatory requirements
- Gate deployments until security and compliance requirements are met
- Lead incident response coordination for security-related issues
- Update and maintain security policies and standards
- Conduct security training and awareness activities

### Goals
- Ensure all releases meet security and compliance standards
- Prevent security incidents through proactive review and scanning
- Respond swiftly and effectively to security incidents
- Build security awareness and responsibility across the organization

### Typical Communication
- Security review meetings during planning and before deployment
- Security scanning and vulnerability reports in CI/CD pipeline
- Incident response coordination and post-incident retrospectives
- Security policy updates and training communications

### Interactions
- Partner with Technical Lead on architectural security requirements and review
- Review code and deployments with Developers and Project Manager before release
- Lead incident response coordination with Project Manager and Stakeholder/Sponsor when security issues arise
- Work with Project Manager to prioritize security fixes and vulnerability remediation
- Collaborate with QA/Testing Lead on security testing and validation approaches

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the interaction sections to understand decision authority, approval gates, and escalation paths across roles.
