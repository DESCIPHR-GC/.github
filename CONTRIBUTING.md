# Contributing to DESCIPHR-GC repositories

Each repository has its own CONTRIBUTING.md with project rules; this file is the default for any that
does not. The rules below apply everywhere.

- Every change starts from an issue. One issue, one feature branch from `dev`, one pull request into
  `dev`. `main` receives tagged releases only.
- Pull requests need passing checks and one approval from someone other than the author. Changes to
  model specifications and protected tests also need a code-owner review.
- Commit messages include `Issue: #<n>` and `Version: <x.y.z.w>`.
- Model changes come with documentation: mathematical description, assumptions with rationale and
  evidence, and verification.
- Never commit data under a data use agreement, record-level registry data, credentials, or tokens.
- Work done with AI coding assistants follows the same review rules as any other code; the author is
  responsible for every line.
