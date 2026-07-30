# OctoAcme Project Management Docs

This folder contains OctoAcme's project management process documentation and a short, shareable summary to help new teammates quickly understand how we plan, run, and improve projects.

## Brief summary of OctoAcme project management processes

OctoAcme follows a lightweight, iterative project management lifecycle that moves work from initiation through planning, execution, release, and continuous improvement. Initiation centers on a concise Project One-pager that captures the problem, objectives, success metrics, stakeholders, and a high-level timeline to decide whether to proceed to planning. Planning breaks approved initiatives into shippable increments: prioritized backlog items with acceptance criteria, estimates (T-shirt sizing or story points), a Definition of Done, and a release/milestone map. The project docs emphasize capturing dependencies and risks early in a Risk Register so they can be monitored and escalated in regular syncs.

Execution is run through explicit workflows: a project board with Backlog → Ready → In Progress → In Review → QA → Done, a small-PR-first pull request process (with issue links, acceptance criteria, CI checks, and at least one approval), and a clear escalation path for blockers (team → PM → Product Lead → Sponsor). Team rhythm is defined to keep momentum and visibility: short daily standups (15 minutes) for blockers and progress, weekly delivery syncs to surface updates and risks, sprint demos/reviews at milestone ends, and regular PM+PdM alignment meetings. Backlog and sprint planning are timeboxed, and work is pulled only when it meets the Definition of Done and has clear acceptance criteria.

Roles and responsibilities are codified so people know where ownership and decisions live. Product Managers own the problem definition, success metrics, and backlog priorities; Project Managers coordinate timelines, communications, and risk management; Developers implement features, write tests, and participate in reviews; QA/testing roles validate acceptance criteria and perform manual checks where required. These personas are used consistently in templates and artifacts (one-pagers, backlog item templates, decision logs) to reduce ambiguity about who does what and when to escalate decisions or risks.

Quality assurance and release discipline are tightly integrated into the process. Code quality is enforced through CI (unit and integration tests, linting, security scans) and a preference for small PRs to reduce review friction. Testing expectations include unit tests for logic, integration tests for cross-component behavior, and end-to-end smoke tests for critical flows before releases; manual QA is used when necessary for feature acceptance. Releases follow a checklist (pre-release checks, draft release notes, rollback plans, smoke tests on staging, automated deployment pipelines when possible), and post-release activities include verifications, incident playbooks, and retrospectives that convert learnings into backlog action items for continuous improvement.

## Process documents (links)

- Project Management Overview: docs/octoacme-project-management-overview.md  
- Project Initiation Guide: docs/octoacme-project-initiation.md  
- Project Planning: docs/octoacme-project-planning.md  
- Execution & Tracking: docs/octoacme-execution-and-tracking.md  
- Risk Management & Communication: docs/octoacme-risks-and-communication.md  
- Release & Deployment Guide: docs/octoacme-release-and-deployment.md  
- Retrospective & Continuous Improvement: docs/octoacme-retrospective-and-continuous-improvement.md  
- Roles & Personas: docs/octoacme-roles-and-personas.md
