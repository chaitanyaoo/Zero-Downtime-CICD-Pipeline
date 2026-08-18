# DOC5A - CI/CD Pipeline (Chaitanya)

Zero Downtime CI/CD Pipeline assessment deliverables and documentation for a
pipeline built around **NovaPay**, a fictional digital banking landing page
(Java 21 / Spring Boot / Gradle).

The application itself lives in a separate `novapay` repository, which owns
its Java/Gradle build. This repository contains the pipeline design,
infrastructure-as-code, policies, dashboards, runbooks, and assessment
evidence around that app. The root GitHub Actions workflow here validates the
documentation and delivery structure that actually exists in this repository,
so pushes do not fail by trying to build a missing `novapay/` directory.

## Navigation

| Folder | Deliverable | Status |
|---|---|---|
| `docs/01-pipeline-architecture/` | 1 - 8+ stage pipeline | Not started (Day 1) |
| `docs/02-deployment-strategies/` | 2 - Blue-green + canary | Not started (Day 2) |
| `docs/03-compliance-gates/` | 3 - 6+ compliance gates | Not started (Day 2) |
| `docs/04-database-migration/` | 4 - Zero-downtime migration | Not started (Day 3) |
| `docs/05-environment-promotion/` | 5 - 4-env promotion workflow | Not started (Day 3) |
| `docs/06-rollback-specification/` | 6 - Automated rollback | Not started (Day 3) |
| `docs/07-runbook-playbook/` | 7 - Ops runbook + playbook | Not started (Day 4) |
| `docs/08-observability/` | 8 - DORA metrics + dashboards | Not started (Day 4) |
| `pipeline/` | Working IaC, policies, scripts | Structure validated by CI |
| `dashboards/` | Grafana exports + wireframes | Not started (Day 4) |
| `runbooks/` | Deployment + incident docs | Not started (Day 4) |
| `evidence/` | Self-assessment, reflections, errata, screenshots, TRC deck | Blocked - needs brief details (Day 5) |

See `ERRATA.md`, `evidence/self-assessment.md`, and `evidence/reflections.md`
for the current evidence placeholders.
