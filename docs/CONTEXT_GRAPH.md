# Context Graph

The Context Graph is the canonical representation of reality inside Aethelgard.

It is not a knowledge graph.
It is not a social graph.

It is a temporal, relational map of:
- Humans
- Systems
- Artifacts
- Decisions
- Time

## Node Types

1. Person
   - id
   - role
   - team
   - trust_level

2. Artifact
   - id
   - type (code, doc, dataset, ticket)
   - owner
   - volatility_score

3. Process
   - id
   - trigger
   - expected_duration
   - failure_cost

4. Event
   - id
   - timestamp
   - source
   - impact_radius

5. Decision
   - id
   - options
   - confidence
   - reversibility

## Edge Types

- DEPENDS_ON
- CREATED_BY
- BLOCKS
- INFORMED_BY
- PRECEDES
- AMPLIFIES
