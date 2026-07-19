---
title: Department Contract Standard
document_id: CONST-001
version: 2.0.0
status: Active
classification: Governance
authority: High
owner: Studio Governance
approved_by: Executive Producer
depends_on:
  - ARCH-000
  - CONST-000
---

# Department Contract Standard

## Purpose

This document defines the mandatory structure, authority, and operating contract for every department within Patch 10.0 Studio.

Its purpose is to ensure consistency, eliminate ambiguity, and establish a common organizational language across all departments.

Every department manual shall conform to this standard.

No department may omit or redefine the sections defined in this document without formal governance approval.

---

# Scope

This standard applies to every permanent department within the studio, including current and future departments.

Examples include, but are not limited to:

- Executive Producer
- Lore Department
- Visual Production
- Repository & Canon Management
- Quality Assurance
- Narrative Design
- Character Department
- Production Control

---

# Department Identity

Every department manual shall begin with standardized metadata.

Example:

```yaml
---
title:
document_id:
version:
status:
classification:
owner:
authority:
depends_on:
reports_to:
---
```

This metadata uniquely identifies the department and its place within the organization.

---

# Mandatory Sections

Every department manual shall contain the following sections in the specified order.

## 1. Identity

Defines the department.

This section answers:

> "Who are we?"

---

## 2. Purpose

Defines why the department exists.

This section answers:

> "Why does this department exist?"

---

## 3. Mission

Defines the department's long-term objective.

Mission describes what success looks like.

---

## 4. Scope

Defines the operational boundaries of the department.

Scope establishes where the department operates.

Anything outside this scope belongs to another department.

---

## 5. Ownership

Defines everything officially owned by the department.

Ownership includes:

- decision-making
- maintenance
- documentation
- long-term stewardship
- quality within its domain

Ownership shall be exclusive whenever practical.

---

## 6. Authority

Defines decisions the department may make independently.

Authority establishes autonomy.

Authority does not permit modification of another department's owned assets.

---

## 7. Accepts

Defines approved inputs.

Inputs may include:

- Work Orders
- Approved documents
- Repository artifacts
- Reports
- Assets

Only approved inputs may begin production.

---

## 8. Produces

Defines official outputs.

Outputs become inputs for downstream departments after approval.

---

## 9. Responsibilities

Defines recurring operational duties performed by the department.

Responsibilities describe work.

They do not define ownership.

---

## 10. Decision Rules

Defines principles used when multiple valid solutions exist.

Decision rules improve consistency.

Departments should avoid arbitrary decisions.

---

## 11. Success Metrics

Defines how departmental success is evaluated.

Metrics should be measurable whenever practical.

Examples include:

- consistency
- completeness
- maintainability
- production quality
- delivery reliability

---

## 12. Common Failure Modes

Documents predictable mistakes.

The purpose is prevention rather than blame.

Departments should continuously reduce recurring failures.

---

## 13. Collaboration

Defines regular interactions with other departments.

This section identifies:

- upstream departments
- downstream departments
- review relationships
- communication expectations

---

## 14. Deliverables

Defines official artifacts produced by the department.

Examples:

- reports
- documentation
- production assets
- reviews
- standards

Deliverables should be clearly defined.

---

## 15. References

Lists architecture, governance documents, templates, and related departments referenced by the manual.

---

## 16. Closing Statement

Concludes the manual by reaffirming the department's role within the studio.

---

# Ownership Rules

Ownership is exclusive.

Every permanent production domain shall have exactly one owning department.

Departments may:

- review
- advise
- recommend
- support

Ownership shall not be shared unless explicitly defined by governance.

---

# Authority Rules

Departments may make independent decisions within their authority.

Departments shall not:

- modify another department's owned artifacts
- redefine governance
- bypass review requirements
- assume responsibilities outside their scope

---

# Collaboration Rules

Departments are expected to collaborate through documented artifacts rather than informal assumptions.

Communication should produce repository updates whenever practical.

Approved outputs become trusted inputs for downstream departments.

---

# Department Evolution

Departments may evolve over time.

Changes to:

- ownership
- authority
- scope
- responsibilities

shall follow the governance revision process.

Departments should grow through specialization rather than expanding indefinitely.

---

# Compliance

Every department manual shall comply with this standard.

Manuals that do not conform should be revised before approval.

Consistency across departments improves maintainability, onboarding, and long-term governance.

---

# References

- ARCH-000 — Studio Architecture
- CONST-000 — Studio Constitution

---

# Closing Statement

A department is more than a collection of responsibilities.

It is a permanent organizational unit with clearly defined ownership, authority, and accountability.

Standardized department contracts ensure that every department operates consistently while remaining specialized within its own production domain.