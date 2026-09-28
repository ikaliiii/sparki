---
title: "Backend & Data"
---

The backend should make intent, consent, and outcomes auditable without exposing identity too early.

## Core Records

- Intent records
- Collision records
- Response states
- Airlock records
- Identity release
- Outcome records

## Operations

- Operator console
- Analytics events
- Audit trail

The first implementation can use a small relational data model with explicit state transitions and append-only audit events. Schema and provider choices are unresolved.
