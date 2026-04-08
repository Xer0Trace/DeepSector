# Contributing to DeepSector

This project is built to scale into a full system, not just a static site. Follow these guidelines to keep everything clean, consistent, and maintainable.

---

## General Rules

* Keep code simple and readable
* Do not over-engineer
* Avoid unnecessary dependencies
* Think in systems, not just features
* Security should always be considered

---

## Branching Strategy

Never work directly on `main`.

Use:

* `main` → stable production-ready code
* `dev` → active development
* `feature/*` → new features
* `fix/*` → bug fixes

Example:

```
feature/navbar-mobile
fix/contact-form-validation
```

---

## Workflow

1. Pull latest changes from `dev`
2. Create a new branch
3. Make your changes
4. Test locally
5. Commit cleanly
6. Push branch
7. Open a pull request into `dev`

---

## Commit Format

Keep commits clear and intentional.

Examples:

```
feat: add mobile navigation toggle
fix: correct CSS overflow issue on hero section
refactor: restructure service cards layout
```

---

## Code Style

* Use consistent naming (camelCase for JS, kebab-case for CSS)
* Keep functions small and focused
* Avoid inline styles unless necessary
* Group related logic together

---

## Folder Discipline

Do not randomly create folders.

Follow the defined structure. If something new is needed, discuss it or keep it consistent with existing patterns.

---

## Pull Requests

Before submitting:

* Make sure code works
* Remove unused code
* Keep changes focused
* Add a short description of what was done

---

## Mindset

We are not just building pages.

We are building a system that will expand into full stack applications and services.

Write code that can grow.
