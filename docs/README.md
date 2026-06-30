# OctoAcme Project Management Docs

This is the central index for OctoAcme's project management process documentation. Whether you're a new contributor getting oriented or a returning team member looking for a specific process, start here.

## Overview

OctoAcme uses a lightweight, end-to-end project management approach that covers the full lifecycle from initiation through planning, execution, release, and retrospective improvement. Projects begin with a one-pager that defines the problem, goals, success metrics, stakeholders, timeline, risks, and resource needs. Once a project is approved, the team moves into planning by breaking work into prioritized backlog items with acceptance criteria, estimates, dependencies, milestones, and a defined Definition of Done. This creates a structured but iterative delivery model centered on small, testable increments.

The core roles in OctoAcme are clearly defined and collaborative. Project Managers coordinate delivery, timelines, risks, documentation, and stakeholder communication. Product Managers define outcomes, prioritize the backlog, and ensure work delivers customer and business value. Developers implement features, contribute to estimates and design, maintain tests and documentation, and help surface technical risks. QA or testing contributors validate acceptance criteria and overall quality, while stakeholders provide inputs, approvals, and ongoing feedback throughout the lifecycle.

Execution is managed through a regular team rhythm and visible workflows. Teams use a project board with stages such as Backlog, Ready, In Progress, In Review, QA, and Done to track work. Daily or twice-weekly standups, weekly delivery or PM/Product syncs, sprint demos, and monthly stakeholder updates help maintain alignment and surface blockers early. Risks and dependencies are tracked in a risk register, reviewed regularly, and escalated through a clear path from team-level triage to PM, Product Lead, and sponsor when business impact increases. Communication is designed to rely on a single source of truth and consistent status updates, including weekly progress, next steps, blockers, and decision needs.

Quality assurance is embedded throughout delivery and release rather than treated as a final step. OctoAcme expects unit tests for new logic, integration tests where needed, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance when appropriate. PR workflows emphasize small pull requests, issue linkage, acceptance criteria, passing CI, and at least one approval before merge. Before release, teams confirm acceptance criteria are met, CI and security checks pass, release notes and rollback plans are prepared, and post-deployment verification is completed. After sprints, milestones, or incidents, retrospectives capture what worked, what should improve, and concrete action items that feed back into the backlog for continuous improvement.

## Documentation Index

| Document | Description |
|---|---|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level overview of OctoAcme's project management approach |
| [Project Initiation](octoacme-project-initiation.md) | How to kick off a new project, including the one-pager template and approval process |
| [Project Planning](octoacme-project-planning.md) | Backlog creation, estimation, milestones, and Definition of Done |
| [Execution and Tracking](octoacme-execution-and-tracking.md) | Team rhythms, project board workflow, and progress tracking |
| [Risks and Communication](octoacme-risks-and-communication.md) | Risk register, escalation paths, and communication cadence |
| [Release and Deployment](octoacme-release-and-deployment.md) | Release checklist, deployment process, and post-deployment verification |
| [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Running retrospectives and feeding improvements back into the backlog |
| [Roles and Personas](octoacme-roles-and-personas.md) | Definitions and responsibilities for each role on a project team |

## Keeping This Index Updated

When new process documentation is added to the `docs/` folder, please update this README to include a link and short description for the new file. This index is the entry point for contributors and new team members, so keeping it current ensures everyone can find what they need.
