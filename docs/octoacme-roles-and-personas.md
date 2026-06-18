# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Product & Delivery Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

#### Key Interactions
- **With Tech Lead**: receive technical guidance, code review feedback, architecture decisions
- **With QA/Testing**: collaborate on test plans and acceptance criteria verification
- **With Platform/DevOps**: coordinate deployment and infrastructure needs
- **With Project Manager**: participate in planning and status updates

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Key Interactions
- **With Project Manager**: weekly sync on delivery status, timeline risks, dependencies
- **With Tech Lead**: validate feasibility and discuss technical trade-offs
- **With UX Researcher**: review research findings and validate design decisions
- **With Data Analyst**: review metrics and usage data to inform decisions

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Key Interactions
- **With Product Manager**: align on scope, priorities, and success metrics
- **With Engineering Manager**: coordinate resource availability and capacity planning
- **With Incident Commander**: manage incident escalations and post-incident actions
- **With Support Lead**: triage and prioritize customer-impacting issues

---

## Operational & Cross-Functional Roles

### Engineering Manager

#### Role Summary
Engineering Managers oversee engineering team health, capacity planning, and cross-team coordination. They enable developers to do their best work while aligning team efforts with organizational priorities.

#### Responsibilities
- Manage team capacity and resource allocation across projects
- Conduct career development conversations and performance reviews
- Identify and resolve team-level blockers
- Provide input on technical prioritization and feasibility
- Mentor and support engineering staff

#### Goals
- Maintain team health, productivity, and morale
- Enable efficient resource utilization across the organization
- Reduce team-level dependencies and bottlenecks

#### Typical Communication
- One-on-ones with team members
- Capacity planning and resource negotiation with Project Managers
- Technical leadership meetings with Tech Leads

#### Key Interactions
- **With Project Manager**: align team capacity to roadmap demands, discuss staffing constraints
- **With Tech Leads**: provide technical direction and mentorship
- **With Product Manager**: input on feasibility and effort estimation
- **With Developers**: career development, performance feedback, and support

---

### Tech Lead

#### Role Summary
Tech Leads are technical owners for a service or feature area. They ensure design quality, maintain architectural consistency, and mentor engineers.

#### Responsibilities
- Drive architecture and design decisions for services or components
- Establish code review cadence and quality standards
- Mentor and support developers on the team
- Ensure non-functional requirements (performance, security, scalability) are met
- Identify and communicate technical risks and opportunities

#### Goals
- Maintain high code quality and architectural consistency
- Reduce technical debt and improve system reliability
- Enable team growth through mentorship and knowledge sharing

#### Typical Communication
- Design reviews and architecture discussions
- Code reviews and technical guidance
- Technical design documents and RFCs

#### Key Interactions
- **With Developers**: provide technical guidance, code reviews, and mentorship
- **With QA/Testing**: collaborate on testability and quality strategies
- **With Platform/DevOps**: coordinate infrastructure and deployment needs
- **With Product Manager**: translate requirements into technical scope and discuss trade-offs
- **With Engineering Manager**: provide technical input on team capability and growth

---

### UX Researcher / Designer

#### Role Summary
UX Researchers and Designers own user research, usability testing, and design quality. They ensure solutions are usable and accessible.

#### Responsibilities
- Conduct user research studies and validate assumptions
- Create wireframes, prototypes, and design specifications
- Perform accessibility audits and recommend improvements
- Test designs with users and iterate based on feedback
- Document design decisions and patterns

#### Goals
- Ensure solutions are usable, accessible, and delightful
- Reduce design-related rework through early validation
- Build a cohesive and consistent user experience

#### Typical Communication
- Research reports and findings presentations
- Design reviews and feedback sessions
- Accessibility checklists and guidelines

#### Key Interactions
- **With Product Manager**: collaborate on success criteria and validate research findings
- **With Developers**: discuss implementation feasibility and design patterns
- **With QA/Testing**: define acceptance criteria based on design specifications
- **With Support Lead**: gather customer feedback on usability issues

---

### Platform / DevOps Engineer

#### Role Summary
Platform and DevOps Engineers manage CI/CD infrastructure, deployment automation, and observability. They enable teams to deploy reliably and respond quickly to issues.

#### Responsibilities
- Design and maintain CI/CD pipelines and infrastructure
- Automate deployment processes and reduce manual work
- Implement monitoring, logging, and alerting systems
- Maintain incident runbooks and disaster recovery procedures
- Plan for capacity and scalability

#### Goals
- Enable fast, reliable, and safe deployments
- Minimize downtime and improve mean time to recovery (MTTR)
- Provide visibility into system health and performance

#### Typical Communication
- Deployment pipeline documentation and runbooks
- Infrastructure change reviews and capacity planning
- Incident response coordination

#### Key Interactions
- **With Developers**: support deployment patterns and troubleshooting
- **With Project Manager**: coordinate release schedules and deployment windows
- **With Incident Commander**: provide technical support during incidents
- **With Security Liaison**: implement security scanning and compliance checks

---

### Incident Commander (Rotating Role)

#### Role Summary
Incident Commanders lead incident response for major outages or severity incidents. They coordinate responders, manage communications, and ensure swift resolution.

#### Responsibilities
- Coordinate incident responders and track actions
- Communicate status updates to stakeholders
- Document incident timeline and decisions
- Run post-incident reviews and capture action items
- Escalate to leadership for business-impacting incidents

#### Goals
- Minimize incident duration and customer impact
- Improve incident response effectiveness over time
- Create a blameless, learning-focused culture

#### Typical Communication
- Incident status updates (internal and external)
- Post-incident review notes
- Incident escalation communications

#### Key Interactions
- **With Platform/DevOps**: technical troubleshooting and remediation
- **With Developers**: assist with code-level debugging and fixes
- **With Support Lead**: coordinate customer communication and status
- **With Project Manager**: escalate business impact and timeline updates
- **With Security Liaison**: coordinate for security-related incidents

---

### Support Lead / Customer Success Liaison

#### Role Summary
Support Leads own customer-facing communications and triage major support escalations. They ensure customer issues are addressed quickly and escalated appropriately.

#### Responsibilities
- Triage support tickets and validate severity levels
- Escalate customer-impacting bugs to the engineering team
- Coordinate workarounds and temporary fixes
- Manage customer communication during incidents
- Provide feedback on product usability issues

#### Goals
- Resolve customer issues quickly and effectively
- Reduce time-to-resolution for critical issues
- Improve customer satisfaction and trust

#### Typical Communication
- Support ticket triage and escalation emails
- Customer-facing incident updates
- Feature request and bug feedback summaries

#### Key Interactions
- **With Project Manager**: escalate urgent customer issues and timeline impacts
- **With Developers**: coordinate reproduction steps and provide debugging information
- **With Incident Commander**: manage external communications during incidents
- **With Product Manager**: provide customer feedback on usability and feature requests
- **With QA/Testing**: verify bug fixes before customer communication

---

### Security Liaison / AppSec

#### Role Summary
Security Liaisons coordinate security reviews and risk assessments. They ensure security requirements are met and help teams understand security best practices.

#### Responsibilities
- Conduct threat modeling and security reviews for new features
- Establish and maintain security checklists and guidelines
- Coordinate security scanning and vulnerability remediation
- Provide security training and guidance to teams
- Manage compliance and audit requirements

#### Goals
- Reduce security vulnerabilities and risk exposure
- Enable teams to build secure solutions by design
- Maintain compliance with regulations and standards

#### Typical Communication
- Security review checklists and approval sign-offs
- Threat model documents
- Security incident notifications

#### Key Interactions
- **With Tech Leads**: conduct security reviews and design discussions
- **With Platform/DevOps**: coordinate security scanning and infrastructure hardening
- **With Project Manager**: prioritize security work and timeline impacts
- **With Developers**: provide guidance on secure coding practices
- **With Incident Commander**: coordinate response for security-related incidents

---

### Data Analyst / Analytics Owner

#### Role Summary
Data Analysts own measurement strategy, dashboards, and data requests. They enable data-driven decision-making through reliable metrics and insights.

#### Responsibilities
- Define success metrics and KPIs for projects and features
- Design and implement event instrumentation
- Build dashboards and reports for stakeholders
- Analyze usage data and provide insights
- Validate data quality and completeness

#### Goals
- Enable data-informed decision-making
- Provide reliable, actionable insights
- Reduce time-to-insight for key questions

#### Typical Communication
- Metrics definitions and data dictionaries
- Dashboard and report updates
- Analysis summaries and insights

#### Key Interactions
- **With Product Manager**: define success metrics and review performance data
- **With Developers**: coordinate event instrumentation and data schema
- **With Project Manager**: provide metrics for project status and impact
- **With Support Lead**: analyze support tickets and usage patterns for feedback

---

## QA/Testing

#### Role Summary
QA and Testing professionals ensure quality standards are met. They validate features, identify bugs, and provide feedback on acceptance criteria.

#### Responsibilities
- Execute test plans and validate acceptance criteria
- Identify and document bugs with reproduction steps
- Conduct exploratory testing and edge case analysis
- Provide feedback on usability and quality
- Maintain test automation and CI integration

#### Goals
- Ensure high quality of shipped features
- Catch defects early and reduce production issues
- Provide fast, reliable feedback on quality

#### Typical Communication
- Test plans and test case documentation
- Bug reports and quality metrics
- QA sign-off on acceptance criteria

#### Key Interactions
- **With Developers**: clarify acceptance criteria and test scenarios
- **With Product Manager**: validate acceptance criteria alignment
- **With Tech Lead**: discuss testability and testing strategies
- **With Support Lead**: reproduce and verify customer-reported issues

---

## How to Use These Personas

- Use these persona definitions to frame scenarios and sample interactions in project documentation
- Assign responsibilities clearly at project initiation based on these role definitions
- Use the "Key Interactions" section to identify cross-team dependencies
- For projects, map each persona to a named individual or confirm the role is not needed
- Refer to interaction patterns when planning escalation paths and communication cadences
