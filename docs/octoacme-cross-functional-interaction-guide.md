# OctoAcme Cross-Functional Interaction Guide

## Purpose
This guide clarifies how different personas collaborate, what handoffs look like, and how to prevent common gaps or bottlenecks in project execution.

## Collaboration Map by Project Phase

### Initiation Phase
**Primary roles:** Product Manager, Project Manager, Stakeholders

| From | To | Handoff | Acceptance Criteria |
|------|-----|---------|--------------------|
| Product Manager | Project Manager | Problem statement, success metrics, stakeholder list | PM understands business case and can socialize with sponsors |
| Product Manager | Stakeholders | One-pager and timeline | Stakeholders aligned on priority and willing to commit resources |
| Project Manager | Delivery Lead | Initial timeline and resource needs | Delivery Lead can assess capacity and identify gaps |

---

### Planning Phase
**Primary roles:** Product Manager, Project Manager, Engineering Lead, Delivery Lead, UX Researcher

| From | To | Handoff | Acceptance Criteria |
|------|-----|---------|--------------------|
| Product Manager | Engineering Lead | Requirements and acceptance criteria | Eng Lead can estimate scope and identify technical trade-offs |
| Engineering Lead | Project Manager | Technical architecture, capacity plan, risk register | PM can finalize timeline and adjust scope if needed |
| UX Researcher | Developers | Design specs, prototypes, accessibility checklist | Devs understand design intent and can build to spec |
| Delivery Lead | All teams | Release plan, milestone dates, definition of done | All teams understand expectations and can plan sprints |
| Project Manager | Stakeholders | Release plan and feature roadmap | Stakeholders know what to expect and when |

---

### Execution Phase
**Primary roles:** All roles

| From | To | Handoff | Acceptance Criteria |
|------|-----|---------|--------------------|
| Developers | QA | Feature code and test plan | QA can execute tests and validate acceptance criteria |
| Developers | Engineering Lead | Code for review | Code meets quality standards and design expectations |
| QA | Developers | Defect reports with reproduction steps | Devs can quickly reproduce and fix issues |
| Support Liaison | Product Manager | Customer feedback and emerging patterns | PM prioritizes issues and communicates trade-offs |
| Data Analyst | All teams | Metrics dashboards and weekly insights | Teams understand impact and can adjust approach |
| Delivery Lead | Project Manager | Daily standup summary and blockers | PM aware of status and can help unblock |

---

### Release & Deployment Phase
**Primary roles:** Release Manager, DevOps, QA, Engineering Lead, Product Manager

| From | To | Handoff | Acceptance Criteria |
|------|-----|---------|--------------------|
| QA | Release Manager | Test sign-off and known issues list | Release Manager can confirm readiness and plan communication |
| Engineering Lead | Release Manager | Code freeze and any late-breaking changes | Release Manager understands what's in the release |
| Release Manager | DevOps | Go-ahead for deployment | DevOps executes deployment following runbook |
| DevOps | Release Manager | Post-deployment verification results | Release Manager can confirm success and publish announcements |
| Release Manager | Stakeholders & Support | Release notes and customer communication | Stakeholders and customers understand what changed |
| Data Analyst | Release Manager | Baseline metrics captured | Release Manager can track post-launch impact |

---

### Post-Release & Retrospective Phase
**Primary roles:** All roles

| From | To | Handoff | Acceptance Criteria |
|------|-----|---------|--------------------|
| Delivery Lead | All teams | Retrospective insights and action items | Teams identify improvements and commit to changes |
| Data Analyst | Product Manager | Post-launch metrics and impact analysis | PM understands feature adoption and next steps |
| Support Liaison | Product Manager | Customer feedback themes and issues | PM considers feedback in future prioritization |
| Project Manager | Stakeholders | Final status, metrics, and lessons learned | Stakeholders understand outcome and business impact |

---

## Common Handoff Failure Points

### 1. **Unclear Acceptance Criteria**
- **Problem:** Developers and QA have different interpretations of "done."
- **Prevention:** Product Manager and QA collaborate to define acceptance criteria BEFORE development starts.
- **Recovery:** Engineering Lead facilitates a sync between QA and Dev to align on expected behavior.

### 2. **Scope Creep During Development**
- **Problem:** Feature requests or "nice to haves" get added without re-planning.
- **Prevention:** Delivery Lead enforces change management process and requires PM approval for scope changes.
- **Recovery:** Project Manager assesses impact on timeline and coordinates with stakeholders.

### 3. **Late Technical Risks Surfaced**
- **Problem:** Architecture limitations discovered during implementation cause delays.
- **Prevention:** Engineering Lead performs architecture review during planning phase and maintains risk register.
- **Recovery:** Engineering Lead and Project Manager quickly assess and escalate; adjust timeline or reduce scope.

### 4. **Poor Quality Makes it to Production**
- **Problem:** QA testing incomplete or insufficient; defects slip through.
- **Prevention:** QA Lead defines test plan and acceptance criteria upfront; Engineering Lead enforces code review standards.
- **Recovery:** DevOps and Release Manager execute rollback; post-incident retrospective identifies gaps.

### 5. **Unclear Ownership of Deployment**
- **Problem:** Confusion about who is responsible for deployment; deployment is delayed or executed incorrectly.
- **Prevention:** Release Manager clarifies roles and runbook during pre-release sync; all parties sign off.
- **Recovery:** Release Manager and DevOps quickly communicate and execute coordinated response.

### 6. **Customer Impact Not Communicated**
- **Problem:** Support and customers surprised by changes; increase in support tickets.
- **Prevention:** Release Manager drafts release notes early; Support Liaison reviews and plans customer communication.
- **Recovery:** Support Liaison quickly publishes FAQ or workarounds; escalates customer impact to PM.

---

## Weekly Cross-Functional Sync Template

### Agenda (45 min)
1. **Execution Status** (10 min) — Delivery Lead reviews progress, milestones, blockers
2. **Risk Register Review** (10 min) — Project Manager and Engineering Lead review open risks and mitigation status
3. **Dependency Check** (10 min) — Delivery Lead flags cross-team dependencies and escalates as needed
4. **Metrics & Impact** (10 min) — Data Analyst shares weekly insights and emerging patterns
5. **Next Steps & Decisions** (5 min) — Clarify action items and confirm decisions

### Attendees
- Product Manager
- Project Manager
- Delivery Lead
- Engineering Lead
- QA Lead (or representative)
- Release Manager (as needed)
- Data Analyst (as needed)

---

## Escalation Path for Cross-Functional Issues

**Level 1: Team Lead Sync**
- Delivery Lead convenes relevant leads (Engineering, QA, DevOps)
- Attempt to resolve within 24 hours
- Example: Deployment blocker due to infrastructure issue

**Level 2: PM Escalation**
- Project Manager convenes with Product Manager, Engineering Lead, and Stakeholder
- Assess impact on timeline and scope
- Make go/no-go or scope adjustment decision
- Example: Major technical risk that impacts timeline

**Level 3: Sponsor Escalation**
- Project Manager escalates to Sponsor and Executive Steering Committee
- Assess business impact and strategic implications
- Make strategic decisions (green-light despite risk, pivot, pause, etc.)
- Example: Release timing impacts business-critical deadline

---

## Handoff Checklist Template

Use this template when transitioning work between phases or personas:

```
## Handoff: [From Role] → [To Role]
Date: [Date]
Project: [Project Name]

### What's Being Handed Off
- [ ] [Deliverable 1]
- [ ] [Deliverable 2]
- [ ] [Documentation]

### Acceptance Criteria
- [ ] [Criterion 1]
- [ ] [Criterion 2]
- [ ] [Recipient understands expectations]

### Known Risks or Assumptions
- [Risk 1]
- [Assumption 1]

### Questions or Clarifications
- [From side]: [Question]
- [To side]: [Answer]

### Sign-Off
- [From Role]: _______ Date: _____
- [To Role]: _______ Date: _____
```

---

## Integration with GitHub Project Board

When using GitHub Projects, include interaction and handoff information in:
- **Issue descriptions:** Link to persona definitions and clarify owner
- **Labels:** Use labels to indicate handoff points (e.g., `ready-for-qa`, `ready-for-release`)
- **Milestones:** Map milestones to collaboration phases (Initiation, Planning, Execution, Release, Retrospective)
- **Custom fields:** Track owner, dependent teams, and status of handoffs

---

## References
- [OctoAcme Personas](octoacme-roles-and-personas.md)
- [OctoAcme Execution & Tracking](octoacme-execution-and-tracking.md)
- [OctoAcme Release & Deployment](octoacme-release-and-deployment.md)
- [OctoAcme Risks & Communication](octoacme-risks-and-communication.md)
