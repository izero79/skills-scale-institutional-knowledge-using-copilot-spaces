# OctoAcme Project Management Documentation

## Overview
OctoAcme follows a structured, iterative project management approach designed to deliver customer value safely and predictably. The documentation in this folder collects initiation, planning, execution, release, risk, and continuous improvement guidance so teams can find consistent practices, clear roles, and concrete artifacts for running projects.

## Project Lifecycle
1. Initiation — define the problem, align stakeholders, and validate the need with a Project One‑pager.
2. Planning — break approved work into shippable backlog items with acceptance criteria, estimates, and a release plan.
3. Execution — implement in small increments using the project board and PR workflow, run tests and CI, and track progress.
4. Release — follow pre‑release checks, automated deployment pipelines where possible, and post‑deploy verification and rollback plans.
5. Retrospective — capture learnings and convert them to tracked action items for continuous improvement.

## Core Principles
- Customer-first: prioritize value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: named PM and Product Lead for each project.
- Data-informed: measure impact and iterate.
- Psychological safety: encourage feedback and learning.

## Quick Links (docs/)
- Project Management Overview — docs/octoacme-project-management-overview.md
- Project Initiation Guide — docs/octoacme-project-initiation.md
- Project Planning — docs/octoacme-project-planning.md
- Execution & Tracking — docs/octoacme-execution-and-tracking.md
- Risks & Communication — docs/octoacme-risks-and-communication.md
- Release & Deployment — docs/octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement — docs/octoacme-retrospective-and-continuous-improvement.md
- Roles & Personas — docs/octoacme-roles-and-personas.md

## Brief Process Summary
OctoAcme runs projects with an iterative, outcome-focused workflow that begins with a lightweight initiation step (a Project One‑pager that defines the problem, success metrics, stakeholders, and rough timeline) and moves into planning where work is decomposed into shippable backlog items with acceptance criteria and a Definition of Done. Execution is managed on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and emphasizes small, reviewable increments (PRs targeted at ≤400 lines) that link back to issues, include clear acceptance criteria, and pass automated CI checks before review. Releases are classified (patch/minor/major) and require pre-release checks (passing CI/security scans, release notes, rollback plans) with an explicit deployment and post‑deploy verification checklist.

Roles and responsibilities are explicit: Product Managers define outcomes and prioritize the backlog, Project Managers coordinate schedules, risks, and communications, Developers implement and test features, QA validates acceptance criteria, and Stakeholders provide approvals and input. The docs encourage clear ownership for artifacts (one‑pager, roadmap, risk register, release notes) and call out specific deliverables at each lifecycle stage (initiation, planning, execution, release, close/retrospective).

Communication and quality practices are embedded into cadence and tooling: daily standups for progress and blockers, weekly delivery syncs and PM+PdM alignments, regular demos at the end of sprints/milestones, and monthly stakeholder updates. Risk management uses a simple register (ID, impact, likelihood, owner, mitigation) with defined escalation paths (team → PM → Product Lead → Sponsor) and incident communication templates. Quality assurance includes unit and integration tests, end‑to‑end smoke tests for critical flows, security scanning in CI, and manual QA when needed; retrospective action items become tracked issues to drive continuous improvement.

## Getting Started
- Start with the Project Management Overview then review Roles & Personas.
- For a new idea, use the Project Initiation Guide to produce a one‑pager.
- Link artifacts back to the project board and repository files for visibility.

## Using these docs in Copilot Spaces
Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context. Keep artifacts up-to-date so Copilot guidance remains accurate.

## Acceptance Criteria for this README
- Links to all docs in this folder are present and correct.
- Contains a clear process summary and quick navigation for new team members.
- Explains how to use these docs with Copilot Spaces.
