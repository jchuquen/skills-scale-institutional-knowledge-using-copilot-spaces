# OctoAcme Project Management Docs

This folder collects OctoAcme's project management process documents and provides a concise orientation for new teammates and contributors. Use these docs as the canonical, versioned source for how we plan, execute, communicate, and improve projects at OctoAcme.

OctoAcme runs projects through a lightweight, iterative lifecycle: Initiation to validate the problem and success metrics; Planning to create a prioritized backlog, release plan, and Definition of Done; Execution to build, review, and verify small, testable increments; Release and Deployment with rollout and rollback plans; and Close with retrospectives to capture learnings. Key artifacts (Project One‑pager, backlog items with acceptance criteria, risk register, release notes) and a visible project board help keep work aligned and traceable.

Roles and responsibilities are explicit to maintain clear ownership: Product Managers own the vision, prioritization, and success metrics; Project Managers coordinate delivery, schedule, risks, and communications; Developers implement and test; QA validates acceptance; and Stakeholders provide input and approvals. This separation ensures accountability for both outcome (PdM) and delivery (PM) while enabling cross-functional collaboration.

Communication is structured and predictable: daily standups for progress and blockers, a weekly delivery sync for progress and risks, demos at sprint/milestone ends, and monthly stakeholder updates. Quality assurance is integrated into the pipeline through unit/integration tests, CI security scanning, E2E smoke tests before releases, PR conventions (small PRs, linked issues, CI checks), and a Definition of Done. Retrospectives convert findings into tracked action items to continuously improve the process.

Docs in this folder:
- octoacme-project-management-overview.md
- octoacme-project-initiation.md
- octoacme-project-planning.md
- octoacme-execution-and-tracking.md
- octoacme-risks-and-communication.md
- octoacme-release-and-deployment.md
- octoacme-retrospective-and-continuous-improvement.md
- octoacme-roles-and-personas.md

How to contribute
- Use the ".github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml" issue template to propose changes.
- For updates: open an issue, discuss, then create a branch, add the change, and open a PR that references the issue (e.g., "Relates to #2").
- Add reviewers from the team and move the change through the usual PR + CI checks before merging.

> Tip: Add any new process docs under this folder and update this README with links to keep the set of docs discoverable.
