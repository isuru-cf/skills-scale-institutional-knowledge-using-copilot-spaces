# OctoAcme Project Management Docs

Welcome to the documentation hub for OctoAcme's project management processes. This README provides (1) an index with direct links to all the key documents in the `docs/` folder and (2) a brief overview of how OctoAcme manages projects end-to-end.

## Project Management Approach (Brief Overview)

OctoAcme manages cross-functional delivery through a lightweight, repeatable project lifecycle with clear artifacts and decision gates. Work typically moves from **Initiation** (validate the problem, define a SMART objective, success metrics, stakeholders, an initial timeline, and risks) into **Planning** (kickoff, prioritized backlog with acceptance criteria, estimates, Definition of Done, dependencies, and a release/milestone map). Execution then proceeds iteratively with a strong bias toward shipping in small increments, tracking progress against milestones, and continuously updating shared project artifacts such as the one-pager/charter, backlog, risk register, and retrospective actions.

Roles are intentionally explicit to reduce ambiguity. A **Project Manager (PM)** coordinates delivery, schedules, risks, and communications; a **Product Manager (PdM)** defines outcomes, prioritizes the backlog, and measures success; **Developers** design and implement solutions with tests and documentation while collaborating on estimation and reviews; **QA/Testing** validates acceptance criteria and quality; and **Stakeholders** provide input and approvals. This role clarity is reinforced by the expectation of clear ownership for backlog items, risks, and action items (including named owners and due dates), enabling dependable handoffs and accountability throughout the project.

Communication is structured around a consistent team rhythm and stakeholder transparency. The delivery team uses short **daily standups** to surface blockers and dependencies, a **weekly delivery sync** to show progress, updates, and flagged risks, and **demo/review** checkpoints at the end of each sprint or milestone. Stakeholder updates are supported with a single source of truth (for example, a project README/status doc) and a weekly status template covering progress, next steps, risks/blockers, and decisions needed. Blockers escalate through defined levels—from team-level triage to PM escalation to the Product Lead and dependent teams, and then to sponsor-level escalation for business-impacting issues.

Quality assurance is embedded in both day-to-day engineering workflow and release discipline. OctoAcme emphasizes a PR-based workflow with **small pull requests** (<= 400 lines when possible), issue links and acceptance criteria in PR descriptions, CI checks (automated tests, linting, and security scanning) before requesting review, and at least one approval before merging (or a team-defined policy). Testing expectations include **unit tests for new logic**, **integration tests where applicable**, and **end-to-end smoke tests for critical flows**—especially before releases—plus manual QA for feature acceptance when needed. Releases also require release notes, a rollback/mitigation plan, staged deployment with smoke tests, post-deploy verification, and continuous improvement through retrospectives with owned action items.

## Documentation Index

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

> For process updates or addition requests, use the process improvement issue template in `.github/ISSUE_TEMPLATE/`.
