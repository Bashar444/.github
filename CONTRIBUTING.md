# Contributing

Thank you for considering a contribution. This guide applies to every repository under [@bashar-al-agha](https://github.com/bashar-al-agha) that does not ship its own `CONTRIBUTING.md`.

## Before you start

- Search the existing issues first. For anything larger than a small fix, open an issue and agree the approach before writing code.
- Do **not** report security problems in public. Follow [SECURITY.md](SECURITY.md).
- By taking part you agree to the [Code of Conduct](CODE_OF_CONDUCT.md).

## Workflow

1. Fork the repository and create a branch from `main`, for example `git switch -c fix/short-description`.
2. Keep commits focused and use [Conventional Commits](https://www.conventionalcommits.org/): `feat:`, `fix:`, `docs:`, `test:`, `refactor:`, `perf:`, `chore:`.
3. Sign off every commit with `git commit -s`. The sign-off certifies the [Developer Certificate of Origin](https://developercertificate.org/): you wrote the change, or you have the right to submit it under the project's licence.
4. Run the tests and linters locally, and add tests for new behaviour.
5. Open a pull request against `main`, complete the template and link the issue it resolves (`Closes #123`).

## Pull request checklist

- Tests pass locally and in continuous integration.
- Behaviour changes are documented in the README or docs and in the `Unreleased` section of `CHANGELOG.md`.
- No secrets, credentials, personal data or large binary files are committed.

## Licensing of contributions

Unless a repository states otherwise, contributions are accepted under that repository's licence (inbound = outbound). In an MIT-licensed project your contribution is licensed under MIT.

## Research software

Where a repository supports academic work, any change that affects numerical output must include a reproducible check: a test with a fixed random seed and a stated tolerance against a reference implementation. Published results must never change silently. Cite the methods and datasets involved in the pull request description.
