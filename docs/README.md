# OctoAcme Project Management Docs

This README is the central entry point for all project management knowledge at OctoAcme. It introduces our methodology and philosophy, then links to detailed process and role documents so that any team member—new or experienced—can quickly orient themselves and navigate to the guidance they need.

## Overview

OctoAcme follows a lightweight, end-to-end project lifecycle designed for cross-functional delivery: **Initiation → Planning → Execution → Release → Retrospective**. Work begins by validating the business need and aligning stakeholders using a **Project One-pager/Charter** (problem, SMART objective, success metrics, stakeholders, timeline, risks, and proposed roles). A decision gate then determines whether the initiative is ready to move into detailed planning, with early emphasis on clarity of success metrics, stakeholder agreement on priority, and confirmed team availability.

In **Planning**, the team converts the approved initiative into an actionable backlog and release path. This includes holding a kickoff, creating prioritized backlog items with explicit **acceptance criteria**, estimating scope, defining a shared **Definition of Done**, and identifying risks and cross-team dependencies. Risks are managed via a simple **risk register** (impact, likelihood, owner, mitigation, status) and dependencies are made visible on the project board so they can be tracked and escalated early.

During **Execution & Tracking**, OctoAcme relies on a consistent team rhythm and transparent workflow management. Teams use a project board (e.g., **Backlog → Ready → In Progress → In Review → QA → Done**) and maintain a PR practice favoring small changes, issue linkage, acceptance criteria in descriptions, CI validation before review, and at least one approval before merge. Progress is reviewed in daily standups focused on blockers and dependencies, complemented by weekly delivery syncs and sprint-end demos/reviews. Escalation is structured from team triage to PM-led cross-team escalation, and ultimately sponsor-level escalation for business-impacting issues.

Quality and release discipline are reinforced throughout: teams use **unit, integration, and end-to-end smoke tests** (especially for critical flows), plus CI-based linting and security scanning, with manual QA when needed for acceptance. Releases follow standardized pre-release requirements (met acceptance criteria, passing CI/scans, release notes, rollback plan, smoke tests) and a deployment checklist that emphasizes staging verification, post-deploy checks, and clear stakeholder/support announcements. Finally, OctoAcme closes the loop with **retrospectives** after sprints, releases, or incidents, converting learnings into owned action items that are tracked in the backlog and reviewed regularly to drive continuous improvement.

## Process Docs

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)
