# Contributing to Odin Informatics

Thank you for your interest in contributing to the Odin Informatics open-source ecosystem!

## Code Quality & Engineering Standards

All contributions must follow our high-reliability standards:

1. **Type Safety:** 
   - Python: Strict typing verified with `mypy`.
   - TypeScript: Strict mode (`noImplicitAny`, strict null checks).
2. **Commit Conventions:**
   We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:
   - `feat:` for new capabilities or user-facing changes.
   - `fix:` for bug fixes.
   - `docs:` for documentation updates.
   - `test:` for adding or improving test coverage.
   - `refactor:` for code structure improvements with no behavior change.
3. **Automated Testing:**
   - Any new feature or bugfix must be accompanied by automated unit or integration tests.
   - PRs must pass all matrix tests on GitHub Actions.

## Development Workflow

1. Fork the repo and clone locally.
2. Create your topic branch: `git checkout -b feat/my-new-feature`.
3. Verify linting and tests locally before pushing.
4. Open a Pull Request against `main`.
