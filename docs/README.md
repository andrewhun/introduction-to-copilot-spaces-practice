# OctoAcme Project Management Docs

This README provides a comprehensive overview of OctoAcme's project management processes and links to detailed process documents in this repository's docs/ folder.

## Project Management Overview

OctoAcme employs a structured, customer-first project lifecycle that spans from initial concept through post-release retrospectives. The organization follows a five-stage approach:

1. **Initiation** – Validate business need and stakeholder alignment with a Project One-pager, identify stakeholders, and confirm measurable success metrics before committing resources.

2. **Planning** – Break work into shippable increments with prioritized backlog, estimate scope using T-shirt sizing or story points, define Definition of Done, and map release milestones and dependencies.

3. **Execution & Tracking** – Execute work through daily standups, weekly syncs, and iterative delivery using project boards. Follow PR disciplines (small PRs ≤400 lines, CI checks, code review approval) and maintain velocity and burndown metrics.

4. **Release & Deployment** – Follow standardized pre-release checks, smoke tests, deployment windows, and documented rollback procedures to reduce risk and ensure observability.

5. **Close & Retrospective** – Conduct post-sprint or post-milestone retrospectives to capture learnings and convert them into actionable improvements tracked in the backlog.

### Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named Project Manager (PM) and Product Lead roles
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

### Core Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, measures success
- **Developers**: Implement features, collaborate on design and testability, contribute to estimates
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and feedback

### Communication & Risk Management

OctoAcme maintains a structured communication cadence:
- Daily standups (15 minutes)
- Weekly PM + PdM sync
- Twice-weekly team standups
- Monthly stakeholder updates
- Ad-hoc escalations as needed

Risk management follows a clear lifecycle: identify → assess → mitigate → monitor. A three-level escalation path (team → PM → Product Lead → Sponsor) ensures blockers surface quickly without creating bottlenecks.

### Quality & Testing

Quality is embedded into execution:
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

---

## Links to Process Documents

- **[octoacme-project-management-overview.md](octoacme-project-management-overview.md)** – High-level overview of OctoAcme's approach, roles, key artifacts, and project lifecycle
- **[octoacme-project-initiation.md](octoacme-project-initiation.md)** – Project initiation guide, one-pager template, and decision gates
- **[octoacme-project-planning.md](octoacme-project-planning.md)** – Planning steps, backlog and sprint planning templates, risk & dependency management
- **[octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md)** – Day-to-day execution guidance, PR workflow, quality standards, and execution checklist
- **[octoacme-release-and-deployment.md](octoacme-release-and-deployment.md)** – Release types, pre-release requirements, deployment checklist, and rollback playbook
- **[octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md)** – Retrospective structure, tracking improvements, and action item template
- **[octoacme-risks-and-communication.md](octoacme-risks-and-communication.md)** – Risk register maintenance, risk lifecycle, stakeholder communication templates, and escalation paths
- **[octoacme-roles-and-personas.md](octoacme-roles-and-personas.md)** – Detailed role definitions and persona responsibilities for Developers, Product Managers, and Project Managers

---

## How to Use These Docs

- Keep the Project Charter (One-pager) updated in your project repo
- Reference the relevant process doc for guidance at each lifecycle phase
- Add process-specific docs to `.copilot/` if you want Copilot Spaces to use them as context
- Use the templates and checklists provided in each document to standardize execution
- Treat these docs as living artifacts—update them as your team learns and evolves

---

*Last updated: 2026-09-03*
