---
title: "Backend & Data"
---

{{< sparki/evidence status="VERIFIED CONTEXT" >}}
The backend should make intent, consent, and outcomes auditable without exposing identity too early.
{{< /sparki/evidence >}}

## System Overview

The first system can be a small relational application with explicit state transitions, an operator queue, and append-only audit events.

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
- Permissions
- Data model

## Manual vs Automated Responsibilities

| Responsibility | First version | Later consideration |
| --- | --- | --- |
| Intent quality | Operator review | Assisted checks |
| Collision qualification | Operator or assisted | Evidence-backed matching |
| Consent and identity release | Explicit system state | Never bypass consent |
| Outcome follow-up | Operator workflow | Reminders and reporting |

The first implementation can use a small relational data model with explicit state transitions and append-only audit events. Schema and provider choices are unresolved.
