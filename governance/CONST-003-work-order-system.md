---
title: Work Order System
document_id: CONST-003
version: 2.0.0
status: Active
classification: Governance
authority: High
owner: Production Control
approved_by: Executive Producer
depends_on:
  - ARCH-000
  - CONST-000
  - CONST-001
  - CONST-002
---

# Work Order System

## Purpose

This document defines the standard Work Order (WO) system used by Patch 10.0 Studio.

A Work Order is the official authorization for production work.

No production activity shall begin without an approved Work Order unless explicitly exempted by Studio Governance.

---

# Scope

This standard applies to every department, assignment, and production cycle.

All production work shall be traceable to one or more Work Orders.

---

# Philosophy

Ideas are not work.

Requests are not work.

Conversations are not work.

Only approved Work Orders represent official production activities.

The Work Order transforms planning into execution.

---

# Work Order Lifecycle

Every Work Order follows the same lifecycle.

```text
Draft

↓

Proposed

↓

Approved

↓

Assigned

↓

In Progress

↓

Under Review

↓

Completed

↓

Archived
```

Only Approved Work Orders may enter production.

---

# Work Order Identifier

Every Work Order shall receive a unique identifier.

Example:

```text
WO-000001
WO-000002
WO-000003
```

Identifiers are permanent.

They shall never be reused.

---

# Required Information

Every Work Order shall contain at minimum:

- Identifier
- Title
- Objective
- Requesting Authority
- Owning Department
- Priority
- Production Unit
- Dependencies
- Deliverables
- Acceptance Criteria
- Status

Additional fields may be added when necessary.

---

# Production Units

Every Work Order shall reference exactly one primary production unit.

Examples include:

- Franchise
- Universe
- Saga
- Arc
- Volume
- Chapter
- Scene
- Shot
- Asset
- Documentation

Large objectives should be divided into multiple Work Orders.

---

# Ownership

Every Work Order shall have exactly one owning department.

The owning department is accountable for:

- execution
- coordination
- completion
- reporting

Other departments may support the Work Order through separate assignments.

Ownership shall remain singular.

---

# Priority Levels

Work Orders shall use standardized priority levels.

```text
Critical

High

Normal

Low
```

Priority determines scheduling.

Priority does not override governance.

---

# Dependencies

Dependencies shall be documented explicitly.

Examples include:

- another Work Order
- approved document
- completed review
- production milestone

Assignments shall not begin until required dependencies are satisfied.

---

# Deliverables

Every Work Order shall define expected outputs.

Examples include:

- document
- artwork
- storyboard
- report
- repository update
- review package
- production asset

Completion is measured against deliverables, not effort.

---

# Acceptance Criteria

Every Work Order shall define objective completion criteria.

Acceptance criteria should be measurable whenever practical.

Examples:

- document approved
- canon verified
- repository updated
- review completed
- asset exported

Work shall not be considered complete until acceptance criteria have been satisfied.

---

# Assignment Relationship

A Work Order authorizes production.

Assignments execute production.

One Work Order may create:

- one assignment
- multiple assignments
- sequential assignments
- parallel assignments

Assignments inherit scope from the Work Order.

Assignments shall not exceed that scope without revision.

---

# Work Order Revision

Approved Work Orders may be revised when:

- scope changes
- dependencies change
- priorities change
- production requirements change

Significant revisions should be documented.

Historical revisions should remain traceable.

---

# Completion

A Work Order is complete only when:

- all assignments have finished
- reviews have passed
- acceptance criteria are satisfied
- repository updates are complete

Completion shall be recorded before archival.

---

# Archival

Completed Work Orders shall be archived.

Archived Work Orders provide:

- production history
- audit trail
- decision traceability
- performance analysis

Archived records shall remain immutable except for administrative corrections.

---

# References

- ARCH-000 — Studio Architecture
- CONST-000 — Studio Constitution
- CONST-001 — Department Contract Standard
- CONST-002 — Production Cycle Standard

---

# Closing Statement

The Work Order System transforms production planning into structured execution.

By standardizing authorization, ownership, scope, and completion criteria, Work Orders ensure that every production activity remains traceable, accountable, and aligned with the long-term objectives of Patch 10.0 Studio.