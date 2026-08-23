# React Learning Lab

Hands-on React + TypeScript learning repository documenting my transition from Angular to React.

## Purpose

This repository contains the **actual React implementation work** for the React learning track in [`oboikanyego/software-engineer-learning-roadmap`](https://github.com/oboikanyego/software-engineer-learning-roadmap).

The roadmap repository tracks lessons, due dates, prerequisites, System Design work and learning evidence. This repository holds React source code, tests and feature pull requests.

## Current learning cycle

Restart date: **26 August 2026**

Current lesson: **R01 — React fundamentals: JSX, rendering and project setup**

Roadmap issue: https://github.com/oboikanyego/software-engineer-learning-roadmap/issues/6

## Working agreement

- `main` stays stable.
- Every lesson is developed on its own branch.
- Do not push lesson implementation directly to `main`.
- Each lesson ends with a pull request.
- A lesson only counts when its Definition of Done is satisfied and I can explain the code in my own words.

### Branch naming

```text
learn/r01-react-fundamentals
learn/r02-components-props-composition
learn/r03-state-events-forms-effects
```

### Commit examples

```text
learn(r01): initialize Vite React TypeScript app
learn(r01): add reusable profile components
learn(r01): demonstrate JSX and conditional rendering
docs(r01): document React vs Angular mental model
```

## Pull request flow

```text
Roadmap issue -> lesson branch -> small commits -> test/build -> PR -> evidence -> merge -> close lesson
```

See [`docs/WORKFLOW.md`](docs/WORKFLOW.md) for the full workflow.

## Important

This is a learning repository, but the code should still be treated like production work: clear naming, focused commits, testing, documentation and explicit design decisions.
