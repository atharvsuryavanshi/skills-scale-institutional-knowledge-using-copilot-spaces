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
- **With Engineering Lead**: Receive architecture guidance and code review feedback
- **With QA**: Clarify acceptance criteria and ensure testability
- **With UX/Design**: Review design specs and implement UI/UX requirements
- **With DevOps**: Coordinate deployment requirements and runbook updates

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
- **With Delivery Lead**: Discuss timeline, risks, and stakeholder updates
- **With Data Analyst**: Define and interpret success metrics
- **With UX Researcher**: Validate user needs and design direction
- **With Engineering Lead**: Negotiate scope and technical trade-offs

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
- **With Delivery Lead**: Synchronize milestones and remove blockers
- **With Engineering Lead**: Address technical dependencies and risks
- **With Product Manager**: Align on priorities and stakeholder expectations
- **With Release Manager**: Coordinate release readiness and go-live activities

---

## Engineering Lead / Tech Lead

### Role Summary
Engineering Leads oversee technical design and implementation quality across a project. They provide architecture guidance, mentor developers, and own technical risk mitigation.

### Responsibilities
- Provide architecture guidance and technical design decisions
- Mentor and support developers on technical challenges
- Conduct and oversee code reviews to maintain quality standards
- Own technical risk register items and propose mitigations
- Coordinate with other teams on technical dependencies
- Document technical decisions and design rationale

### Goals
- Ensure scalable, maintainable, and secure technical implementation
- Reduce technical debt and complexity
- Foster a culture of quality and continuous improvement
- Enable team autonomy through clear technical direction

### Typical Communication
- Technical design reviews and architecture discussions
- Code review feedback and mentoring sessions
- Risk escalations and mitigation planning
- Cross-team technical coordination

### Key Interactions
- **With Developers**: Provide technical guidance, review code, mentor on best practices
- **With Project Manager**: Escalate technical risks and dependencies
- **With QA**: Define testability requirements and acceptance criteria
- **With DevOps**: Coordinate deployment, scaling, and infrastructure needs
- **With Product Manager**: Discuss technical feasibility and trade-offs

### Handoff Checklist
- [ ] Architecture and design decisions documented
- [ ] Code review standards and expectations communicated
- [ ] Technical risks identified and mitigation plans drafted
- [ ] Cross-team dependencies clearly mapped
- [ ] Team technical knowledge and capability assessed

---

## Delivery Lead

### Role Summary
Delivery Leads focus on end-to-end delivery—schedules, dependencies, and removal of impediments. They ensure milestones are on track and work flows smoothly across teams.

### Responsibilities
- Track project milestones, deliverables, and timelines
- Coordinate across teams to identify and resolve blockers
- Manage the risk register and escalate issues
- Ensure release readiness and deployment coordination
- Monitor team capacity and workload balance
- Facilitate daily standups and weekly syncs

### Goals
- Deliver committed milestones on time
- Maintain clear visibility of progress and blockers
- Minimize unplanned delays and rework
- Foster cross-team collaboration and accountability

### Typical Communication
- Daily standups focused on progress and blockers
- Weekly milestone and risk reviews
- Cross-team coordination and dependency management
- Status updates to Project Manager and stakeholders

### Key Interactions
- **With Project Manager**: Report status, escalate risks, align on priorities
- **With Engineering Lead**: Identify technical blockers and resource constraints
- **With QA Lead**: Coordinate testing phases and acceptance criteria
- **With Release Manager**: Confirm deployment readiness and coordination
- **With Product Manager**: Clarify prioritization and acceptance criteria

### Handoff Checklist
- [ ] Milestone timeline and critical path defined
- [ ] Dependencies and blockers identified and tracked
- [ ] Daily standup cadence established
- [ ] Risk register created and reviewed weekly
- [ ] Release readiness criteria documented

---

## UX Researcher / Designer

### Role Summary
UX Researchers and Designers own user research, design decisions, and usability validation. They ensure features are discoverable, intuitive, and meet user needs.

### Responsibilities
- Conduct user research (interviews, surveys, usability testing)
- Create wireframes, prototypes, and design specifications
- Produce clear acceptance criteria for UX and interaction patterns
- Ensure accessibility considerations are addressed
- Validate designs with users and iterate based on feedback
- Document design decisions and design system contributions

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support burden
- Enable data-driven design decisions
- Build and maintain a consistent design language

### Typical Communication
- Design specs and clickable prototypes
- Accessibility checklists and guidelines
- User research findings and insights
- Design review and feedback sessions

### Key Interactions
- **With Product Manager**: Validate user needs and design direction
- **With Developers**: Provide detailed design specs and component libraries
- **With QA**: Define UX acceptance criteria and test scenarios
- **With Support/Customer Success**: Gather feedback on usability and pain points
- **With Stakeholders**: Present user research and design rationale

### Handoff Checklist
- [ ] User research conducted and findings documented
- [ ] High-fidelity prototypes or wireframes completed
- [ ] Accessibility audit performed (WCAG compliance)
- [ ] Design system components defined
- [ ] Dev handoff: clickable prototype + API specs + accessibility checklist

---

## DevOps / Platform Engineer

### Role Summary
DevOps and Platform Engineers ensure reliable CI/CD pipelines, infrastructure, and observability for the project. They enable rapid, safe deployments and system reliability.

### Responsibilities
- Design and maintain CI/CD pipelines (automated testing, linting, deployment)
- Configure and manage infrastructure, containers, and cloud resources
- Set up monitoring, alerting, and observability (logs, metrics, traces)
- Own rollback and incident runbooks related to infrastructure
- Document deployment procedures and troubleshooting guides
- Support incident response and post-mortem activities

### Goals
- Enable rapid, safe deployments with high confidence
- Minimize downtime and incident impact
- Provide observability and debugging capabilities
- Reduce manual, error-prone deployment work

### Typical Communication
- Deployment pipeline status and CI/CD failures
- Infrastructure and scaling recommendations
- Incident alerts and post-mortem findings
- Runbook and troubleshooting documentation

### Key Interactions
- **With Engineering Lead**: Understand deployment requirements and SLO targets
- **With Release Manager**: Coordinate deployment windows and rollback plans
- **With Developers**: Troubleshoot CI/CD failures and environment issues
- **With QA**: Support test environment setup and data management
- **With Support/On-call**: Provide incident response and runbooks

### Handoff Checklist
- [ ] CI/CD pipeline automated and documented
- [ ] Monitoring and alerting configured
- [ ] Deployment and rollback runbooks created
- [ ] Infrastructure-as-Code documented
- [ ] Incident response playbooks drafted

---

## Data Analyst / Analytics Lead

### Role Summary
Data Analysts define success metrics and measurement approaches for features. They enable data-driven decisions and provide insights on feature adoption and impact.

### Responsibilities
- Work with Product Manager to define success metrics and KPIs
- Design instrumentation and event tracking strategy
- Create dashboards and reporting tools for stakeholders
- Validate hypotheses through A/B testing and experiments
- Analyze feature adoption, performance, and business impact
- Provide actionable insights for prioritization and iteration

### Goals
- Enable clear, measurable understanding of feature impact
- Support data-driven prioritization and decision-making
- Identify opportunities for optimization and improvement
- Build trust through transparent, accessible analytics

### Typical Communication
- Success metrics and instrumentation specs
- Dashboard creation and metric definitions
- Weekly analytics reviews and insights
- Experiment results and findings reports

### Key Interactions
- **With Product Manager**: Define KPIs and success metrics; analyze feature impact
- **With Developers**: Clarify instrumentation requirements and event schema
- **With Release Manager**: Track launch metrics and post-release performance
- **With Stakeholders**: Present insights and support data-driven decisions
- **With Support/Customer Success**: Gather qualitative feedback to complement metrics

### Handoff Checklist
- [ ] Success metrics and KPIs defined
- [ ] Instrumentation plan and event schema documented
- [ ] Dashboards and reporting tools created
- [ ] Baseline metrics captured (pre-launch)
- [ ] Post-launch analysis plan established

---

## Release Manager

### Role Summary
Release Managers orchestrate release activities and ensure all pre- and post-release checks are completed. They minimize release risk and communicate changes to stakeholders.

### Responsibilities
- Schedule and coordinate release windows
- Verify pre-release checklist completion (testing, security, docs, etc.)
- Coordinate deployment with DevOps and Engineering
- Execute post-deployment verification and smoke tests
- Draft and publish release notes
- Manage rollback procedures if issues arise
- Communicate releases to support and stakeholders

### Goals
- Execute zero-impact releases with high confidence
- Minimize release cycles and time-to-market
- Ensure clear communication to all stakeholders
- Enable rapid incident response if issues occur

### Typical Communication
- Release notes and feature summaries
- Pre-release checklists and go/no-go decisions
- Deployment status and post-release verification
- Incident alerts and rollback decisions

### Key Interactions
- **With Delivery Lead**: Confirm release readiness and final approval
- **With DevOps**: Coordinate deployment and rollback execution
- **With QA**: Verify testing completion and accept quality gates
- **With Engineering Lead**: Address last-minute issues and blockers
- **With Support/Customer Success**: Brief on changes and coordinate customer communication
- **With Data Analyst**: Capture post-launch metrics and performance

### Handoff Checklist
- [ ] Pre-release checklist completed and signed off
- [ ] Testing, security, and compliance sign-offs obtained
- [ ] Release notes drafted and reviewed
- [ ] Rollback plan and runbook documented
- [ ] Support and stakeholder notification plan confirmed
- [ ] Post-deployment monitoring and verification plan ready

---

## Support / Customer Success Liaison

### Role Summary
Support and Customer Success Liaisons represent support-facing insights and post-release customer feedback. They help prioritize issues and ensure customer problems are quickly surfaced and addressed.

### Responsibilities
- Triage incoming customer issues and support tickets
- Provide detailed reproduction steps and impact summaries
- Help prioritize hotfixes and urgent bug fixes
- Gather qualitative customer feedback on usability and pain points
- Communicate product changes and workarounds to customers
- Support incident response and blameless post-mortems
- Identify patterns in customer issues for product improvement

### Goals
- Reduce customer-facing issues and support burden
- Enable rapid triage and prioritization of urgent issues
- Provide valuable feedback to product and engineering teams
- Maintain customer trust through transparent communication

### Typical Communication
- Issue triage summaries and impact assessments
- Customer feedback and emerging patterns
- Product update announcements and workarounds
- Post-incident communication and follow-up

### Key Interactions
- **With Product Manager & Engineering**: Escalate urgent issues and customer feedback
- **With QA**: Provide reproduction steps and quality validation
- **With DevOps & Release Manager**: Support incident triage and post-deployment monitoring
- **With UX/Design**: Share usability pain points and feature requests
- **With Developers**: Provide context on customer-reported bugs
- **With Stakeholders**: Communicate on service health and customer impact

### Handoff Checklist
- [ ] Issue triage process documented
- [ ] Customer feedback channel established
- [ ] Escalation path for urgent issues defined
- [ ] Post-incident communication template created
- [ ] Customer-facing documentation and FAQs updated

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Key Interactions" and "Handoff Checklists" to understand cross-functional dependencies and responsibilities.
- When running projects, ensure all roles are clearly assigned and responsibilities are distributed to avoid single-person dependencies.
