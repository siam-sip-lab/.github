# Security policy

**Do not open a public issue for a security problem or a leaked secret.**

## If you find a vulnerability

Report it privately to an organization owner, or use **Security → Report a
vulnerability** on the repository if private reporting is enabled.

## If a secret was committed (password, token, key)

1. **Rotate it immediately** — revoke and replace. Treat it as leaked from the
   moment it was pushed, even if the commit is deleted.
2. Tell an organization owner.
3. Only then remove it from history (owners follow the secret-leak runbook).
