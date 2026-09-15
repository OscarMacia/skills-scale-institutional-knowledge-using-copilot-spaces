# OctoAcme Project Management Documentation

## Overview

OctoAcme follows a structured, customer-first project management approach designed to deliver value iteratively while maintaining clear ownership, risk management, and stakeholder alignment. This documentation serves as the central repository of OctoAcme's project management processes, roles, and best practices.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

OctoAcme projects follow a five-phase lifecycle:

1. **Initiation** — Validate business need, identify stakeholders, and align on success criteria
2. **Planning** — Break work into shippable increments, identify dependencies, and create a detailed roadmap
3. **Execution** — Build, test, review, and iterate through regular team rhythms and quality gates
4. **Release** — Deploy to production with verified acceptance criteria, passing CI/security scans, and documented rollback plans
5. **Retrospective** — Capture learnings and drive continuous improvement through actionable insights

## Key Workflows & Processes

### Execution & Quality Assurance

Day-to-day delivery is structured around regular team rhythms:
- **Daily standups** (15 minutes) — focus on progress, blockers, and dependencies
- **Weekly delivery sync** — show progress, updates, and flagged risks
- **End-of-sprint demos** — validate work and gather feedback

OctoAcme maintains rigorous quality standards:
- Small pull requests (≤400 lines) with issue links and acceptance criteria
- Unit tests, integration tests, and end-to-end smoke tests for critical flows
- Security scanning in CI before merge
- At least one approval required before merging
- Clear Definition of Done enforced across all work

### Risk Management & Communication

Risks are actively managed through a structured Risk Register (ID, Description, Impact, Likelihood, Owner, Mitigation, Status) reviewed weekly. A three-tier escalation path keeps risks visible:
- **Level 1**: Team-level triage in daily standup
- **Level 2**: PM escalates to Product Lead and dependent teams
- **Level 3**: Sponsor-level escalation for business-impacting issues

Stakeholder alignment is maintained through multiple communication channels:
- Weekly PM/Product Manager syncs
- Twice-weekly standups for delivery team
- Monthly stakeholder updates
- Standardized weekly status templates covering progress, next steps, risks, and decisions

### Continuous Improvement

Retrospectives held after each sprint, release, or milestone drive continuous improvement. Teams timebox sessions (45–75 minutes) to capture what went well, what could improve, and prioritize 2–3 actionable items with clear owners and due dates. Action items feed back into the project backlog with progress reviewed in weekly PM syncs.

## Core Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risk management, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and priority guidance

## Documentation Guide

### Getting Started

Start with the **[Project Management Overview](octoacme-project-management-overview.md)** for a concise introduction to OctoAcme principles, roles, and key artifacts.

### Process Documentation by Phase

Follow these guides based on your project phase:

- **[Project Initiation](octoacme-project-initiation.md)** — Define business need, identify stakeholders, create a Project One-pager, and decide go/no-go for planning
- **[Project Planning](octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and prioritized backlog with acceptance criteria and risk identification
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day execution, maintain team rhythm, track quality standards, and escalate blockers
- **[Release & Deployment](octoacme-release-and-deployment.md)** — Standardize how features are released to production with pre-release validation, deployment checklists, and rollback planning
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings after sprints or milestones and drive iterative process improvements

### Cross-Cutting Processes

These processes apply throughout the project lifecycle:

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies throughout execution
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Understand the responsibilities, goals, and communication patterns of core project roles

## Quick Reference: Key Checklists

### Initiation Checklist
- [ ] One-pager completed and reviewed by Product Lead
- [ ] Sponsor / Stakeholder alignment confirmed (email or meeting)
- [ ] Decision: Approve to move into planning?
- [ ] Create repo or project board skeleton
- [ ] Add initial artifacts to repo (docs/ or .copilot/)

### Planning Checklist
- [ ] Project kickoff held
- [ ] Backlog prioritized and estimated
- [ ] Release timeline and milestones agreed
- [ ] Definition of Done documented
- [ ] Initial test plan / QA approach drafted

### Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly

### Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support

## Communication Cadence

- **Weekly sync**: PM + Product Manager alignment
- **Twice-weekly standups**: Delivery team (or as agreed)
- **Monthly updates**: Stakeholder briefings
- **Ad-hoc escalations**: As needed for risks and blockers

## Key Artifacts

All OctoAcme projects maintain these core artifacts:

- **Project Charter / One-pager** — Problem statement, goals, success metrics, timeline
- **Roadmap and Release Plan** — High-level milestones and delivery phases
- **Sprint/Iteration Backlog** — Prioritized work items with acceptance criteria
- **Risk Register** — Active risks with impact, likelihood, and mitigations
- **Retrospective notes** — Learnings and action items from completed phases

## How to Use These Docs

- **For new team members**: Start with the [Project Management Overview](octoacme-project-management-overview.md), then explore the phase guides based on your role
- **For project setup**: Use the [Project Initiation](octoacme-project-initiation.md) guide and Project One-pager template
- **For ongoing management**: Reference the [Execution & Tracking](octoacme-execution-and-tracking.md) guide and use the checklists above
- **In Copilot Spaces**: Add process-specific docs to `.copilot/` to ground Copilot's knowledge in OctoAcme practices

---

*Last updated: 2026-09-15*
