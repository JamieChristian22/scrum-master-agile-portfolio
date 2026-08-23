# Dependency Aging Tracker

| ID | Upstream | Downstream | Dependency | Initial Age | Final Age | Criticality | Owner | Status |
|---|---|---|---|---:|---:|---|---|---|
| DEP-001 | CI/CD Reliability | Network Automation | API / data contract | 10 | 3 | High | Engineering Lead | Closed |
| DEP-002 | Network Automation | Observability | Test environment | 8 | 2 | High | QA Lead | Closed |
| DEP-003 | Observability | Release Automation | Release configuration | 7 | 3 | Medium | DevOps Lead | Closed |
| DEP-004 | Release Automation | DevOps Operating Model | Analytics event schema | 6 | 2 | Medium | Data Lead | Closed |
| DEP-005 | DevOps Operating Model | CI/CD Reliability | Business approval | 9 | 4 | High | Product Owner | Closed |

High-criticality dependencies are reviewed at least twice weekly. Any dependency older than 5 business days requires a recovery date.
