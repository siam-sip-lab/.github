# Contributing

This guide applies to every repository in siam-sip-lab unless the repository has its own.
Full rules live in the [engineering handbook](https://github.com/siam-sip-lab/engineering-handbook/blob/main/README.md).

## Workflow (GitHub Flow)

1. Pick or open an **issue**. No issue, no branch.
2. Branch from the latest `main`: `<type>/<issue#>-<short-desc>`
   ([branching](https://github.com/siam-sip-lab/engineering-handbook/blob/main/docs/standards/branching.md)).
3. Commit small, meaningful changes.
4. Open a **draft pull request** early; fill in the template; add `Closes #<issue>`.
5. PR title follows [Conventional Commits](https://github.com/siam-sip-lab/engineering-handbook/blob/main/docs/standards/commit-messages.md).
   It becomes the commit message on `main`.
6. Keep it small: about 400 changed lines or fewer.
7. CI green + review approved ([code review](https://github.com/siam-sip-lab/engineering-handbook/blob/main/docs/standards/code-review.md)).
8. **Squash and merge.** The branch is deleted automatically.

## Never

- Push directly to `main` (it is blocked).
- Use `git push --force`; use `--force-with-lease`.
- Commit secrets, customer data, or files larger than 1 MB.
