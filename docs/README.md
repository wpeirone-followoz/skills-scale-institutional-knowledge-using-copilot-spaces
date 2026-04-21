# OctoAcme Project Management — Overview

> **Living documentation:** This README is versioned, living guidance. As OctoAcme's teams adapt their processes, this document and the linked detail docs are updated to reflect current practice. If you spot something out of date, open a PR.

---

## Purpose

This overview helps new contributors get up to speed quickly on how OctoAcme plans, tracks, and ships work. It synthesizes the key concepts from the full set of process documents in this directory and points to the detail docs for each topic.

---

## Scope

These practices apply to all **cross-functional projects** that deliver product features, services, or integrations. Whether you are a first-time contributor or a returning team member, this guide outlines what to expect and where to look for specifics.

For the full overview, see [`octoacme-project-management-overview.md`](./octoacme-project-management-overview.md).

---

## Guiding Principles

| Principle | What it means in practice |
|---|---|
| **Customer-first** | Prioritize customer value and usability in every decision |
| **Iterative delivery** | Ship small, testable increments rather than big-bang releases |
| **Clear ownership** | Every project has a named PM and Product Lead |
| **Data-informed** | Measure impact; let evidence drive prioritization |
| **Psychological safety** | Encourage candid feedback and learning without blame |

---

## Core Roles & Responsibilities

Three roles are most directly involved in program and project management at OctoAcme. Detailed persona definitions are in [`octoacme-roles-and-personas.md`](./octoacme-roles-and-personas.md).

### Project Manager (PM)
- Owns project plans, timelines, and milestone tracking
- Manages risks, dependencies, and resource constraints
- Facilitates standups, planning sessions, and retrospectives
- Publishes weekly status updates and maintains the risk register

### Product Manager (PdM)
- Defines the problem statement, goals, and success metrics
- Prioritizes and maintains the product backlog
- Collaborates with engineering and stakeholders on trade-offs
- Validates solutions through user research and outcome metrics

### Developers
- Implement features and fixes to acceptance criteria
- Write and maintain tests and documentation
- Participate in design reviews, estimation, and planning
- Help identify and mitigate technical risks

---

## Project Artifact Lifecycle

Artifacts are created progressively as a project moves through its phases:

| Artifact | Created In | Owner | Purpose |
|---|---|---|---|
| **Project One-pager** | Initiation | PM + PdM | Problem, goal, success metrics, stakeholders |
| **Stakeholder & Communication Plan** | Initiation | PM | Identify groups and update cadence |
| **Prioritized Backlog** | Planning | PdM | Shippable increments with acceptance criteria |
| **Release Plan / Milestone Map** | Planning | PM | Timeline and key delivery gates |
| **Definition of Done (DoD)** | Planning | Team | Shared quality bar for "done" |
| **Risk Register** | Planning → ongoing | PM | ID, impact, likelihood, owner, mitigation, status |
| **Sprint/Iteration Board** | Execution | Team | Backlog → In Progress → Done workflow |
| **Release Notes** | Release | PM | Summary, changes, migration steps, known issues |
| **Retrospective Notes & Action Items** | Close | PM | Learnings and follow-up owners |

---

## Process Phases

### 1 · Initiation
Validate and authorize new work before committing resources.

Key activities: write the Project One-pager, identify stakeholders, establish success metrics, and hold a go/no-go gate.

→ Detail: [`octoacme-project-initiation.md`](./octoacme-project-initiation.md)

---

### 2 · Planning
Turn an approved initiative into an actionable backlog and delivery plan.

Key activities: kickoff meeting, backlog creation with acceptance criteria, estimation, Definition of Done, release plan, and an initial risk register.

→ Detail: [`octoacme-project-planning.md`](./octoacme-project-planning.md)

---

### 3 · Execution & Tracking
Build, test, review, and iterate using a clear team rhythm.

Key activities: daily standups, weekly delivery syncs, sprint demos, PR workflow (small PRs, CI checks, one approval), burndown tracking, and blocker escalation.

→ Detail: [`octoacme-execution-and-tracking.md`](./octoacme-execution-and-tracking.md)

---

### 4 · Release & Deployment
Ship predictably with low risk and high observability.

Key activities: verify all acceptance criteria and CI checks, draft release notes, schedule a deployment window, run smoke tests in staging, deploy to production, and announce to stakeholders.

Release types: **Patch** (hotfix) · **Minor** (incremental feature) · **Major** (breaking change)

→ Detail: [`octoacme-release-and-deployment.md`](./octoacme-release-and-deployment.md)

---

### 5 · Retrospective & Continuous Improvement
Capture learnings and convert them into concrete improvements.

Key activities: run a structured retrospective (what went well / what to improve / action items) after every sprint, release, or major incident. Track 2–3 prioritized action items; review them at the next weekly PM sync.

→ Detail: [`octoacme-retrospective-and-continuous-improvement.md`](./octoacme-retrospective-and-continuous-improvement.md)

---

## Risk Management

Risks are identified during planning and monitored continuously. The **Risk Register** is the single source of truth and is reviewed at every weekly sync.

Risk lifecycle: **Identify → Assess → Mitigate → Monitor**

Escalation path: Team standup → PM → Product Lead → Sponsor. Security incidents follow the security incident runbook with Security on-call notification.

→ Detail: [`octoacme-risks-and-communication.md`](./octoacme-risks-and-communication.md)

---

## Meeting Rhythm & Reporting

| Meeting / Report | Cadence | Participants |
|---|---|---|
| Daily standup | Daily (15 min) | Delivery team |
| PM + PdM alignment | Weekly | PM, PdM |
| Weekly delivery sync | Weekly | PM, team leads |
| Sprint demo / review | End of each sprint | Team + stakeholders |
| Stakeholder status update | Monthly (or milestone-based) | PM → stakeholders |
| Retrospective | After each sprint / release / incident | Full team |
| Ad-hoc escalations | As needed | PM + relevant parties |

**Weekly status report format:** Progress · Next steps · Risks & blockers · Decisions needed.

→ Detail: [`octoacme-risks-and-communication.md`](./octoacme-risks-and-communication.md)

---

## Goals of These Practices

- **Transparency** — One source of truth for status, risks, and decisions; visible to all stakeholders.
- **Iteration** — Deliver incrementally, gather feedback early, and course-correct often.
- **Clear ownership** — Every artifact, action item, and risk has a named owner and due date.

---

## Document Index

| File | Topic |
|---|---|
| [`octoacme-project-management-overview.md`](./octoacme-project-management-overview.md) | High-level overview, principles, roles, and lifecycle |
| [`octoacme-roles-and-personas.md`](./octoacme-roles-and-personas.md) | Detailed persona definitions for PM, PdM, and Developers |
| [`octoacme-project-initiation.md`](./octoacme-project-initiation.md) | Initiation process, one-pager template, and decision gate |
| [`octoacme-project-planning.md`](./octoacme-project-planning.md) | Planning activities, backlog template, sprint planning |
| [`octoacme-execution-and-tracking.md`](./octoacme-execution-and-tracking.md) | Execution workflows, PR conventions, quality, and escalation |
| [`octoacme-release-and-deployment.md`](./octoacme-release-and-deployment.md) | Release types, deployment checklist, rollback playbook |
| [`octoacme-retrospective-and-continuous-improvement.md`](./octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure and continuous improvement culture |
| [`octoacme-risks-and-communication.md`](./octoacme-risks-and-communication.md) | Risk register, stakeholder communication, escalation paths |

---

*This is a living document. To propose changes, open a pull request against this file and tag the PM for review.*
