# Contributing

Thank you for your interest in the Odin Bilişim open-source tools (`odin-agent-sdk`, `odin-cli`). Both are experimental; please open an issue to discuss larger changes before sending a pull request.

## Code Quality & Engineering Standards

Please follow these conventions:

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
   - PRs must pass the GitHub Actions checks.
4. **Security:**
   - Never commit API keys, tokens or `.env` files. See [SECURITY.md](SECURITY.md) for reporting vulnerabilities.

## Development Workflow

1. Fork the repo and clone locally.
2. Create your topic branch: `git checkout -b feat/my-new-feature`.
3. Verify linting and tests locally before pushing.
4. Open a Pull Request against `main`.
