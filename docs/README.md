# OctoAcme — Project Management Overview

OctoAcme runs projects through a lightweight, evidence-driven lifecycle designed for iterative delivery and clear ownership. Projects begin with a concise Project One‑pager that defines the problem, measurable success metrics, primary stakeholders, and a high‑level timeline. Teams move from Initiation into Planning only when success criteria and stakeholder alignment are confirmed; planning produces a prioritized backlog, estimates, a Definition of Done, and a release/milestone map.

Responsibility is explicit: a named Project Manager (PM) coordinates schedules, risks, and communications while the Product Manager / Product Lead (PdM) owns outcomes and prioritization. Developers, QA, and stakeholders have defined responsibilities and handoffs. Regular team rhythms — daily standups, weekly delivery syncs, and sprint/milestone demos — keep work aligned and surface blockers early.

Work happens on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and follows a small-PR, CI-first pull request workflow. Quality assurance is built into the cadence with unit/integration tests, end-to-end smoke tests for critical flows, CI security scanning, and manual QA where needed. Release processes include pre-release checks (passing CI, release notes, rollback plan), staged smoke testing, and an incident/rollback playbook.

Risk and communication practices are lightweight and actionable: maintain a simple risk register (ID, impact, likelihood, owner, mitigation), review it weekly, and escalate through a defined path (team → PM → PdM → sponsor) for high‑impact issues. Retrospectives after sprints, releases, and incidents produce 2–3 prioritized action items that feed back into the backlog to drive continuous improvement.
