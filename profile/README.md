````md
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
- **fenix/localization** — Localization foundation for managing locales, translations, and runtime language support.
- **fenix/media-library** — Media management with uploads, image processing, storage, and reusable file handling.

## Modules
- **fenix/blog** — Blogging module with posts, categories, tags, pages, and content management.

## Architecture

```text
Application
└── fenix/admin
    └── fenix/core
        ├── fenix/ui
        ├── fenix/theme-default
        ├── fenix/localization
        └── fenix/media-library

Modules
└── fenix/blog

Development
├── fenix/dev-kit
├── fenix/hello
└── fenix/lab
```

## Goals

- Modular architecture
- Independent package versioning
- Laravel-first approach
- AI-friendly development workflow
- Long-term maintainability

---

Built with ❤️ using Laravel.
````
