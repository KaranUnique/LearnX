# Contributing to LearnX

Thanks for your interest in contributing! This document explains how to set up the project locally, the branch and PR workflow, and basic code style expectations.

## Getting started locally

1. Fork the repo and clone your fork locally.

```powershell
git clone https://github.com/tilakjain619/LearnX.git
cd LearnX
npm install
npm run dev
```

2. Open http://localhost:3000 to verify the app runs.

## Branching & PRs

- Work from feature branches: `feature/short-description` or `fix/short-description`.
- Keep `main` protected and up-to-date. Open a pull request against `main` when ready.
- Provide a clear PR description and link any related issue(s).

## Commit messages

Use Conventional Commits style where convenient, for example:

- `feat: add new learning page`
- `fix: correct types in user model`
- `chore: update dependencies`

## Coding style

- The project uses TypeScript and Next.js conventions.
- Follow the existing formatting and linting rules. If Prettier and ESLint scripts exist, run them before opening a PR:

```powershell
npm run lint
npm run format
```

## Tests

- If tests are present, run them locally before requesting review. Example:

```powershell
npm test
```

If there are no tests yet, open an issue proposing tests and we can add basic coverage.

## How to propose changes

- Open an issue first to discuss the change.

## Reporting bugs

- Open an issue with steps to reproduce, Node/npm versions, and any relevant logs.

## Code of conduct

Please be respectful and constructive. If you need a formal code of conduct added, we can add one.
