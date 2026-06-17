# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management process library. This README provides an overview of OctoAcme's approach to managing projects and links to detailed process documents for each phase of the project lifecycle.

## Project Management Approach

OctoAcme employs a structured, customer-first approach to project management that emphasizes iterative delivery and data-informed decision-making. The project lifecycle consists of five key phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**.

During initiation, teams validate business needs and establish stakeholder alignment through a lightweight Project One-pager that defines the problem statement, objectives, success metrics, and initial timeline. Once approved, the planning phase transforms this vision into an actionable backlog with clear acceptance criteria, estimated scope, defined dependencies, and a release plan.

Execution is driven by a consistent team rhythm that includes daily standups, weekly delivery syncs, and sprint-based iterations using GitHub Projects. Small pull requests (≤400 lines when possible) are encouraged, with mandatory automated testing, linting, and security scanning in CI before review. Quality is emphasized through unit tests, integration tests, end-to-end smoke tests, and manual QA for feature acceptance.

OctoAcme defines clear ownership through four core personas: Project Managers (coordinate delivery, schedules, and communications), Product Managers (define outcomes and prioritize backlog), Developers (implement and test features), and QA/Testing (validate acceptance criteria). Throughout execution, risks are actively managed through a Risk Register with escalation paths, and communication is consistent through weekly syncs and standardized status templates.

Release management follows a structured checklist including acceptance criteria validation, passing CI/security scans, smoke testing, and a documented rollback plan. Finally, the organization embraces continuous improvement through timeboxed retrospectives held after each sprint or milestone, where teams discuss what went well, identify improvements, and track action items with clear owners and success criteria.

## Process Documents

### [Project Management Overview](octoacme-project-management-overview.md)
Introduction to OctoAcme's project management approach, core roles, key artifacts, and high-level lifecycle. **Start here** to understand the framework and principles.

### [Project Initiation Guide](octoacme-project-initiation.md)
Guidance for the initiation phase, including how to validate business needs, align stakeholders, and create a Project One-pager. Use this to kick off new projects or feature proposals.

### [Project Planning](octoacme-project-planning.md)
Detailed process for turning an approved initiative into an actionable backlog and plan. Covers kickoff, backlog creation, estimation, Definition of Done, dependency management, and release planning.

### [Execution & Tracking](octoacme-execution-and-tracking.md)
Guidance for day-to-day execution, including team rhythm, PR workflows, quality and testing practices, metrics tracking, and blocker escalation.

### [Release & Deployment Guide](octoacme-release-and-deployment.md)
Standardized approach to releasing features to production, including release types, pre-release requirements, deployment checklist, rollback playbook, and release notes template.

### [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
Framework for capturing learnings after sprints and milestones, running effective retrospectives, and converting action items into measurable improvements.

### [Risk Management & Communication](octoacme-risks-and-communication.md)
Processes for identifying, assessing, monitoring, and mitigating risks. Includes Risk Register template, stakeholder communication strategies, and escalation paths.

### [Roles & Personas](octoacme-roles-and-personas.md)
Detailed descriptions of the core personas used throughout OctoAcme projects: Project Managers, Product Managers, Developers, and QA/Testing. Reference this to understand role responsibilities and communication patterns.

## How to Use These Docs

1. **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md) to understand roles and the project lifecycle.

2. **Starting a new project?** Use the [Project Initiation Guide](octoacme-project-initiation.md) and the Project One-pager template to validate the initiative.

3. **Planning a project?** Follow [Project Planning](octoacme-project-planning.md) to create your backlog, estimates, and release plan.

4. **During execution?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) for team rhythm, PR conventions, and quality standards.

5. **Managing risks or communicating with stakeholders?** Use [Risk Management & Communication](octoacme-risks-and-communication.md) for templates and processes.

6. **Preparing a release?** Check [Release & Deployment Guide](octoacme-release-and-deployment.md) for checklists and playbooks.

7. **Completing a sprint or milestone?** Run a retrospective using [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md).

## Single Source of Truth

These documents serve as the **single source of truth** for OctoAcme project management practices. When creating project-specific documentation, link to the relevant process documents in `docs/` to ensure consistency and reduce duplication.

For Copilot Spaces users: Add these documents to your `.copilot/` folder to provide context-specific guidance aligned with OctoAcme practices.

---

**Last Updated:** [Current Date]  
**Maintained By:** OctoAcme Project Management Team
