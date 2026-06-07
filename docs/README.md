# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation. Below is an overview of how OctoAcme manages projects, followed by links to detailed guides for each part of the process.

## Project Management at OctoAcme

OctoAcme uses a structured lifecycle-based approach to project management that prioritizes customer value, iterative delivery, and clear ownership. The organization applies five core phases—**Initiation** (validating business need and stakeholder alignment through a lightweight One-pager), **Planning** (breaking work into shippable increments with acceptance criteria and risk assessment), **Execution** (daily standups, sprint-based delivery with PR workflows, and quality gates), **Release** (standardized deployment with pre-release checklists and rollback plans), and **Close & Retrospective** (capturing learnings and continuous improvement). This end-to-end approach ensures that projects remain aligned with business objectives while maintaining flexibility to adapt based on evidence and team feedback.

OctoAcme's organizational model is built on three primary roles with distinct accountability: **Project Managers (PM)** coordinate delivery schedules, manage risks and communications, and facilitate key ceremonies; **Product Managers (PdM)** define outcomes, prioritize backlogs, and measure success against metrics; and **Developers** implement features while collaborating on design, testing, and risk identification. This clear role definition, supported by QA/Testing and Stakeholder input, establishes transparent ownership and reduces ambiguity. The structure emphasizes "psychological safety" as a core principle, encouraging teams to provide feedback and learn from setbacks.

Communication and alignment happen through a layered cadence: weekly syncs between PM and PdM, twice-weekly delivery team standups, monthly stakeholder updates, and ad-hoc escalations as needed. Status is tracked using standardized templates (weekly progress reports, incident summaries) and centralized artifacts such as Project Charters, Risk Registers, and Release notes. The Risk Management & Communication framework defines clear escalation paths from team-level through PM, Product Lead, and Sponsor, ensuring that blockers and critical issues surface quickly.

Quality assurance is embedded throughout execution via multiple mechanisms: unit and integration tests run in CI before PR approval, end-to-end smoke tests validate critical flows before release, and security scanning is integrated into the pipeline. Teams follow small PR conventions (≤400 lines), require at least one approval before merging, and conduct manual QA for feature acceptance when needed. The release process includes pre-deployment verification steps (staging smoke tests, rollback planning) and post-deployment checks, with a documented incident playbook to handle failures quickly and capture root causes for continuous improvement.

## Process Documentation Index

- [Project Management Overview](octoacme-project-management-overview.md) — Introduction to OctoAcme's approach, core roles, key artifacts, and high-level lifecycle
- [Project Initiation Guide](octoacme-project-initiation.md) — Initial steps to validate business need, align stakeholders, and create a lightweight plan
- [Project Planning](octoacme-project-planning.md) — Turn an approved initiative into an actionable plan and backlog for delivery
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Guidance for managing day-to-day execution and tracking progress toward project milestones
- [Risk Management & Communication](octoacme-risks-and-communication.md) — How to identify, manage, and communicate risks and dependencies
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Standardize how OctoAcme releases features to production to reduce risk and improve observability
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements
- [Roles & Personas](octoacme-roles-and-personas.md) — Definitions of typical roles and responsibilities used in OctoAcme projects

## Getting Started

1. **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand our principles and core roles.
2. **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md) to validate the business case and align stakeholders.
3. **Planning delivery?** Use the [Project Planning](octoacme-project-planning.md) guide to break work into shippable increments.
4. **In active delivery?** Refer to [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md) for daily guidance.
5. **Preparing to release?** Check the [Release & Deployment Guide](octoacme-release-and-deployment.md) to ensure quality and minimize risk.
6. **After a sprint or release?** Run a [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) session to capture learnings.

## Contributing to This Documentation

Have feedback, improvements, or want to propose changes to these process docs? Please use the templates in `.github/ISSUE_TEMPLATE/`:

- **[Add Content to Project Management Process Docs](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** — Request to add new content or updates to an existing process document.

Your insights help us continuously refine and improve how we work together.