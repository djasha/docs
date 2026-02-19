# AGENTS

This repository is the published documentation surface for DealDash.

## Agent Rules

1. Treat `docs.json` as navigation source of truth.
2. Update docs in the same change as behavior/API changes.
3. Run link validation before commit:

```bash
pnpm docs:check
```

4. Keep internal handbooks current:
   - `internal/*`
   - `agents/*`
   - `operations/*`

5. Do not remove safety or troubleshooting docs without replacement.
