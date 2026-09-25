# OctoAcme Project Management Documentation

## About OctoAcme

OctoAcme is a customer-first, iterative project management framework for cross-functional projects that deliver product features, services, and integrations. It emphasizes clear ownership, data-informed decisions, psychological safety, and small, testable increments.

Use this README as the central index for the project management process documentation. The guides are organized around the project lifecycle and provide practical checklists, templates, and role guidance.

## Project Lifecycle Overview

OctoAcme follows a five-phase lifecycle:

1. **Initiation** — Define the problem, desired outcome, stakeholders, success metrics, risks, and high-level timeline. Decide whether the initiative should move into planning.
2. **Planning** — Turn the approved initiative into a prioritized backlog, shippable increments, milestones, estimates, dependencies, a Definition of Done, and an initial test plan.
3. **Execution** — Build, test, review, and iterate on deliverables while tracking progress, risks, dependencies, quality, and project metrics.
4. **Release** — Deploy completed work with acceptance criteria, CI and security checks, release notes, smoke tests, verification, and a rollback plan.
5. **Close & Retrospective** — Capture what went well, identify improvements, assign follow-up actions, and apply learnings to future work.

## Core Principles

- **Customer-first:** Prioritize customer value, usability, and measurable outcomes.
- **Iterative delivery:** Deliver small, testable increments and learn from feedback.
- **Clear ownership:** Every project has a named Project Manager and Product Lead, with responsibilities understood across the team.
- **Data-informed decisions:** Measure impact and use evidence to guide prioritization and iteration.
- **Psychological safety:** Encourage candid feedback, learning, and blameless improvement.

## Core Concepts and Practices

### Roles and ownership

- **Project Manager (PM):** Coordinates delivery, schedules, risks, communications, and stakeholder alignment.
- **Product Manager (PdM):** Defines outcomes, prioritizes the backlog, and measures success.
- **Developers:** Design, implement, test, review, and document maintainable solutions.
- **QA/Testing:** Validates quality and acceptance criteria.
- **Stakeholders:** Provide input, decisions, feedback, and approvals.

### Planning and delivery

- Start with a project one-pager that defines the problem, SMART goal, success metrics, stakeholders, milestones, risks, dependencies, and proposed team.
- Break approved work into prioritized backlog items with clear acceptance criteria, estimates, owners, and related links.
- Use a project board with the workflow **Backlog → Ready → In Progress → In Review → QA → Done**.
- Keep work small where possible; target pull requests of 400 lines or fewer.
- Define and apply a shared Definition of Done, including the required testing and review activities.

### Quality and release readiness

- Add unit tests for new logic and integration tests where appropriate.
- Run automated tests, linting, and security scanning in CI before review or release.
- Perform end-to-end smoke tests for critical flows and manual QA when feature acceptance requires it.
- Before release, confirm acceptance criteria, CI results, release notes, smoke tests, observability, and rollback or mitigation plans.

### Communication, risk, and improvement

- Use regular standups, delivery syncs, demos, stakeholder updates, and retrospectives to maintain alignment.
- Maintain a risk register with an owner, impact, likelihood, mitigation plan, and status; review it at least weekly.
- Escalate blockers from the team to the PM, Product Lead, and sponsor as the business impact requires.
- Convert retrospective findings into a small number of owned, time-bound action items and track their impact.

## Documentation Index

### Getting Started

- [OctoAcme Project Management Overview](docs/octoacme-project-management-overview.md) — Introduction to the framework, principles, roles, artifacts, lifecycle, and communication cadence.

### Project Lifecycle Guides

- [Project Initiation Guide](docs/octoacme-project-initiation.md) — Validate a project idea, align stakeholders, define success, and make the planning decision.
- [Project Planning](docs/octoacme-project-planning.md) — Create the backlog, estimates, milestones, Definition of Done, dependency plan, and initial QA approach.
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md) — Manage day-to-day delivery, project-board workflow, quality checks, metrics, and blocker escalation.
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md) — Prepare, deploy, verify, communicate, and roll back releases safely.
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md) — Run retrospectives and turn learnings into measurable improvements.

### Cross-Cutting Practices

- [Risk Management & Communication](docs/octoacme-risks-and-communication.md) — Maintain the risk register, communicate status and incidents, and follow escalation paths.
- [Roles and Personas](docs/octoacme-roles-and-personas.md) — Reference responsibilities, goals, and communication patterns for common project roles.

## Key Resources and Templates

The following templates and checklists are embedded in the process guides:

- [Project One-pager Template](docs/octoacme-project-initiation.md#project-one-pager-template) — Define the problem, goal, metrics, stakeholders, timeline, risks, and team.
- [Backlog Item Template](docs/octoacme-project-planning.md#backlog-item-template) — Capture the title, description, acceptance criteria, priority, estimate, owner, and links.
- [Risk Register guidance](docs/octoacme-risks-and-communication.md#risk-register) — Track risk ID, description, impact, likelihood, owner, mitigation, and status.
- [Weekly Status Template](docs/octoacme-risks-and-communication.md#communication-templates) — Report progress, next steps, risks, blockers, and decisions needed.
- [Release Notes Template](docs/octoacme-release-and-deployment.md#release-notes-template) — Record release summary, changes, migration steps, and known issues.
- [Execution Checklist](docs/octoacme-execution-and-tracking.md#execution-checklist) — Confirm branching, CI, demos, and risk-register maintenance.
- [Planning Checklist](docs/octoacme-project-planning.md#planning-checklist) — Confirm kickoff, backlog readiness, milestones, DoD, and QA planning.
- [Deployment Checklist](docs/octoacme-release-and-deployment.md#deployment-checklist) — Confirm staging, smoke tests, production deployment, verification, and announcements.

## Suggested Starting Points

- **New to OctoAcme?** Start with the [Project Management Overview](docs/octoacme-project-management-overview.md), then read the [Roles and Personas](docs/octoacme-roles-and-personas.md) guide.
- **Starting a new initiative?** Use the [Project Initiation Guide](docs/octoacme-project-initiation.md).
- **Ready to deliver approved work?** Follow [Project Planning](docs/octoacme-project-planning.md) and [Execution & Tracking](docs/octoacme-execution-and-tracking.md).
- **Preparing a release?** Use the [Release & Deployment Guide](docs/octoacme-release-and-deployment.md).
- **Responding to a risk or blocker?** Consult [Risk Management & Communication](docs/octoacme-risks-and-communication.md).
- **Finishing a milestone or incident?** Run a [Retrospective](docs/octoacme-retrospective-and-continuous-improvement.md).

## Keeping the Documentation Current

Treat this README and the linked process guides as a shared source of truth. Update the relevant guide when the process changes, keep checklists aligned with team practice, and use the repository's process-document issue template for proposed additions or revisions.
