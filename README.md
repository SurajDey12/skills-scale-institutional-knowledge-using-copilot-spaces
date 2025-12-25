# OctoAcme Project Management Docs

This README introduces OctoAcme’s approach to project management and provides links to the living process documentation in this folder.

OctoAcme delivers projects through a clear lifecycle: initiation, planning, execution, release, and retrospective. Each stage is supported by lightweight, repeatable artifacts (Project One-pager, roadmap/release plan, sprint backlog, Definition of Done, and a Risk Register). Projects begin with a concise initiation that confirms success metrics, stakeholders, and initial risks, moving to planning only after priority and team availability are confirmed. Planning produces a prioritized, estimated backlog, explicit acceptance criteria, and a release milestone map that guides execution.

Workflows emphasize small, shippable increments and visible boards: teams use a project board with Backlog → Ready → In Progress → In Review → QA → Done and follow a pull-request-first workflow (small PRs where possible, include issue link and acceptance criteria, run CI/lint/tests, and require approvals). Release management is standardized by type (patch, minor, major) and checklist-driven, including staging smoke tests, production verification, rollback plans, and clear communications. Reporting and dashboards surface velocity, burndown, and success metrics tied to the Project One-pager.

Roles and communication are explicit: Project Managers coordinate delivery and risks; Product Managers define outcomes and prioritize the backlog; Developers implement and test; QA validates acceptance; and Stakeholders provide input and approvals. Team rhythm includes daily standups, weekly delivery syncs, sprint demos, PM+PdM alignment sessions, and monthly stakeholder updates. Quality is built in with CI gating, unit/integration/end-to-end tests, security scans, and manual QA when needed. Retrospectives turn learnings into tracked actions so processes continuously improve and institutional knowledge scales across teams.

## Docs Index

- [Project Management Overview](octoacme-project-management-overview.md)  
- [Project Initiation Guide](octoacme-project-initiation.md)  
- [Project Planning Guide](octoacme-project-planning.md)  
- [Execution & Tracking](octoacme-execution-and-tracking.md)  
- [Risk & Communication](octoacme-risks-and-communication.md)  
- [Release & Deployment Guide](octoacme-release-and-deployment.md)  
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)  
- [Roles & Personas](octoacme-roles-and-personas.md)

Each document contains templates, checklists, and step-by-step guidance to help teams onboard quickly, reduce single-person dependencies, and run repeatable projects.
