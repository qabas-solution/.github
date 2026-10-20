# Contributing to Qabas

This is how we work together. Keep it simple, keep it consistent.

## Workflow

1. Pick an issue, or open one if it does not exist yet.
2. Create a branch from `main`.
3. Make small, focused commits.
4. Open a pull request and request a review.
5. After approval, squash and merge, then delete the branch.

Nobody pushes directly to `main`.

## Branch names

Lowercase, words separated by dashes, short and descriptive.

| Prefix | Use for | Example |
|---|---|---|
| `feature/` | New functionality | `feature/login-page` |
| `fix/` | Bug fixes | `fix/api-500-error` |
| `docs/` | Documentation only | `docs/update-readme` |
| `refactor/` | Code cleanup with no behavior change | `refactor/auth-service` |
| `chore/` | Maintenance and dependencies | `chore/update-dependencies` |

## Commit messages

Format: `type: short description` in English, imperative mood, no period at the end.

| Type | Use for |
|---|---|
| `feat` | A new feature |
| `fix` | A bug fix |
| `docs` | Documentation |
| `refactor` | Restructuring without changing behavior |
| `test` | Tests |
| `chore` | Maintenance and tooling |

Examples:

```
feat: add braille upload screen
fix: handle empty image response
docs: describe local setup
```

## Pull requests

- The title follows the commit format, for example `feat: add dashboard theme editor`.
- Fill in the pull request template.
- Keep it small. One pull request, one purpose.
- At least one approval is required. For changes that touch another track, ask someone from that track to review.
- Automated checks must pass before merging.
- Resolve every review comment before merging.
- Use **Squash and merge**.

## Versions

We use semantic versioning: `v1.0.0`. Before launch we use `v0.x.x`.

- Bug fix: `v1.0.1`
- New feature: `v1.1.0`
- Breaking change: `v2.0.0`

## Secrets

Never commit passwords, API keys, tokens, `.env` files, or webhook URLs. Add `.env` to `.gitignore`.

If a secret was committed by mistake, tell the Team Lead right away and rotate it. Deleting the commit is not enough.

## Need help?

Ask in our team Discord server. For a problem that needs tracking, open an issue.
