# Contributing to Azmara Labs projects

Thanks for your interest in contributing. This file describes the general
workflow used across `azmara-labs` repositories. Individual repos may have
their own `CONTRIBUTING.md` with project-specific setup and conventions —
that takes precedence over this one when it exists.

## Workflow

We use [GitHub Flow](https://docs.github.com/en/get-started/using-github/github-flow):
one long-lived branch (`main`), short-lived feature branches, pull requests.
No `develop`/`release`/`hotfix` branches.

1. Branch off `main`
2. Make your change, with tests
3. Open a pull request against `main`
4. CI must pass (build, test, type-check, lint, security audit)
5. Squash-merge once approved

`main` is protected — direct pushes aren't possible, required checks must
pass, and (once the project has more than one maintainer) at least one
approving review is required.

## Contributor License Agreement (CLA)

First-time contributors need to sign our CLA before a PR can merge. A bot
will comment on your first PR with instructions — it's a one-time,
one-comment process.

## Commit messages

[Conventional Commits](https://www.conventionalcommits.org/): `type: description`
(`feat`, `fix`, `docs`, `chore`, `refactor`, `test`, `ci`). Imperative mood
("add" not "added"). No AI-attribution trailers.

## Security

Found a vulnerability? Please use GitHub's private vulnerability reporting
(the "Report a vulnerability" option under a repo's Security tab) rather
than a public issue.
