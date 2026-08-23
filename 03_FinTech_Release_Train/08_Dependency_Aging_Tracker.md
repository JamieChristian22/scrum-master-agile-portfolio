# Dependency Aging Tracker

| ID | Upstream | Downstream | Dependency | Initial Age | Final Age | Criticality | Owner | Status |
|---|---|---|---|---:|---:|---|---|---|
| DEP-001 | Digital Account Opening | Payments Modernization | API / data contract | 10 | 3 | High | Engineering Lead | Closed |
| DEP-002 | Payments Modernization | Fraud Controls | Test environment | 8 | 2 | High | QA Lead | Closed |
| DEP-003 | Fraud Controls | Mobile Banking | Release configuration | 7 | 3 | Medium | DevOps Lead | Closed |
| DEP-004 | Mobile Banking | Release Governance | Analytics event schema | 6 | 2 | Medium | Data Lead | Closed |
| DEP-005 | Release Governance | Digital Account Opening | Business approval | 9 | 4 | High | Product Owner | Closed |

High-criticality dependencies are reviewed at least twice weekly. Any dependency older than 5 business days requires a recovery date.
