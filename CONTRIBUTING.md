# Contributing

Thanks for helping improve k-neco-lab projects.

## Getting started
- Search existing issues and pull requests before opening a new one.
- Keep changes focused. Avoid mixing unrelated refactors with functional changes.

## Issues
We use issue forms to capture the information needed to triage and fix problems.
Please avoid including secrets, credentials, or private user data.

## Pull requests
### Titles
Use Conventional Commits in PR titles:

`type(scope): subject`

Allowed types:
- feat, fix, refactor, chore, docs, build, ci, test, perf

Examples:
- `fix(api): handle empty token response`
- `feat(cli): add dry-run option`

### Merge policy
Repositories may be configured as squash-merge only. In that case:
- The squash commit title is derived from the PR title.
- Keep the PR description meaningful; it may be used as the squash commit message.

### Testing
- Add or update tests where appropriate.
- Include the command you ran in the PR description (or explain why tests are not applicable).

## Security
Do not open public issues for security vulnerabilities.
