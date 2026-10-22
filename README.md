# Geletec Ecosystem

> ⚠️ **Enterprise project — source code is proprietary and not published here.**
> This repository exists as a portfolio placeholder to document my role and contributions on the Geletec ecosystem at **Concepment**.

![Status](https://img.shields.io/badge/status-production-success)
![Type](https://img.shields.io/badge/code-proprietary-lightgrey)
![Stack](https://img.shields.io/badge/stack-ASP.NET%20Core%20%7C%20Blazor%20%7C%20PHP%20%7C%20MariaDB-blueviolet)

---

## About the project

**Geletec** is a multi-service ecosystem that combines legacy and modern components into a single production platform.

Developed and maintained at **[Concepment](https://www.concepment.com)** under the `Geletec` Azure DevOps organization.

---

## My role

**Full-Stack Developer** — frontend and backend contributions across the modern .NET stack and the legacy PHP web app.

I work on both sides of the platform: building and maintaining the user-facing web interfaces as well as the backend services, databases, and container orchestration that power them.

---

## Tech stack

### Frontend
- **Blazor (ASP.NET Core 8)** — modern web UI (`gt-blazor`)
- **Razor views / HTML / CSS / JavaScript** — admin interfaces (`gt-admin`)
- **Zend Framework 1 views (PHP 5.6)** — legacy web app UI (`genius-tracker-web`)
- Responsive layouts, form handling, data tables, dashboards

### Backend
- **ASP.NET Core 8** — modern services (`gt-admin`, `gt-blazor`, `gt-main-server`)
- **C#** — .NET services and controllers
- **PHP 5.6 / Zend Framework 1** — legacy web application
- REST APIs, authentication, business logic

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

- **Frontend development** — Blazor components, Razor views, admin dashboards, forms, data tables, and UI maintenance across the modern .NET and legacy PHP interfaces.
- **Backend development** — feature implementation and bug fixes across .NET services (`gt-admin`, `gt-blazor`, `gt-main-server`) and the legacy PHP web app.
- **Database work** — schema changes with migration tracking in `migrations/`, cross-tenant data handling (master DB + customer-scoped slave DBs).
- **Container orchestration** — Docker Compose configurations, service management, and dev server deployment via `docker-compose.dev.yml`.
- **Code review** and PR workflow on the `develop` branch (no direct pushes to `master` — CI must pass, merges to `master` trigger auto-deploy).

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
