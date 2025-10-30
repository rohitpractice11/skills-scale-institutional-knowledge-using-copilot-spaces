# OctoAcme Project Management Docs

This README is the central index for OctoAcme's project management process documentation. It provides a concise overview of how OctoAcme runs projects, the key workflows and roles involved, and direct links to the detailed process documents in this folder.

OctoAcme follows a lightweight, outcome-driven lifecycle that moves work through initiation, planning, execution, release, and retrospective stages. Initiation begins with a Project One‑pager that defines the problem, measurable success metrics, stakeholders, and a go/no‑go decision. During planning, approved initiatives are translated into a prioritized, estimated backlog with a clear Definition of Done, release plan, and risk register to ensure alignment and feasibility.

Day-to-day execution uses visible project boards and a disciplined Pull Request workflow. Teams operate with a board (Backlog → Ready → In Progress → In Review → QA → Done), timeboxed iterations or milestones, daily standups for blockers and progress, and weekly delivery syncs for demos and risk conversations. Pull requests should be small, reference the related issue and acceptance criteria, and pass CI (tests, linting, security scans) before requesting review; at least one approval is required before merge. Blocker escalation scales from team triage to PM, Product Lead, and sponsor-level involvement for business-critical issues.

Roles are explicit: Project Managers coordinate delivery, schedules, risks, and communications; Product Managers define outcomes, prioritize the backlog, and measure success; Developers implement and maintain tests and docs; QA validates acceptance criteria and quality; stakeholders provide input and approvals. Releases follow a pre-release checklist (passing CI, release notes, rollback plan, smoke tests) and have documented deployment and rollback steps. Retrospectives after milestones or incidents capture learnings and create tracked action items to drive continuous improvement.

## Process documentation (links)
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## How to use this README
- Use this page as the single source of truth for navigating OctoAcme process docs.
- When updating a process doc, add a short note here referencing the change.
- For Copilot Spaces: adding process-specific docs into `.copilot/` makes them available as context for Copilot sessions.

## Acceptance criteria (from issue #2)
- [ ] Content aligns with existing process docs
- [ ] Update improves clarity or closes a documented gap
- [ ] Proposed content has been reviewed with stakeholders (if needed)
