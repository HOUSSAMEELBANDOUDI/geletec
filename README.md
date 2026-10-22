# Geletec Ecosystem

> ⚠️ **Enterprise project — source code is proprietary and not published here.**
> This repository exists as a portfolio placeholder to document my role and contributions on the Geletec ecosystem at **Concepment**.

![Status](https://img.shields.io/badge/status-production-success)
![Type](https://img.shields.io/badge/code-proprietary-lightgrey)
![Stack](https://img.shields.io/badge/stack-ASP.NET%20Core%20%7C%20PHP%20%7C%20MariaDB-blueviolet)

---

## About the project

**Geletec** is a multi-service ecosystem that combines legacy and modern components into a single production platform.

Developed and maintained at **[Concepment](https://www.concepment.com)** under the `Geletec` Azure DevOps organization.

---

## My role

**Backend contributor** — modernization work, bug fixes, feature delivery across the containerized service stack.

I contribute to the Geletec backend services alongside my primary role on the Daribati mobile application.

---

## Tech stack

### Backend
- **ASP.NET Core 8** — modern services (`gt-admin`, `gt-blazor`, `gt-main-server`)
- **PHP 5.6 / Zend Framework 1** — legacy web app (`genius-tracker-web`)
- **C#** — .NET services, Blazor UI

### Data layer
- **MariaDB 10.4**
  - Master DB (configuration, devices)
  - Customer-scoped slave DBs (isolated per-tenant data)
- **Migration-tracked schema changes** — all DB changes versioned as SQL files

### Infrastructure
- **Docker Compose** — the full stack runs in containers via `docker-compose.dev.yml`
- **Linux dev server** (shared, SSH key-based access)
- **Portainer** — container management UI

---

## What I contribute

- Backend feature development across .NET services and the legacy PHP web app.
- Schema changes with migration tracking in `migrations/`.
- Container orchestration via Docker Compose on the dev server.
- Code review and PR workflow on the `develop` branch (no direct pushes to `master` — CI must pass, merges to `master` trigger auto-deploy).

---

## Collaboration

- **Azure DevOps** (`Geletec` organization) — `develop → feature/* → PR` workflow, CI-gated merges, Agile delivery.
- Code review required on every merge.
- Shared dev server environment with the rest of the engineering team.

---

## Links

- 🏢 Company: **[Concepment](https://www.concepment.com)**

---

## Why no code here?

Geletec's source code is the property of Concepment and its customers. This repository documents my professional contribution without disclosing proprietary code, infrastructure details, or confidential business logic.

For a technical discussion of the architecture or specific contributions — feel free to reach out.
