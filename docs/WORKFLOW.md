# React Lesson Workflow

Use the same engineering workflow for every React lesson.

## 1. Start from `main`

```bash
git checkout main
git pull
```

## 2. Create the lesson branch

Example for R01:

```bash
git checkout -b learn/r01-react-fundamentals
```

Branch format:

```text
learn/rXX-short-topic
```

## 3. Build the lesson outcome

Keep the branch focused on the lesson's Definition of Done.

For R01, the implementation should be created by the learner on the R01 branch. Do not pre-build future lessons into the same PR.

## 4. Commit in small meaningful steps

Examples:

```text
learn(r01): initialize Vite React TypeScript app
learn(r01): add reusable profile components
learn(r01): demonstrate JSX and conditional rendering
docs(r01): document React vs Angular mental model
```

Avoid messages such as `update`, `changes`, `done`, or `final`.

## 5. Validate before pushing

At minimum:

```bash
npm run build
```

Once tests exist, run the appropriate test command too.

Also inspect the application manually and check the browser console.

## 6. Push the lesson branch

```bash
git push -u origin learn/r01-react-fundamentals
```

## 7. Open a pull request into `main`

PR title format:

```text
R01 · Build React fundamentals learning lab
```

The PR must explain:

- what changed;
- what was learned;
- how it was tested;
- one problem and its resolution;
- key design choices;
- an interview-ready explanation.

## 8. Link evidence back to the roadmap

The source-of-truth learning ticket remains in:

https://github.com/oboikanyego/software-engineer-learning-roadmap

After the PR is ready, add its link to the relevant lesson evidence and roadmap issue.

## 9. Merge only when the lesson is complete

A watched tutorial is not completion. Merge when:

- the Definition of Done is satisfied;
- build/tests pass;
- evidence exists;
- you can explain the lesson without reading notes.

## Repository boundaries

### This repository

Contains:

- React application source;
- components;
- hooks;
- state-management code;
- tests;
- application README/documentation tied to the code;
- React lesson PR history.

### `software-engineer-learning-roadmap`

Contains:

- learning tickets;
- prerequisites;
- dates and progress;
- System Design diagrams;
- learning evidence/retrospectives;
- links to code PRs.
