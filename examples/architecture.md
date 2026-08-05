# Example: Architecture Decision

## Prompt

```text
Use GrillForge in deep mode:
Should we split this modular monolith into microservices now?
```

## Critical claims

- Current deployment boundaries are blocking delivery.
- Independent scaling is required now, not hypothetically.
- The team can absorb distributed-system complexity.
- Service ownership will remain clear.
- Operational tooling is mature enough.

## Flip test

If the system were already split into ten services, would the team choose to keep that structure today?

## Possible verdict

`KILL` or `PROBE` unless measured bottlenecks justify the additional operational and coordination cost.
