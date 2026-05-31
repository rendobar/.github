# Contributing to Rendobar

Thanks for your interest in contributing. These guidelines apply across all Rendobar repositories unless a repo overrides them with its own `CONTRIBUTING.md`.

## Ways to contribute

- **Report bugs.** Open an issue on the relevant repository with clear reproduction steps.
- **Suggest features.** Open a feature request issue describing the problem you're solving.
- **Improve docs.** Fixes and clarifications to [rendobar/docs](https://github.com/rendobar/docs) are always welcome.
- **Submit code.** See the workflow below.

## Development workflow

1. Fork the repository and create a branch from `main`.
2. Make your change. Keep commits focused and write clear commit messages describing **what** changed and **why**.
3. Add or update tests where applicable.
4. Run the repo's lint and test commands before opening a PR.
5. Open a pull request against `main` and fill out the PR template.

## Pull request expectations

- Reference the issue your PR addresses, if one exists.
- Keep PRs scoped to a single concern. Smaller PRs review faster.
- Describe how you tested the change.
- CI must pass before review.

## Commit messages

Use clear, imperative commit subjects (`fix: handle empty input URL`). Most repos here follow [Conventional Commits](https://www.conventionalcommits.org). Match the convention already used in the repo you are contributing to. Run `git log --oneline -20` first to see the local style.

## Code of conduct

By participating you agree to uphold our [Code of Conduct](./CODE_OF_CONDUCT.md). Be respectful and constructive.

## Questions

Open a discussion or issue on the relevant repo, or check [rendobar.com/docs](https://rendobar.com/docs).
