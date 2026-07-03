# Fenix

A modular ecosystem for building modern Laravel applications.

Fenix is a collection of independent packages designed to work together while remaining fully reusable in any Laravel project. Each package has its own repository, release cycle, and documentation.

## Packages

### Development

- **fenix/lab** — Development sandbox and showcase application.
- **fenix/hello** — Starter package for new projects.
- **fenix/dev-kit** — Development toolkit, documentation, AI agents, and project standards.

### UI

- **fenix/ui** — Reusable UI components and frontend foundation.
- **fenix/theme-default** — Default theme for the Fenix ecosystem.

### Core

- **fenix/core** — Core framework functionality.
- **fenix/admin** — Administration panel built on top of Fenix.

## Architecture

```
Application
      │
      ▼
fenix/admin
      │
      ▼
fenix/core
      │
      ├──────────────┐
      ▼              ▼
fenix/ui   fenix/theme-default

Development

fenix/dev-kit
fenix/hello
fenix/lab
```

## Goals

- Modular architecture
- Independent package versioning
- Laravel-first approach
- AI-friendly development workflow
- Long-term maintainability

---

Built with ❤️ using Laravel.
