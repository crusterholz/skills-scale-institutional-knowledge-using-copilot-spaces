# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation! This repository provides structured guidance, checklists, and templates for managing technical projects using industry best practices.

## Project Management Processes Summary

OctoAcme project management is guided by these principles:
- **Customer-first value delivery** — prioritize customer value and usability
- **Iterative, incremental progress** — deliver small, testable increments
- **Clear roles and artifact ownership** — each project has named leaders and clear responsibilities
- **Data-driven prioritization** — measure impact and iterate based on evidence
- **Psychological safety and transparency** — encourage feedback, learning, and open communication

### Project Lifecycle

OctoAcme follows a structured five-phase lifecycle:

1. **Initiation** — Validate new ideas through a lightweight Project One-pager that confirms business need, identifies stakeholders, and establishes measurable success metrics.

2. **Planning** — Break scope into shippable increments with clear acceptance criteria, map dependencies, create a release plan, and establish the Definition of Done.

3. **Execution & Tracking** — Deliver through sprints using a GitHub Projects board (Backlog → Ready → In Progress → In Review → QA → Done). Daily standups focus on progress and blockers; weekly delivery syncs show demos and flag risks.

4. **Release & Deployment** — Manage deployments with pre-release requirements, smoke tests, rollback plans, and post-deploy verification to reduce production risk.

5. **Retrospective & Continuous Improvement** — Capture learnings after sprints, releases, or incidents through blameless retrospectives and convert insights into actionable improvements.

### Core Roles & Responsibilities

Success depends on clear ownership across distributed teams:

- **Product Managers** define what should be built—owning the product vision, prioritizing the backlog, and measuring outcomes through customer and business metrics.
- **Project Managers** coordinate delivery by managing schedules, risks, dependencies, and stakeholder communication.
- **Developers** design and build features to specification while writing tests, participating in reviews, and identifying technical risks.
- **QA/Testing** validate quality against acceptance criteria and coordinate testing throughout the delivery cycle.

### Quality & Risk Management

Quality is built into execution through:
- Small PRs (≤400 lines when possible)
- Mandatory CI testing, linting, and security scanning
- Unit, integration, and end-to-end smoke tests
- Manual QA for feature acceptance
- A formal **Risk Register** tracking risks by impact, likelihood, owner, and mitigation status
- A three-level blocker escalation process (team triage → PM escalation → sponsor involvement)
- A **Definition of Done** that all work must meet before marking complete

### Communication & Continuous Learning

Transparency and psychological safety are maintained through:
- **Regular cadences:** daily standups, weekly PM-PdM syncs, twice-weekly team standups, monthly stakeholder updates
- **Structured templates** for status updates, incident response, and escalation paths
- **Blameless retrospectives** after sprints, releases, and incidents that convert learnings into actionable improvements with clear owners
- **Centralized documentation** in the repository using Copilot Spaces to reduce single-person dependency and accelerate onboarding

---

## Documentation Structure

See each linked document for detailed process steps, templates, and checklists:

| Document | Purpose |
|----------|---------|
| [Project Management Overview](octoacme-project-management-overview.md) | Concise introduction to OctoAcme's approach, roles, and key artifacts |
| [Project Initiation Guide](octoacme-project-initiation.md) | Initial steps to validate and authorize work, align stakeholders, and create a lightweight plan |
| [Project Planning](octoacme-project-planning.md) | Turn an approved initiative into an actionable plan and backlog for delivery |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Manage day-to-day execution and track progress toward project milestones |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Identify, manage, and communicate risks and dependencies |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Standardize how OctoAcme releases features to production to reduce risk and improve observability |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert them into actionable improvements |
| [Roles & Personas](octoacme-roles-and-personas.md) | Define typical roles and responsibilities used across OctoAcme projects |

---

## Getting Started

1. **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md) for a high-level introduction.
2. **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md).
3. **In active delivery?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md) for day-to-day guidance.
4. **Preparing for release?** See [Release & Deployment Guide](octoacme-release-and-deployment.md).
5. **Wrapping up?** Run a retrospective using [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md).

---

## Contributing to These Docs

Have feedback or want to improve the OctoAcme processes? Use the [Add/Update Content to Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose changes, and we'll review and iterate together.
