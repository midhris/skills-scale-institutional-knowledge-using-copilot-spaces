# OctoAcme Project Management Docs

Welcome to OctoAcme's centralized project management documentation. These docs codify our approach to running projects, making it easy for new and existing team members to understand our processes, roles, and best practices.

## Overview

OctoAcme runs projects using a lifecycle-driven, outcome-focused approach: Initiation (validate the business need, align stakeholders, and produce a project one‑pager), Planning (create a prioritized backlog, define acceptance criteria and a Definition of Done), Execution (iterate in short increments with CI and PR reviews), Release (deploy safely with smoke tests, rollback plans, and release notes), and Retrospective (capture learnings and convert them into tracked improvements). The emphasis is on small, testable increments, data-informed decision making, and keeping a single source of truth for project status and artifacts.

## Key Workflows

Workflows and key practices are standardized across the project. Teams operate a project board with Backlog → Ready → In Progress → In Review → QA → Done, and use a pull request workflow that encourages small PRs with clear acceptance criteria, automated tests and security scans in CI, and at least one approval before merging. Backlog items follow a template (title, description, acceptance criteria, estimate, owner) and planning sessions are timeboxed to the team sprint cadence with capacity-aware commitment.

## Personas & Communication

Roles and communication are explicit: each project names a Project Manager (PM) and a Product Lead (PdM), with developers and QA responsible for implementation and verification. The standard communication cadence includes daily standups, weekly delivery syncs, PM–PdM alignment, and monthly stakeholder updates; risks are tracked in a Risk Register and incident communications follow a templated triage/notification/playbook flow.

## Quality Assurance & Releases

Quality assurance and release discipline are built into the workflow. Developers add unit and integration tests for new logic, critical flows have end‑to‑end smoke checks, CI runs security scanning and linting, and manual QA is used for feature acceptance as required. Releases require passing CI, documented release notes, and a rollback plan; deployments follow a staging → production verification checklist and are followed by a post‑release verification and retrospective to capture action items.

## Core Principles
- Customer-first: prioritize customer value and usability
- Iterative delivery: deliver small, testable increments
- Clear ownership: each project has named roles and accountability
- Data-informed: measure impact and iterate based on evidence
- Psychological safety: encourage feedback and learning

## Process Documentation (in this folder)
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

## Quick Reference
- Starting a new project? → Begin with [Project Initiation](./octoacme-project-initiation.md)
- Need to plan deliverables? → See [Project Planning](./octoacme-project-planning.md)
- Tracking daily progress? → Check [Execution & Tracking](./octoacme-execution-and-tracking.md)
- Managing risks? → Review [Risk Management & Communication](./octoacme-risks-and-communication.md)
- Releasing to production? → Follow [Release & Deployment](./octoacme-release-and-deployment.md)
- Learning from delivery? → Run a [Retrospective](./octoacme-retrospective-and-continuous-improvement.md)

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
- Use the issue template ".github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml" to request content changes or additions.
