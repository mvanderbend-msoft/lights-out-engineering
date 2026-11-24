# Copilot instructions

<!-- ✏️ Starter file. A cloud agent can't ask you questions, so write down what it would otherwise ask. Keep it short. -->

## What this repo is

One or two lines: what the product does and how the code is organised (for example `backend/` = API, `frontend/` = web app).

## Build and test

```bash
npm run install:all      # install everything
npm --prefix backend run build
npm --prefix frontend run build
npm test                 # run all tests
```

## Before you open a pull request

- The build and all tests pass.
- New behaviour has a test.
- The PR description says what changed, why, and how to check it.
- The PR body contains `Closes #<issue>`.

## Leave these alone

- Generated files and lock files you didn't need to change.
- `.github/workflows/` unless the issue is about CI.
- Anything outside the folder your task is about.

## When you're not sure

- Pick the simplest option that matches existing code, and explain the choice in the PR.
- If the issue is unclear or too big, say so in the PR instead of guessing.
