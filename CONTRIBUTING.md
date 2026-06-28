# Contributing

Most repositories under the [`ukwebmarketing`](https://github.com/ukwebmarketing) GitHub organisation are **private client repositories** maintained by the UK Web Marketing team. They are not open to external contribution.

A small number of public repositories (this `.github` org-profile repo, occasional reference snippets) accept contributions on the terms below.

## Before you open an issue or pull request

1. Confirm the repository is public and is not labelled `archive`, `internal`, or `client-site`.
2. Search existing issues and pull requests first — duplicates are closed.
3. Read the [Code of Conduct](./CODE_OF_CONDUCT.md).

## Reporting bugs

Open an issue with:

- A clear title (`<area>: <one-line summary>`)
- The version, browser, and operating system where applicable
- Reproduction steps and expected vs actual behaviour
- A minimal reproducible example, if the bug is in code

**Security issues do not go in GitHub issues.** Email [security@ukwebmarketing.com](mailto:security@ukwebmarketing.com) — see [SECURITY.md](./SECURITY.md).

## Proposing a change

For anything larger than a typo, open an issue first and wait for a maintainer to agree on the approach. We do not merge pull requests that arrive without prior discussion.

## Pull-request checklist

- One logical change per pull request
- Commit messages follow [Conventional Commits](https://www.conventionalcommits.org/) (e.g. `fix:`, `feat:`, `chore:`, `docs:`)
- The pull-request description names the issue it resolves (`Closes #N`)
- CI is green; no `gitleaks` or CodeQL findings introduced
- No secrets, no client data, no production URLs that expose tenant identifiers

## Reviewing and merging

A maintainer reviews within a UK business week. Merges use squash-merge. The pull-request title becomes the commit message — keep it tidy.

## Questions

For anything not covered here, email [hello@ukwebmarketing.com](mailto:hello@ukwebmarketing.com).
