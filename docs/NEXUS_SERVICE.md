# Nexus Service

The Nexus is the central authority of Aethelgard.

It enforces:
- Identity
- Time
- Causality
- Permissions
- Invariants

No system may mutate state without Nexus approval.

## Responsibilities
- Accept events
- Validate invariants
- Update context graph
- Emit state changes to Pulse

## Forbidden
- Direct AI calls
- UI logic
- Business-specific heuristics
